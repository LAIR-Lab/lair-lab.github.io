---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
#################################
  - block: markdown
    content:
      title: 
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: LAIRLabLogo.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: contain #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          text_color_light: true
      spacing:
        padding: ['300px', '0', '0px', '0']
      # css_class: fit
#################################
  - block: markdown
    content:
      # title: Living with Assistive and Interactive Robots (LAIR) Lab
      text: |-
        The **Living with Assistive and Interactive Robots (LAIR) Lab** is located at [Concordia University](https://www.concordia.ca/) in Montreal, Canada and is led by [Prof. Christopher Yee Wong](./author/chris-yee-wong/). The lab focuses research in physical-social human-robot interaction (psHRI).
        
        For prospective students, please see the [Contact](./contact/) section.

        (Note: This site is a work in progress).
    design:
      spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
        padding: ["20px", "0", "50px", "0"]
#################################
  # - block: hero
  #   content:
  #     title: 
  #     image:
  #       filename: LAIRLabLogo.png
  #     text: |-
  #       # <br>
  #       The **Living with Assistive and Interactive Robots (LAIR) Lab** is located at [Concordia University](https://www.concordia.ca/) in Montreal, Canada and is led by [Prof. Christopher Yee Wong](https://lair-lab.github.io/author/chris-yee-wong/). The lab focuses research in physical-social human-robot interaction (psHRI).
        
  #       For prospective students, please see the [Contact](./contact/) section.

  #       (Note: This site is a work in progress).
#################################
  - block: slider
    content:
      slides:

      - title: '' # Welcome to the LAIR Lab!
        content: Members of the LAIR Lab
        align: center
        background:
          image:
            filename: 'LAIR Lab Group Photo.jpg'
            filters:
              brightness: 0.7
          position: center
          color: '#666'
        link:
          icon: user
          icon_pack: fas
          text: Check out the team!
          url: ../people/

      - title: 
        content: 'Physical-Social Human-Robot Interaction Research'
        align: center
        background:
          image:
            filename: projectsshowcase.png
            filters:
              brightness: 0.7
          position: center
          color: '#555'
        link:
          icon: robot
          icon_pack: fas
          text: Check out our research!
          url: ../projects/

      # - title: World-Class Semiconductor Lab
      #   content: 'Just opened last month!'
      #   align: center
      #   background:
      #     image:
      #       filename: welcome.jpg
      #       filters:
      #         brightness: 0.5
      #     position: center
      #     color: '#333'
      #   link:
      #     icon: graduation-cap
      #     icon_pack: fas
      #     text: Join Us
      #     url: ../contact/

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '500px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 4000
#################################
#   - block: collection
#     content:
#       title: Latest News
#       subtitle: from the LAIR Lab
#       text:
#       count: 5
#       filters:
#         author: ''
#         category: ''
#         exclude_featured: false
#         publication_type: ''
#         tag: ''
#       offset: 0
#       order: desc
#       page_type: post
#     design:
#       view: card
#       columns: '2'
# #################################
#   - block: collection
#     content:
#       title: Latest Publications
#       text: ""
#       count: 5
#       filters:
#         folders:
#           - publication
#         publication_type: 'article'
#     design:
#       view: citation
#       columns: '1'
#################################
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen
#################################
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '1'
---
