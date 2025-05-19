---
title: Teaching
summary: My teaching experience and philosophy
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  # - block: markdown
  #   content:
  #     title: Teaching Philosophy
  #     text: |-
  #       As an educator, I believe in fostering a collaborative learning environment where students are encouraged to think critically and develop problem-solving skills. My teaching approach emphasizes conceptual understanding over rote memorization, and I strive to make mathematics accessible and engaging for all students.
        
  #       I incorporate active learning strategies, real-world applications, and technology to enhance the learning experience. My goal is to help students build confidence in their mathematical abilities and develop a lifelong appreciation for the subject.
  #   design:
  #     columns: '1'
  
  - block: collection
    content:
      title: Teaching
      filters:
        folders:
          - teaching
        exclude_featured: false
      sort_by: 'Date'
      sort_order: 'desc'
      # Add pagination settings
      count: 20  # Increased to show more items
      offset: 0
      page_type: teaching
      # Remove the view_all section since we're already on the teaching page
    design:
      view: article-grid
      columns: 2
---
