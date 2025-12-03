---
title: 'Research Projects'
date: 2025-05-19
type: landing

design:
  # Section spacing
  spacing: '2rem'

# Page sections
sections:
  # - block: collection
  #   content:
  #     title: Research Projects
  #     text: #Here are a selection of research projects that I have worked on over the years.
  #     filters:
  #       folders:
  #         - project
  #     count: 50

  #     # buttons:
  #     #   - name: All
  #     #     tag: '*'
  #     #   - name: Active Projects
  #     #     tag: 'active'
  #     #   - name: Past Projects
  #     #     tag: old
  #   design:
  #     view: article-grid
  #     fill_image: false
  #     columns: 4
      
  - block: portfolio
    content:
      title: Research Projects
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
        - name: Active Projects
          tag: 'active'
        - name: Past Projects
          tag: old
---
