---
title: Minimum chain partitioning (using Hopcroft-Karp)
summary: Efficient algorithm for a variant of the Box-Stacking problem (essentially a Dilworth chain partitioning problem). Constructs a bipartite matching and solves this with the Hopcroft-Karp Algorithm.
tags:
date: "2022-12-12T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: 'https://github.com/MatthijsMu/Min-Chain-Partitioning'

image:
  caption: An illustration from the explanation of HopCroft-Karp.
  focal_point: Smart
---

### Summary
 One of two practical assignments for the course Algorithms and Datastructures. A variant of the box-stacking problem is given, which essentially comes down to a minimum chain partitioning (also called Dilworth partitioning) problem. This problem can be reformulated as a bipartite matching problem, which is efficiently solved in O(n^2.5) time where n is the size of the poset. 
 
### Implementation

The implementation of Hopcroft-Karp presented here is different from Wikipedia, and faster. There is no distance dictionary for keeping track of the layers. Rather, a BFS lattice is built every BFS iteration, which is then explored backwards in the DFS phase. Nodes are marked as visited, but edges are not: rather, we use a residual graph (like in the Ford-Fulkerson algorithm) to keep track of the direction in which edges may be traversed. This was apparently an approach that Python could execute much faster, because only this approach was what made us pass all the test cases without time limits!

### Contents

The repo contains the problem statement, code, and a report. 

- The problem statement formally states the problem to solve and specifies the input format that the test cases follow.
- The report features a proof of correctness and complexity analysis. 
- The code (to be found in `Solution_Code`) is split up into 2 classes and a main program: 
  1. class Matching (`bipartiteMatching.py`) for solving general bipartite matching problems using Hopcroft-Karp.
  2. class MinChainPartition (`minChainPartition.py`) for solving general minimum-chain partitioning problems. It is backed by the class Matching, of course.
  3. a main program (`main.py`) which contains code specific to solving the box-fitting problem specified in the problem statement. It contains relevant functions to this problem, such as a comparator that defines partial order on the boxes, as well as a function for parsing the specified input format.
- A folder `Test_Cases` containing test cases numbered from 1 to 26, which you can try on the code. The cases are numbered 1 to 26. Each test case consists of two files, namely `<nr>.in` containing input in plain text, and `<nr>.out` containing the required output (the minimum number of box stacks) in a single line of plain text. The test cases are formatted according to the problem statement. 


### Usage

If you want to use the code to solve your own box stacking problem, please read the problem statement to see the required input format. The `main.py` script will wait for input in the specified format and print a minimum number of chains to stdout.

Test cases range in size from 4 to 5000 boxes. To run a test, change directories to `Solution_Code` and start the interpreter; the entry code is in `main.py`, so you run this:
```
../Solution_Code$ python3 main.py
```

The program will wait for input, and you can copy-paste the plain text of a test's `.in` file (hint: `Ctrl`+`a` + `v`) into the terminal (`Ctrl`+`Shift`+`v`) into the terminal. Within **a few seconds** (5 or less, this is Python code, after all...), the program will print an integer, the minimum number of outer boxes. Try this if you are interested, or if you cannot come up with interesting test cases of 5000 boxes yourself.

It should be noted that the main.py part of the program is mainly constructed for testing purposes.


The classes for solving min-chain partitioning problems and bipartite matchings have, however, been intendedly separated from this driver code. These modules can be reused for solving general min-chain partitioning problems or bipartite matchings.
