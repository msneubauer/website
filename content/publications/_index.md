---
title: Publications
cms_exclude: true
date: 2023-10-24
type: landing

sections:
  - block: collection
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
      count: 0 # Set count to 0 to display all items
    design:
      view: article-grid
      columns: 4
      spacing:
        # Top, Right, Bottom, Left
        padding: ['40px', '0', '0', '0']
  
  - block: collection
    content:
      title: Selected Publications
      text: ''
      count: 0 # Set count to 0 to display all items
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
      spacing:
        padding: [0, 0, 0, 0]

  - block: cta-button-list
    content:
      buttons:
        - text: See all publications
          url: /uploads/mypubs.pdf
    design:
      columns: "1"
      padding: none
      align: center
      background:
        color: "blue-50"

# View.
#view: citation

# Optional header image (relative to `static/media/` folder).
banner:
  caption: ''
  image: ''
---