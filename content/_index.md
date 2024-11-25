---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: collection
    id: journal-articles
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      columns: '2'

  - block: collection
    id: awards-and-grants
    content:
      title: Awards & Grants
      filters:
        folders:
          - news
        tag: 'Awards & Grants'
    design:
      columns: '2'
      view: community/news_list

  - block: experience
    id: experience
    design:
      columns: '2'
    content:
      title: Experiences
      items:
          - title: Visiting Intern
            company: The Hong Kong University of Science and Technology
            company_url: 'https://join.hkust.edu.hk/admissions/visiting'
            company_logo: 
            location: Hong Kong SAR, China
            date_start: '2023-01-15'
            date_end: '2023-08-31'
            description: 
          - title: Research Intern
            company: Research Center for Social Computing and Information Retrieval (SCIR)
            company_url: 'http://ir.hit.edu.cn/'
            company_logo: 
            location: Harbin, China
            date_start: '2020-09-01'
            date_end: '2022-08-31'
            description: 

  - block: markdown
    design:
      columns: '2'
      
    content:
      title: 🌏 Visitors
      subtitle: Powerd by [clustrmaps.com](https://clustrmaps.com/)
      text: |-
        <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=SEDymVEFJHTaCJ9iGcuU4QJ4WF7CE1nY1E2_w9UVgm4&cl=ffffff&w=a"></script>
---
