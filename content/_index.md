---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: QuantCorner Research Laboratory
      subtitle: by Thai and Quantitative Analyst and Financial Engineer Association
      text: |
        Welcome to the **QuantCorner Research Lab**! We are dedicated to advancing research in **Quantitative Finance** and **Quantitative Risk Management**. Our team focuses on cutting-edge methodologies, including statistical modeling, machine learning, and data-driven approaches, to address complex financial and risk-related challenges.
    design:
      columns: '1'
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: showcase
      columns: '3'
  
  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: compact
      columns: '1'

---
