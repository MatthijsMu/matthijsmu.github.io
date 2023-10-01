---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin









- block: accomplishments # use the accomplishments format block for Extracurricular activities
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Extra&shy;curricular'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Extracurricular.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_start: '2023-08-06'
          date_end: '2023-08-13'
          description: |2-
            Summer school hosted by MPI-SWS on state-of-the-art research in computer science.
            Engagement in lectures and interaction with a highly international group of faculty and students.
          organization: Hosted by MPI-SWS, Saarbrücken
          organization_url: https://cmmrs.mpi-sws.org/
          title: Cornell, Maryland, Max Planck Pre-doctoral Research School
          url: https://cmmrs.mpi-sws.org/
  
        - certificate_url: ''
          date_start: '2023-08-31'
          date_end: '2025-08-01'
          description: |2-
            2-year extracurricular programme (24 ec.) for extracurricular engagement with real research.
            Selected, 25 participants per year.
          organization: Radboud Honours Academy
          organization_url: https://www.ru.nl/honoursacademy/bachelor/science/
          title: Radboud Honours Programme Science
          url: https://www.ru.nl/honoursacademy/bachelor/science/
  
    design:
      columns: '2'








  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: '2021-09-17'
          date_start: '2021-09-17'
          description: '16th place overall, 9th place in my age class in the national finals. Hosted at TU Eindhoven.'
          organization: 'Dutch Mathematical Olympiad'
          organization_url: https://wiskundeolympiade.nl/docenten/info-in-english
          title: 'Finalist, Dutch Mathematical Olympiad'
          url: https://wiskundeolympiade.nl/docenten/info-in-english
        - certificate_url: ''
          date_end: '2022-07-07'
          date_start: '2022-07-07'
          description: |2- 
              Represented my secondary school (/34 participating member schools of OMO).
              Won the first prize of  &euro; 1200.
              Project title: \"Optimizing Black Jack Strategies using Reinforcement Learning\".
          organization: OMO
          organization_url: https://www.omojaarverslag.nl/verslag2022/f/omoprijzen/omoprijzen-een-bijzondere-motiveringsprijs-voor-leerlingen
          title: 'VWO Final Project Award, 1st place'
          url: https://www.omojaarverslag.nl/verslag2022/f/omoprijzen/omoprijzen-een-bijzondere-motiveringsprijs-voor-leerlingen
        - certificate_url: ''
          date_end: '2019-03-21'
          date_start: '2019-03-21'
          description: 'Our duo scored 130/150 points on the wizPROF variant of the Dutch Kangaroo contest.'
          organization: 'W4 Kangaroo'
          organization_url: https://www.w4kangoeroe.nl/kangoeroe/
          title: 'W4 Kangaroo Mathematics Contest'
          url: https://www.w4kangoeroe.nl/kangoeroe/
    design:
      columns: '2'









  - block: features
    content:
      title: Programming Languages 
      items:
        - name: C/C++
          description: |2-
            'Basic command of C. Some knowledge of STL. Courses:
              * Imperative Programming
              * Hacking in C
              * Operating System Concepts (see projects)'
          icon: c
          icon_pack: fa
        - name: Java
          description: 'Basic command. Some knowledge of Collections API and Threads API. Courses: Object-Oriented Programming'
          icon: java
          icon_pack: fab
        #- name: Python
        #  #description: 100%
        #  icon: python
        #  icon_pack: fab
        - name: Haskell
          icon: arrow-right
          icon_pack: fas
          description: 'Basic command. Courses: Functional Programming'
        - name: SQL
          icon: database
          icon_pack: fas
          description: 'Basic command. Courses: Information Modelling and Databases'
        - name: R
          icon: r-project
          icon_pack: fab
          description: 'Basic command. Courses: Statistics (see projects)'
  
  

  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'

  # This is where I keep track of projects
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

    
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'

    
  #- block: collection
  #  id: featured
  #  content:
  #    title: Featured Publications
  #    filters:
  #      folders:
  #        - publication
  #      featured_only: true
  #  design:
  #    columns: '2'
  #    view: card

    
  #- block: collection
  #  content:
  #    title: Recent Publications
  #    text: |-
  #      {{% callout note %}}
  #      Quickly discover relevant content by [filtering publications](./publication/).
  #      {{% /callout %}}
  #    filters:
  #      folders:
  #        - publication
  #      exclude_featured: true
  #  design:
  #    columns: '2'
  #    view: citation

    
  #- block: collection
  #  id: talks
  #  content:
  #    title: Recent & Upcoming Talks
  #    filters:
  #      folders:
  #        - event
  #  design:
  #    columns: '2'
  #    view: compact

    
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'

    
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        You can contact me via email.
      # Contact (add or remove contact options as necessary)
      email: matthijs.muis@ru.nl
      contact_links:
        - icon: instagram
          icon_pack: fab
          name: Drawings
          link: 'https://www.instagram.com/mathijsmuis/'
        - icon: linkedin
          icon_pack: fab
          name: Networking
          link: 'https://nl.linkedin.com/in/matthijs-muis'
    
      # Automatically link email and phone or display as text?
      autolink: false
    design:
      columns: '2'
---
