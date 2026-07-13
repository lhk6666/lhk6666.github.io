---
# 中文首页（留空 title 则使用站点名称）
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: 下载简历
        url: uploads/resume.pdf
      headings:
        about: '关于我'
        education: '教育经历'
        interests: '研究兴趣'
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: '📚 研究方向'
      subtitle: ''
      text: |-
        我的研究方向是面向机器人的**视觉-语言-动作（VLA）模型**——
        让空中与地面机器人能够理解自然语言指令，并在真实世界中自主行动。
        我也关注视觉语言导航（VLN）和基于学习的机器人控制。

        欢迎有兴趣合作的朋友与我联系 😃
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: 代表性论文
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: 近期论文
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: 学术报告
      filters:
        folders:
          - events
    design:
      view: card
  - block: collection
    id: news
    content:
      title: 最新动态
      subtitle: ''
      text: ''
      page_type: blog
      count: 10
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      offset: 0
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]
---
