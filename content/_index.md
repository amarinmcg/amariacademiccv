---
# Leave the homepage title empty to use the site title
title: Amari McGee
date: 2024-06-12
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
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My research primarily dwells in the intersection of LGBTQ+ rights, racial inequality, and child neglection.
        
        By employing a range of computational methods and techniques, I seek to shed light on pressing social issues of our time by applying data science to these areas, I aim to bring about a more nuanced, data-driven approach to social justice and human rights.
        
        Please reach out to collaborate 😃
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
---
