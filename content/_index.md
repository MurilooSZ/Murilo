---
# Leave the homepage title empty to use the site title
title: home
date: 2022-10-24
type: landing

sections:

  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: Geospatial
          description: 70%
          icon: globe
          icon_pack: fas
        - name: Statistics
          description: 60%
          icon: chart-line
          icon_pack: fas
        - name: 3D Projects
          description: 70%
          icon: draw-polygon
          icon_pack: fas
        - name: Microsoft Office
          description: 80%
          icon: microsoft
          icon_pack: fab
        - name: Python
          description: 50%
          icon: python
          icon_pack: fab
        - name: Resilience
          description: 90%
          icon: handshake
          icon_pack: fas
    
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Trainee Agricultura Digital  
          company: Amaggi - Fazenda Independência
          company_url: 'https://www.amaggi.com.br/'
          company_logo: Sem-título
          location: Santo Antônio do Leste - MT
          date_start: '2023-02-01'
          date_end: '2023-05-30'
          description: |2-
              Responsibilities include:
            - Implementation, maintenance and training of the telemetry system; Planting line projects (operations traffic control); Conservation and maintenance of dangerous stations; Spray and seeder variable rate application configuration; Tool (GIS): Productivity, rain and thematic maps; Configuration and configuration of monitors; Preparation of reports and analysis of operational indicators; Fertilizer range calibration; Support spray nozzle measurement with a digital tool;
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
        - certificate_url: https://drive.google.com/file/d/1yppGgk33H-9vP61uUZs5wJaD-EY4aS9x/view
          date_end: ''
          date_start: '2023-04-06'
          description: Precision agriculture. Remote sensing.
          organization: TECGRAF AGRO
          organization_url: https://tecgraf.com.br/
          title: Sistematização de Culturas utilizando o AgroCAD360 
          url: https://tecgraf.com.br/
        - certificate_url: https://drive.google.com/file/d/1rvfyIUue29tVa2Hy7k0WG8n0nb2QWM8Y/view?usp=drivesdk
          date_end: ''
          date_start: '2023-02-26'
          description: Precision agriculture.
          organization: SOLINFTEC
          organization_url: https://www.solinftec.com/pt-br/
          title: SGPA - Automated Process Management System
          url: https://www.solinftec.com/pt-br/
        - certificate_url: https://drive.google.com/file/d/1RZ00Q4xF61CdHhBP260RmpYuYp9F8LL-/view
          date_end: ''
          date_start: '2023-02-03'
          description: Precision agriculture.
          organization: SENAR-MT
          organization_url: https://ead.senar.org.br/
          title: Digital Agriculture
          url: https://ead.senar.org.br/
    design:
        columns: '2'
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
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
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
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
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
