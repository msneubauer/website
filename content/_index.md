---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Curriculum Vitae
        url: uploads/CV.pdf
        # target _self for no new tab, _blank for new tab
        target: _blank
      headings:
        about: 'About Me'
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: sm # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded  

########### Research
  - block: collection
    content:
      title: Research Areas
      filters:
        folders:
          - research
        kinds:
          - section
    design:
      view: article-grid
      columns: 3
      fill_image: true
      show_date: false
      show_read_time: false
      show_read_more: false
      flip_back: false
      spacing:
        padding: ['40px', '0', '0', '0']
  - block: cta-button-list
    content:
      buttons:
        - text: Read all about the Neubauer Lab
          url: /research/
    design:
      columns: "1"
      padding: none
      align: center
      background:
        color: "blue-50"

########### Publications
  - block: collection
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
      count: 0
    design:
      view: article-grid
      columns: 4
      spacing:
        padding: ['0', '0', '0', '0']
  - block: cta-button-list
    content:
      buttons:
        - text: See all publications
          url: /publications/
    design:
      columns: "1"
      padding: none
      align: center
      background:
        color: "blue-50"

########### News
  - block: collection
    content:
      title: Featured News
      filters:
        folders:
          - news
        kinds:
          - section
        featured_only: true
      count: 0
    design:
      view: article-grid
      columns: 4
      fill_image: true
      show_date: true
      show_read_time: false
      show_read_more: false
      flip_back: false
      spacing:
        padding: ['0', '0', '0', '0']
  - block: cta-button-list
    content:
      buttons:
        - text: See all news
          url: /news/
    design:
      columns: "1"
      padding: none
      align: center
      background:
        color: "blue-50"

########### Blogs
#  - block: collection
#    content:
#      title: Featured Blogs
#      subtitle: ''
#      text: ''
#      page_type: blog
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 10
#      filters:
#        author: ''
#        category: ''
#        tag: ''
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ''
#        featured_only: true
#      offset: 0
#      order: desc
#    design:
#      view: article-grid
#      columns: 4
#      spacing:
#        padding: [0, 0, 0, 0]
#  - block: cta-button-list
#    content:
#      buttons:
#        - text: See all blogs
#          url: /blog/
#    design:
#      columns: "1"
#      padding: none
#      align: center
#      background:
#        color: "blue-50"
---
