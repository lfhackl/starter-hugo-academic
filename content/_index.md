---
# Leave the homepage title empty to use the site title
title: Lucas Hackl
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: lucas-hackl
      # Override your bio text from `authors/admin/_index.md`?
      text: Lucas Hackl is a Lecturer in Mathematical Physics in the School of Mathematics and Statistics at the University of Melbourne. He is currently funded through a Feodor Lynen Research Fellowship of the Alexander von Humboldt Foundation. He is part of the <a href="https://ms.unimelb.edu.au/research/groups/details?gid=18%22">Mathematical Physics Research Group</a>.
  - block: experience
    id: experience
    content:
      title: Research
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Lecturer in Mathematical Physics
          company: University of Melbourne
          company_url: 'https://ms.unimelb.edu.au/research/groups/details?gid=18%22'
          company_logo: org-gc
          location: Melbourne, Australia
          date_start: '2022-03-01'
          date_end: ''
          description: 
        - title: Feodor Lynen Research Fellow
          company: University of Melbourne
          company_url: 'https://ms.unimelb.edu.au/research/groups/details?gid=18%22'
          company_logo: org-x
          location: Melbourne, Australia
          date_start: '2021-01-01'
          date_end: ''
          description: 
        - title: Postdoctoral Fellow
          company: University of Copenhagen - Københavns Universitet
          company_url: 'https://qmath.ku.dk/'
          company_logo: org-x
          location: Copenhagen, Denmark
          date_start: '2019-09-01'
          date_end: '2020-12-31'
          description: 
        - title: Postdoctoral Fellow
          company: Max Planck Harvard Research Center for Quantum Optics
          company_url: 'https://www.mph-quantum.mpg.de/'
          company_logo: mphq
          location: Munich, Germany
          date_start: '2018-08-01'
          date_end: '2019-08-31'
          description:
    design:
      columns: '2'
  - block: accomplishments
    id: accomplishments
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
        - certificate_url:
          date_end: ''
          date_start: '2022-09-25'
          description: ''
          organization: Australian Research Council
          organization_url: https://www.arc.gov.au/
          title: Discovery Early Career Researcher Award (DECRA)
          url: ''
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2019-07-25'
          description: ''
          organization: Alexander von Humboldt Foundation
          organization_url: https://www.humboldt-foundation.de/en/
          title: Feodor Lynen Research Fellowship
          url: ''
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Penn State Alumni Association
          organization_url: https://gradschool.psu.edu/graduate-school-funding/programs/aada/
          title: Penn State Alumni Association Dissertation Award 2018
          url: ''
        - certificate_url: https://www.coursera.org
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: American Physical Society
          organization_url: https://gradschool.psu.edu/graduate-school-funding/programs/aada/
          title: Brazil-US Exchange Fellowship
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Pennsylvania State University | Department of Physics
          organization_url: https://science.psu.edu/physics
          title: Peter Eklund Award for Scientific Communication
          url: 'https://science.psu.edu/physics/graduate/awards/student-research-awards'
        - certificate_url: 
          date_end: ''
          date_start: '2021-01-25'
          description: ''
          organization: Pennsylvania State University, Department of Physics
          organization_url: 
          title: 66th Linau Nobel Laureate Meeting 2016
          url: ''
        - certificate_url: 
          date_end: ''
          date_start: '2009-01-01'
          description: ''
          organization: Studienstiftung des deutschen Volkes
          organization_url: https://www.studienstiftung.de/en/
          title: Student Scholarship
          url: ''
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
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: lucas.hackl@unimelb.edu.au
      phone: +61 3 834 46492
      address:
        street: 813 Swanston St
        city: Parkville
        region: VIC
        postcode: '3052'
        country: Australia
        country_code: AU
      directions: <a href="https://maps.unimelb.edu.au/point?poi=663141" target="_blank">see directions</a>
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
