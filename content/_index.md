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
      text: |-
        - <2024-05-14 Tue> I passed my Ph.D. defense at CUHK.
      filters:
        folders:
          - newss
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
        - IEEE Symposium on Security and Privacy (S&P), 2023, 2024
        - The ACM Conference on Computer and Communications Security (CCS), 2021, 2022, 2023, 2024
        - The Web Conference (WWW), 2020, 2021, 2022, 2024
        - The ACM ASIA Conference on Computer and Communications Security (ASIACCS), 2021, 2022
      filters:
        folders:
          - services1
    design:
      columns: '2'
---
