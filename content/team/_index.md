---
title: Team
summary: FIWIT Team
type: landing

cascade:
  - target:
      path: '{/team/*/**}'
    type: docs
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: team
    content:
      title: Team
      filters:
        tag: Team
        kinds:
          - section
    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 1
---
