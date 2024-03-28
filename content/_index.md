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
          date_end: '2023-06-30'
          description: |2-
              Responsibilities include:
              * PhD Research: Organizational System Management
              * Teaching: "Business Analysis Tools" & "Internet Marketing" courses
              * Departamental Duties

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
        - date_start: '2024-03-27'
          description: 'Participant'
          icon: gaia
          organization: Gothenburg Artificial Intelligence Alliance
          organization_url: https://www.gaia.fish/
          title: GAIA conference 2024
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          icon: coursera
          organization: Coursera
          organization_url: https://www.coursera.org
          title: Neural Networks and Deep Learning
          url: ''
        - certificate_url: https://www.edx.org
          date_end: ''
          date_start: '2021-01-01'
          description: Formulated informed blockchain models, hypotheses, and use cases.
          icon: edx
          organization: edX
          organization_url: https://www.edx.org
          title: Blockchain Fundamentals
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: https://www.datacamp.com
          date_end: '2020-12-21'
          date_start: '2020-07-01'
          description: ''
          icon: datacamp
          organization: DataCamp
          organization_url: https://www.datacamp.com
          title: 'Object-Oriented Programming in R'
          url: ''
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
        postcode: '417 56'
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
