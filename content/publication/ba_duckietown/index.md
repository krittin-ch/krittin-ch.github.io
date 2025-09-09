---
title: "Real-Time Object Detection for Autonomous Driving: An Empirical Study in a Small-Scale Urban Environment"
authors:
- admin
- Michael Meidinger
- Andreas Herkersdorf
author_notes:
  - 'Author (Bachelor Student)'
  - 'Advisor'
  - 'Supervisor'

date: "2025-09-10T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-08-10T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["bachelor's thesis"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: >
  The Duckietown platform is designed to study and research autonomous driving systems
  in a small-scale urban environment. Our lab's previous work has designed a visual-based
  algorithm, relying on patterns based on Duckies' hue, saturation, and lightness to tackle
  time-of-flight sensor-based inefficiency, detecting an obstacle without recognizing an object.
  However, the visual-based algorithm is limited to only Duckie detection, meaning that the
  algorithm does not apply to other objects such as Duckiebot and stop signs. Hence, this thesis
  focuses on a real-time object detection system and its GPU utilization, and therefore highlights
  two important improvements at the same time:
  1. enabling more targets for object detection for the Duckietown platform, and
  2. avoiding CPU utilization by migrating an object detection model to GPU.
  
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Object Detection
- Real-Time System
- Robotics

featured: true

# hugoblox:
#   ids:
#     arxiv: 1512.04133v1

links:
- type: pdf
  url: uploads/BA-Krittin.pdf
- type: slides
  url: https://github.com/krittin-ch/NV3D
# - type: preprint
#   provider: arxiv
#   id: 1512.04133v1
# - type: slides
#   url: https://www.slideshare.net/

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

# disable social network
share: false

---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
