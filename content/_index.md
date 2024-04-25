---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Visiting Researcher
          company: ISTI-CNR
          company_url: 'https://www.isti.cnr.it/en/'
          company_logo: org-isti
          location: Pisa, Italy
          date_start: '2023-05-24'
          date_end: ''
          description: |2-
              Research Internship with Antonia Bertolino in  the Software Engineering & Dependable Computing  Research Lab.
              Continue with the efficient E2E test suite execution research line. 
        - title: Visiting Researcher
          company: ISTI-CNR
          company_url: 'https://www.isti.cnr.it/en/'
          company_logo: org-isti
          location: Pisa, Italy
          date_start: '2023-05-24'
          date_end: '2023-08-24'
          description: |2-
              Research Internship with Antonia Bertolino in the Software Engineering & Dependable Computing Research Lab. Researching and developing a Cloud Cost Model to select a cost-efficient Cloud Infrastructure for End-to-End testing
        - title: Assistant Professor
          company: University of Oviedo
          company_url: 'www.uniovi.es'
          company_logo: org-uniovi
          location: Gijón, Asturias
          date_start: '2019-01-20'
          date_end: ''
          description: |2-
              Teaching Subjects in several degrees:
              * Computing Basics
              * Databases
              * Operating Systems
              * System Administration
              * Information Systems
              * Software Process Engineering 
              * Software Architecture
              * Final Degree Projects
              * Social, legal, and ethical issues in Computer Science
              * Administrative Information Management

        - title: Researcher
          company: Software Engineering Research Group
          company_url: 'www.giis.uniovi.es'
          company_logo: org-giis
          location: Gijón, Asturias
          date_start: '2018-11-08'
          date_end: ''
          description: |2-
              Actively involved in research endeavors focusing on Software Engineering and Testing

        - title: Collaborator Professor 
          company: International University of Valencia
          company_url: 'https://www.universidadviu.com/'
          company_logo: org-viu
          location: Valencia, Spain
          date_start: '2019-01-01'
          date_end: '2021-08-31'
          description: |2-
              Co-director of several Msc. Degree Projects and imparting seminars about Privacy Preserving Data Publishing.
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
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
      buttons:
        - name: All
          tag: '*'
        - name: Open
          tag: open
        - name: Closed
          tag: closed
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: publications
    content:
      title: Publications
      text: 
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '10'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Events
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ""
          date_end: ''
          date_start: '2022-09-29'
          description: ''
          icon: org-nvidia
          organization: Nvidia
          organization_url: https://azure.microsoft.com/en-us
          title: Deep Learning Fundamentals
          url: ''
        - certificate_url: ""
          date_end: ''
          date_start: '2022-01-18'
          description: ''
          icon: org-microsoft
          organization: Microsoft
          organization_url: https://azure.microsoft.com/en-us
          title: Azure DP-900 
          url: 'https://www.credly.com/badges/169376f3-85bd-4c34-b0b2-de09a7a4f976?source=linked_in_profile'
        - certificate_url: ""
          date_end: ''
          date_start: '2022-01-21'
          description: ''
          icon: org-microsoft
          organization: Microsoft
          organization_url: https://azure.microsoft.com/en-us
          title: Azure SC-900
          url: 'https://www.credly.com/badges/543c9244-5e58-43c8-80f7-75e78349f936?source=linked_in_profile'
        - certificate_url: ""
          date_end: ''
          date_start: '2022-01-21'
          description: ''
          icon: org-microsoft
          organization: Microsoft
          organization_url: https://azure.microsoft.com/en-us
          title: Azure PL-900
          url: 'https://www.credly.com/badges/7cc83dff-338b-4de9-a41c-a9c40b40a438?source=linked_in_profile'
        - certificate_url: ""
          date_end: ''
          date_start: '2021-07-07'
          description: ''
          icon: org-microsoft
          organization: Microsoft
          organization_url: https://azure.microsoft.com/en-us
          title: Azure AI-900
          url: 'https://www.credly.com/badges/f009557b-5cac-4090-8030-b4b88a4dc988?source=linked_in_profile'
        - certificate_url: ""
          date_end: ''
          date_start: '2021-06-25'
          description: ''
          icon: org-microsoft
          organization: Microsoft
          organization_url: https://azure.microsoft.com/en-us
          title: Azure AZ-900
          url: 'https://www.credly.com/badges/c6e86525-186d-4b17-b99d-1b6b9dcc7fbd?source=linked_in_profile'
        - certificate_url: ''
          date_end: ''
          date_start: '2021-01-01'
          description: 'Credencial Number: 20-CTFL-188015-09'
          icon: org-isqi
          organization: ISQI
          organization_url: https://isqi.org/en/
          title: ISTQB Certified Tester
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: ''
          date_end: ''
          date_start: '2022-04-01'
          description: ''
          icon: org-cambridge
          organization: Cambridge English Language Assessment
          organization_url: https://www.cambridgeenglish.org/exams-and-tests/first/
          title: First Certificate in English
          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
        - certificate_url: ''
          date_end: '2020-12-16'
          date_start: '2020-12-14'
          description: ''
          icon: org-nexoqa
          organization: NexoQA
          organization_url: https://www.nexoqa.com/es-training.html
          title: 'ISTQB Fundamentals Course'
          url: 'https://www.nexoqa.com/es-training.html'
        - certificate_url: ''
          date_end: '2020-12-03'
          date_start: '2020-11-30'
          description: ''
          icon: org-nexoqa
          organization: NexoQA
          organization_url: https://www.nexoqa.com/es-training.html
          title: 'Test Process and QA Team management'
          url: 'https://www.nexoqa.com/es-training.html'
        - certificate_url: ''
          date_end: '2020-12-18'
          date_start: '2020-12-10'
          description: ''
          icon: org-nexoqa
          organization: NexoQA
          organization_url: https://www.nexoqa.com/es-training.html
          title: 'Advanced Agile Testing + DevTestOps'
          url: 'https://www.nexoqa.com/es-training.html'

    design:
      columns: '2'


  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Please! don't hesitate in contact me
      # Contact (add or remove contact options as necessary)
      email: augustocristian@uniovi.es
      phone: +34 985 182 679
      appointment_url: 'https://calendly.com'
      address:
        street: Calle de Luís Ortiz Berrocal - Edificio Polivalente
        city: Gijón
        region: Asturias
        postcode: '33203'
        country: Spain
        country_code: SP
      directions: Enter the Edificio Polivalente, proceed to Module 6, and ascend the stairs to the second floor to reach department 06
      office_hours:
        - 'Monday to Friday 10:00 to 19:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates 
      coordinates:
        latitude: '43.524417'
        longitude: '-5.635028'  
        #info about icons: https://github.com/hugo-mods/icons
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/augustOcristian'
        - icon: researchgate
          icon_pack: fab
          name: Follow me!
          link: 'https://www.researchgate.net/profile/Cristian-Augusto-Alonso'
        - icon: google
          icon_pack: fab
          name: Google Scholar
          link: 'https://scholar.google.com/citations?hl=en&user=oIJLk7MAAAAJ'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
