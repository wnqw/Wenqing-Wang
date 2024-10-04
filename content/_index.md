---
# Leave the homepage title empty to use the site title
title: Wenqing Wang
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    
  # - block: collection
  #   content:
  #     title: Publications
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation

  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #   design:
  #     columns: '1'
  #     view: compact

  - block: experience
    content:
      title: News
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Ph.D. Student
          company: Northeastern University
          location: Boston
          date_start: '2022-09-01'
        # - title: Wenqing Wang, Fu Yun, Audio-Driven Emotional 3D Talking-Head Generation
        #   date_start: '2024-09'
    design:
      columns: '2'

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      email: wang.wenqin@northeastern.edu
      address:
        street: 360 Huntington Ave
        city: Boston
        region: MA
        postcode: '02115'
        country: United States
        country_code: US

      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
