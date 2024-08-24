---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-08-08
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
          filename: 'stacked-peaks.svg'
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  
  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: citation
      columns: 1

  - block: collection
    id: projects
    content:
      title: Selected Projects
      text: Here are a selection of projects that I have worked on over the years.
      filters:
        folders:
          - project
      design:
        view: article-grid
        fill_image: false
        columns: 3
  
---
