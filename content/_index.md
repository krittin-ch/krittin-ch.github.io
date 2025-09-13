---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
#   # Default section spacing
  spacing: "5rem"


sections:
  - block: resume-biography-3
    id: bio
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/Krittin-Chaowakarn-CV.pdf
    design:
      css_class: dark
      # Avatar customization
      avatar:
        size: large  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: true
  - block: collection
    id: research
    content:
      title: Projects
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: new-citation
  - block: resume-experience
    id: experience
    content:
      username: admin
      experience_types: [work, education, academic]
    design:
      # Hugo date format
      date_format: 'Jan 2006'
      # Education or Experience section first?
      is_education_first: true
  - block: markdown
    content:
      title: Academic/Teaching Experience
      text: |-
        During my undergraduate studies at SIIT, I was assigned as a teaching assistant in five courses with grading responsibilities and in one laboratory course.
        {{< spoiler text="TA Experience" >}}
        **Jan 2025 - May 2025**: Electromagnetics   
        
        **Aug 2024 - Dec 2024**: Linear Algebra and Optimization Method, Digital Circuits Laboratory  
        
        **Jan 2024 - May 2024**: Electromagnetics  
        
        **Aug 2023 - Dec 2023**: Computational Tools in Electrical Engineering  
        
        **Jan 2023 - May 2023**: Basic Electrical Engineering  
        {{< /spoiler >}}
    design:
      view: article
      columns: 1
      style: wide      
---
