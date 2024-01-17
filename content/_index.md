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

        - title: Research collaborator
          company: HIVE lab (IIT Kanpur)
          company_url: 'https://home.iitk.ac.in/~gowdhampg/'
          company_logo: HIVE 
          location: Remote
          date_start: '2024-01-12'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Research on musical haptics for [NIME](https://www.nime.org/)

        - title: Haptic Design Technologist
          company: Compossible Umwelten
          company_url: 'https://www.umwelten.xyz/dwelling/'
          company_logo: compossible
          location: Remote
          date_start: '2023-12-09'
          date_end: '2024-01-23'
          description: |2-
              Responsibilities include:

              * Attempted to conceptualize a speculative waveform description language for tactile compositions
              * Research into biosignal acquisition formats
              * Machine listening experiments with EMG data and SuperCollider
    
        - title: Creative Technologist Intern
          company: Mantis Shrimp Creative
          company_url: 'https://www.linkedin.com/company/mantis-shrimp-creative/'
          company_logo: mantis
          location: Bangalore
          date_start: '2023-06-07'
          date_end: '2023-08-07'
          description: |2-
              Responsibilities include:

              * Conceptualization and prototyping of RFID based Installation with Raspberry Pi
              * Data channeling and instrumentation of Kuka Robot
              * Creating motion graphics clips for VJ sets
              * Worked on an interactive installation for the release of a limited edition vodka by Johnnie Walker, in collaboration with Air-ink and Shilo Suleman
    
        - title: Assistant Researcher
          company: Indian Sonic Research Organization
          company_url: 'https://www.theisro.org/'
          company_logo: ISRO
          location: Bangalore
          date_start: '2022-09-01'
          date_end: '2023-06-07'
          description: |2-
              Responsibilities include:

              * 3d printing and prototyping of OpenBCI Ganglion 4 channel headset for musical applications and therapy while assisting Neuroscientist Nikhil Prabhu
              * Setting up of ecological soundstream with Hannah Kemp from [CriSap](https://crisap.org/), UAL and Grant smith from [SoundTent](https://soundtent.org/soundcamp_about.html)
              * Prototyping biofeedback based interactions with EMG sensors (MYOWARE)
              * Coordinated the final design and development of the [IMMSANE website](https://www.immsane.com/) for Yati Durant and Andre Bellmonte from the Zurich University of the arts
#        - title: 
#         company: 
#         company_url: ''
#         company_logo: 
#         location: 
#         date_start: ''
#         date_end: ''
#         description: |2-
#             Responsibilities include:

#             * 
#             * 
#             *
#             * 
#             * 
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Certificates'
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 'https://www.udemy.com/certificate/UC-15575581-ba43-4f77-bc99-72c27f976910/'
          date_end: ''
          date_start: '2023-11-19'
          description: ''
          icon: udemy
          organization: Udemy
          organization_url: 'https://www.udemy.com/'
          title: Generative Motion Graphics/vfx in UE-5
          url: 'https://www.udemy.com/course/ue5-procedural-vfx-motion-graphics/'
        - certificate_url: 'https://drive.google.com/file/d/1eQCS27J3YaqwDIYT6gkbxYt01D7tHVvK/view?usp=sharing'
          date_end: ''
          date_start: '2022-11-01'
          description: ''
          icon: 
          organization: EY
          organization_url: 'https://www.ey.com/en_in'
          title: National semifinalist, EY techathon's "Enter the metaverse" challenge
          url: 'https://www.ey.com/en_in/techathon-3/challenge-1-build-a-digital-twin'
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
      title: Talks
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
        Please reach out for any queries, concerns, projects, papers etc.
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
