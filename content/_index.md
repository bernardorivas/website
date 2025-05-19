---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  # - block: markdown
  #   content:
  #     title: '📚 My Research'
  #     subtitle: ''
  #     text: |-
  #       My research focuses on the rigorous study of nonlinear dynamical systems, with applications to robotics, machine learning, systems biology and gene regulatory networks. I develop combinatorial and topological frameworks grounded in Conley Index Theory to analyze complex dynamical systems.

  #       I design algorithms to rigorously identify global dynamics in complex models, particularly focusing on:
  #       - Computational topology for dynamical systems
  #       - Combinatorial methods for gene regulatory networks
  #       - Rigorous numerics of invariant manifolds
        
  #       I'm interested in collaborations at the intersection of mathematics, computation, and biology. Feel free to reach out!
  #   design:
  #     columns: '1'
  # # Featured Publications section removed
  - block: collection
    id: papers
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: projects
    content:
      title: Recent Projects
      filters:
        folders:
          - project
      # Add a link to the projects page
      view_all:
        url: 'project/'
        text: 'See all projects'
    design:
      view: article-grid
      columns: 3
  - block: collection
    id: talks
    content:
      title: Recent Talks
      filters:
        folders:
          - talks
    design:
      view: article-grid
      columns: 1
  - block: collection
    id: teaching
    content:
      title: Recent Teaching
      filters:
        folders:
          - teaching
    design:
      view: article-grid
      columns: 2
---
