---
# An instance of the Portfolio widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: pages

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 66

title: Notes
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: post
  count: 0
  offset: 0
  order: desc
  filters:
    tag: 'show'
    category: ''
    publication_type: ''
    exclude_featured: false
    exclude_past: false
    exclude_future: false
  links:
    - icon_pack: fas
      icon: fa-stick-note
      name: All notes
      url: 'https://wenda-qianhw.netlify.app/category/notes/'

design:
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)  
  view: 2
---

[More Notes]({{< relref "/category/notes/" >}})
