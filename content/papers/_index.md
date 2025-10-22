---
title: 'Papers'
# date: 2024-05-19
type: landing
cms_exclude: true

- block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

sections:
  - block: collection
    id: papers
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - papers
        exclude_featured: false
    design:
      view: citation

# Optional header image (relative to `static/media/` folder).
# banner:
#   caption: ''
#   image: ''
---
