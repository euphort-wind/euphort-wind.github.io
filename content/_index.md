---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Doctoral Candidate
          company: University of Gothenburg
          company_url: 'https://www.gu.se/en'
          company_logo: lgu
          location: Gothenburg
          date_start: '2023-05-23'
          date_end: ''
          description: |2-
              Responsibilities include:
              * PhD Research: Architectural Approach to SE4ML
              * Teaching: "Agile Software Project Management" course
              * Supervision: BSc & MSc Theses  

        - title: Lecturer
          company: Ural Federal University
          company_url: 'https://urfu.ru/en/'
          company_logo: lurfu
          location: Ekaterinburg
          date_start: '2022-09-01'
          date_end: '2023-05-23'
          description: |2-
              Responsibilities include:
              * PhD Research: Organizational System Management
              * Teaching: "Business Intelligence Tools" & "Internet Marketing" courses
              * Departmental Duties

        - title: Project Manager
          company: SPV
          company_url: 'https://spv.se/en/about-your-pensions/'
          company_logo: lspv
          location: Sundsvall
          date_start: '2021-09-01'
          date_end: '2021-12-01'
          description: |2-
              Responsibilities include:
              * Product Management
              * SCRUM Project Management
              * Frontend Development

        - title: Business Analyst
          company: Naumen
          company_url: 'https://www.naumen.ru/en/'
          company_logo: lnaumen
          location: Ekaterinburg
          date_start: '2019-07-01'
          date_end: '2020-08-31'
          description: |2-
              Responsibilities include:
              * ITSM365 Product Management
              * Business Analysis
              * Customer Support  
    design:
      columns: '2'

  - block: collection
    id: recent
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation

  - block: portfolio
    id: projects
    content:
      title: Music
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Events'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_start: '2025-09-10'
          icon: seaa
          organization: Speaker, Euromicro DSD/SEAA (Advanced Applications), Salerno
          organization_url: https://dsd-seaa.com/
          title:  ECMFA Conference 2025
        - date_start: '2025-06-10'
          icon: staf
          organization: Speaker, STAF (Software Technologies), Koblenz
          organization_url: https://conf.researchr.org/home/staf-2025/ecmfa-2025
          title:  ECMFA Conference 2025
        - date_start: '2025-04-10'
          icon: gaia2
          organization: Participant, Artificial Intelligence Alliance, Gothenburg
          organization_url: https://www.gaia.fish/
          title:  GAIA Conference 2025
        - date_start: '2025-03-31'
          icon: sac
          organization: Speaker, ACM SAC (Applied Computing), Catania
          organization_url: https://www.sigapp.org/sac/sac2025/ 
          title:  SIGAPP SAC Conference 2025
        - date_start: '2024-04-15'
          icon: cain
          organization: Speaker, IEEE/ACM CAIN (AI Engineering), Lisbon
          organization_url: https://conf.researchr.org/home/cain-2024
          title:  CAIN Conference 2024
        - date_start: '2024-04-14'
          icon: icse
          organization: Participant, IEEE/ACM ICSE (Software Engineering), Lisbon
          organization_url: https://conf.researchr.org/home/icse-2024
          title:  ICSE Conference 2024
        - date_start: '2024-03-27'
          icon: gaia
          organization: Participant, Artificial Intelligence Alliance, Gothenburg
          organization_url: https://www.gaia.fish/
          title:  GAIA Conference 2024
        - date_start: '2023-10-30'
          icon: siren
          organization: Speaker, Chalmers University, Gothenburg
          organization_url: https://sirensweden.github.io/#swedish-requirements-engineering-network 
          title:  SiREN Meeting 2023
        - date_start: '2023-02-01'
          icon: ppk
          organization: Participant, Ural Federal University, Ekaterinburg
          organization_url: https://urfu.ru/en/
          title: Project-Based Learning Qualification 2023
        - date_start: '2021-09-01'
          icon: ovik
          organization: Participant, High Coast Hub, Örnsköldsvik
          organization_url: https://highcoasthub.com/the-high-coast-international-day
          title: The High Coast International Day 2021
        - date_start: '2021-04-23'
          icon: ivus
          organization: Participant, Kaunas University of Technology, Kaunas
          organization_url: https://www.knf.vu.lt/ivus2021
          title: IVUS Conference 2021
        - date_start: '2021-03-01'
          icon: coursera
          organization: Participant, Erasmus University, Rotterdam
          organization_url: https://www.coursera.org/account/accomplishments/verify/4Y7H3PTZGEKX
          title: Innovation Management Course 2021
        - date_start: '2018-03-01'
          icon: geek
          organization: Participant, Digital Ural Geek Camp, Abzakovo
          organization_url: https://www.facebook.com/UGCmgn/
          title: Ural Geek Camp 2018
    design:
      columns: '2'
      
  - block: collection
    id: posts
    content:
      title: Wanderlust
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
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
      view: list
      columns: '2'
  
  - block: contact
    id: contact
    content:
      title: Contacts
      email: indykov@chalmers.se
      address:
        street: 5 Hörselgången (office 411)
        city: Gothenburg
        postcode: 'Sweden'
        country: Sweden
        country_code: SE
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '57.70629'
        longitude: '11.93853'  
      # Automatically link email and phone or display as text?
      autolink: true
      design:
      columns: '2'
---
