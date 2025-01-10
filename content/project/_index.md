---
title: Research Projects
subtitle: ''
type: landing

sections:
  - block: markdown
    content:
      title: Research Projects
      subtitle: ''
    design:
      spacing: {padding: [0, 0, 0, 0]}
      
  - block: portfolio
    id: projects
    content:
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below)
      default_button_index: 0
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
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
      # Toggle between the various page layout types.
      #   1 = List
      #   2 = Compact
      #   3 = Card
      #   5 = Showcase
      spacing: {padding: [0, 0, 0, 0]}
---

See our current research projects below, which can be filtered by the tags. Explore a [list of all projects >>](./project/)
