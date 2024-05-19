---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: News
    content:
      title: News
      filters:
        folders:
          - news
    design:
      columns: '2'
      view: compact
  - block: collection
    id: Publications
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      columns: '2'
      view: citation
  - block: collection
    id: Services
    content:
      title: Services
      text: "123"
    design:
      columns: '2'
---
