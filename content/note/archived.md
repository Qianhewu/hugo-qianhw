---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 66

title: Notes
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: archived_note
  count: 0
  offset: 0
  order: desc
  
  filter_button:
  - name: All
    tag: '*'
  - name: Typed
    tag: 'typed'
  - name: 'Handwritten'
    tag: 'handwritten'

links:
  - icon_pack: fab
    icon: twitter
    name: Follow
    url: 'https://twitter.com/Twitter'

design:
  background:
    gradient_start: '#000000'
    gradient_end: '#0000CC'
    text_color_light: true
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)  
  view: 2
---
