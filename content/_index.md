---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title:
        CUHK Syntax Lab
      # image:
      #  filename: group_pic.jpg
      text:
        We are syntacticians in CUHK led by Prof Victor Pan, in the Department of Linguistics and Modern Languages. Our interests cover formal syntax (especially under Minimalist Program), understudied languages, and interdisciplinary research for exploring the linguistic essence in human's mind.
    design:
      css_style: 'font-size:20px'
        
  - block: collection
    content:
      title: Latest Activities
      subtitle:
      text:
      count: 5
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
      view: card
      columns: '1'
  
 # - block: markdown
 #   content:
 #     title:
 #     subtitle: ''
 #     text:
 #   design:
 #     columns: '1'
 #     background:
 #       image: 
 #         filename: coders.jpg
 #         filters:
 #           brightness: 1
 #         parallax: false
 #         position: center
 #         size: cover
 #         text_color_light: true
 #     spacing:
 #       padding: ['20px', '0', '20px', '0']
 #     css_class: fullscreen

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: compact
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
