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
      text: |-
        **External Reviewer**
        - IEEE Symposium on Security and Privacy (S&P):
          - 2023
          - 2024
        - The Annual Computer Security Applications Conference (ACSAC):
          - 2023
      filters:
        folders:
          - services
    design:
      columns: '2'
---
