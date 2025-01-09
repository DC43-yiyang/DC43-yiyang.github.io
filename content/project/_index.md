---
title: Research Projects
type: landing

sections:
  - block: portfolio
    id: projects
    content:
      title: Research Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below)
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Genomics
          tag: Genomics
        - name: Multi-omics Integration
          tag: Multi-omics Integration
        - name: Immunology
          tag: Immunology
        - name: Repetitive Region
          tag: Repetitive Region
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: masonry
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
      # Toggle between the various page layout types.
      #   1 = List
      #   2 = Compact
      #   3 = Card
      #   5 = Showcase
      spacing: {padding: [0, 0, 0, 0]}
---
