---
title: 'News'
date: 2025-12-31
type: landing

design:
  spacing: '5rem'
  show_title: false

build:
  list: false   # this is needed to not show extraneous teaching block in collection

sections:
  - block: collection
    content:
      title: News
      filters:
        folders:
          - news
        kinds:
          - section
      count: 0
    design:
      view: article-grid
      columns: 4
      fill_image: true
      show_date: true
      show_read_time: false
      show_read_more: false
      flip_back: false
---