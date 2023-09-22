---
# Leave the homepage title empty to use the site title
title:
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
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Creative technologist Intern
          company: Mantis Shrimp Creative
          company_url: ''
          company_logo: org-gc
          location: Bangalore
          date_start: '2021-01-01'
          date_end: ''
          description: |2- 
              * Conceptualization and prototyping of RFID based Installation with Raspbery Pi
              * Data channeling and instrumentation of Kuka Robot
              * Conceptualization and prototyping installation for Pepsico using optic sensors
              * Creating motion graphics clips for VJ sets
              * Consultation and prototyping of Neural network kiosk for targeted advertising and mass deployment
        - title: Assistant Researcher
          company: Indian Sonic Research Organization
          company_url: ''
          company_logo: org-gc
          location: Bangalore
          date_start: '2021-01-01'
          date_end: ''
          description: |2- 
              * 3D printing and prototyping of OpenBCI Ganglion 4channel headset for musical applications and therapy with assitance
              * Setting up of ecological soundstream with Grant smith from SoundTent
              * Accompanying and coordinating with Artists in Residence for their practice
              * Prototyping biofeedback based interactions with EMG sensors (MYOWARE)
              * Creating motion graphics clips for VJ sets
              * Coordinated the final design and devlopment of the IMMSANE website for Yati Durant and Andre Bellmonte
        - title: Spatial Experience designer (VOLUNTEER)
          company: The Reading Room, Under ZKM and Befantastic
          company_url: ''
          company_logo: org-gc
          location: Bangalore
          date_start: '2021-01-01'
          date_end: ''
          description: |2- 
              * Conceptualized the interaction framework of a public story-access platform for a postpandemic population
              * Devised new spatial interaction frameworks based on the Derive, Wayfinding and Paradigmatic/syntagmatic narratives      
   
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 1
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
        - name: ML
          tag: ML
        - name: Music
          tag: music
        - name: Immersive
          tag: immersive
        - name: Biofeedback
          tag: biofeedback
        - name: Art
          tag: art
        - name: 3D
          tag: 3d
        - name: Electronics
          tag: electronics
        - name: Spatial
          tag: spatial
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: 'My Pixelfed'
      text: |-
        <iframe title="Pixelfed Profile Embed" src="https://pixelfed.social/gearworks/embed" class="pixelfed__embed" style="max-width: 100%; border: 0" width="900" allowfullscreen="allowfullscreen">            </iframe><script async defer src="https://pixelfed.social/embed.js"></script>
    design:
      columns: '2'
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
        I try my best to be available at all times but hope.
      # Contact (add or remove contact options as necessary)
      email: georgepanicker2000@gmail.com
      contact_links:
        - icon: mastodon
          icon_pack: fab
          name: DM Me
          link: 'https://mastodon.social/@georgepanicker'

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
