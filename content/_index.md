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



  - block: experience
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: BSc. Mathematics
          company: Radboud University
          company_url: https://www.ru.nl/
          company_logo: radboud_pre-university_college_of_science
          location: Nijmegen
          date_start: '2022-09-04'
          date_end: ''
          description: |2-
              {{% staticref "uploads/transcript.pdf" "newtab" %}}Transcript of Records.{{% /staticref %}}

        
        - title: BSc. Computing Science
          company: Radboud University
          company_url: https://www.ru.nl/
          company_logo: radboud_pre-university_college_of_science
          location: Nijmegen
          date_start: '2022-09-04'
          date_end: ''
          description: |2-
              {{% staticref "uploads/transcript.pdf" "newtab" %}}Transcript of Records.{{% /staticref %}}

        - title: VWO 
          company: Mill-Hill College
          company_url: https://www.millhillcollege.nl/
          company_logo: mill_hill
          location: Goirle
          date_start: '2016-09-04'
          date_end: '2022-08-31'
          description: |2-
              Courses: 
              Physics (10/10), Chemistry (10/10), Biology (9/10), Mathematics B (10/10), Mathematics D (10/10), Latin (10/10), Spanish (10/10), English (9/10), Dutch (8/10).
              Final Project: "Optimizing Black Jack strategies using Reinforcement Learning" (10/10)

              Extracurricular: 
              * Followed 39 ec of BSc Mathematics courses at Radboud during my final years. 
              * Econasium Programme (Tilburg University, extracurricular programme featuring Statistics course) (9.6/10). 
              * Fast-Lane English Programme (finish English curriculum in 5 years instead of 6).
              * Extra course in Spanish.
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'






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
          organization: MPI-SWS Saarbrucken
          organization_logo:
          organization_url: https://cmmrs.mpi-sws.org/
          title: Cornell, Maryland, Max Planck Pre-doctoral Research School
          url: https://cmmrs.mpi-sws.org/
  
        - certificate_url: ''
          date_start: '2023-08-31'
          date_end: ''
          description: |2-
            Two-year extracurricular programme (24 ec.).
            Selection programme, 25 participants per year.
            Involvement with real research; 
            expand bachelor thesis by 12 ec. and do part of it abroad
            
          organization: Radboud Honours Academy
          organization_url: https://www.ru.nl/honoursacademy/bachelor/science/
          title: Radboud Honours Programme Science
          url: https://www.ru.nl/honoursacademy/bachelor/science/

        - certificate_url: ''
          date_start: '2020-08-01'
          date_end: '2021-07-01'
          description: |2-
            In VWO-5 (penultimate year of secondary school);
            Completed 12 ec. at Radboud before official enrollment.
            * Calculus A (10/10, 6 ec.)
            * Calculus B (10/10, 6 ec.) 
          organization: Radboud Pre-University College of Science
          organization_url: https://www.ru.nl/ise/outreach/pre-university-college-science/
          title: Extracurricular BSc Mathematics courses while in secondary school.
          url: https://www.ru.nl/ise/outreach/pre-university-college-science/

        - certificate_url: ''
          date_start: '2021-08-01'
          date_end: '2022-07-01'
          description: |2-
            In VWO-6 (final year of secondary school);
            Completed 39 ec. at Radboud before official enrollment.
            * Group Theory (10/10, 6 ec.)
            * Probability Theory (9.5/10, 3 ec.)
            * Linear Algebra A (10/10, 6 ec.)
            * Linear Algebra B (10/10, 6 ec.)
            * Introduction Mathematics (i.e. sets, proofs, Peano Arithmetic and Dedekind cuts) (10/10, 6 ec.)
            
          organization: Radboud Pre-University College of Science
          organization_url: https://www.ru.nl/ise/outreach/pre-university-college-science/
          title: Extracurricular BSc Mathematics courses while in secondary school.
          url: https://www.ru.nl/ise/outreach/pre-university-college-science/
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
          date_start: '2023-11-27'
          date_end: '2023-11-27'
          description: |2-
            Awarded for outstanding grades among all first year BCs Computer Science
            students in the Netherlands.
            Prize of &euro; 500.
          organization: Royal Dutch Society of Sciences
          organization_logo:
          organization_url: https://khmw.nl/khmw-jong-talent-prijzen-khmw-young-talent-awards/
          title: KHMW Young talent award
          url: https://khmw.nl/khmw-jong-talent-prijzen-khmw-young-talent-awards/

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
          description: Our duo scored 130/150 points on the wizPROF variant of the Dutch Kangaroo contest.
          organization: W4 Kangaroo
          organization_url: https://www.w4kangoeroe.nl/kangoeroe/
          title: W4 Kangaroo Mathematics Contest
          url: https://www.w4kangoeroe.nl/kangoeroe/
    design:
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
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

    # This is where I keep track of summaries
  - block: portfolio
    id: summaries
    content:
      title: Course Summaries
      text: I keep a list of my summaries made for coursework at university. I only publish notes that are of sufficient quality to be read and used by others. If you have annotations, please let me know.
      filters:
        folders:
          - summaries
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

    
  - block: markdown
    id: art
    content:
      title: Art
      subtitle: I enjoy drawing in my free time. You can find my favorite results on [Google Photos](https://photos.app.goo.gl/3rUHNpn8BF1NBmEV6). You can find even more on my [instagram](https://www.instagram.com/matthijs_muis/) page.
      text: |-
        {{< gallery album="drawings_album" >}}
    design:
      columns: '1'






  - block: features
    content:
      title: Programming Languages 
      items:
        - name: C/C++
          description: |2-
            Basic command of C. Some knowledge of STL. Courses:
              * Imperative Programming
              * Hacking in C
              * Operating System Concepts (see project)
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
          description: 'Basic command. Courses: Statistics (see project)'
  
  






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

    
  #- block: tag_cloud
  #  content:
  #    title: Popular Topics
  #  design:
  #    columns: '2'

    
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        You can contact me via email, or get in touch via LinkedIn. I am sometimes active on Instagram, where I post some of my drawings.
      # Contact (add or remove contact options as necessary)
      email: matthijs.muis@ru.nl
      contact_links:
        - icon: instagram
          icon_pack: fab
          name: Instagram
          link: https://www.instagram.com/matthijs_muis/
        - icon: linkedin
          icon_pack: fab
          name: LinkedIn
          link: 'https://nl.linkedin.com/in/matthijs-muis'
    
      # Automatically link email and phone or display as text?
      autolink: false
    design:
      columns: '2'
---
