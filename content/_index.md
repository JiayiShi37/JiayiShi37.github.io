---
title: ''
summary: ''
date: 2024-01-01
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: jiayi-shi

      text: |-
        I am a Master's student in Statistics (Machine Learning track) at Columbia University.
        My interests lie at the intersection of statistical modeling, interactive data analysis,
        and large language models (LLMs), with applications in forecasting, decision support,
        and intelligent data systems.

      button:
        text: Download CV
        url: uploads/resume.pdf

      headings:
        about: About
        education: Education
        interests: Research Interests

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
      title: 'Research'
      subtitle: ''
      text: |-
        My research focuses on building and evaluating intelligent data analysis systems
        that combine statistical reasoning with large language models.

        I am particularly interested in:
        - Interactive and multi-turn data analysis with LLM agents
        - Evaluation frameworks for LLM-based analytical systems
        - Time-series forecasting and statistical learning
        - Data-driven decision support in real-world settings

        Please feel free to reach out for collaboration.
    design:
      columns: '1'

  - block: collection
    id: featured-publications
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: publications
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: projects
    content:
      title: Selected Projects
      text: ''
      filters:
        folders:
          - project
    design:
      view: article-grid
      columns: 2
---
