---
title: '3D Gaussian Inverse Rendering with Approximated Global Illumination'

authors:
  - Zirui Wu
  - admin
  - Laijian Li
  - Shaoteng Wu
  - Zhikai Zhu
  - Kang Xu
  - Martin R. Oswald
  - Jie Song

# Author notes (optional)
author_notes:
  # - 'Equal contribution'
  # - 'Equal contribution'
  # - 'Equal contribution'

# date: '20-07-01T00:00:00Z'
# doi: '10.1007/978-981-99-8850-1_1'
doi: '10.48550/arXiv.2504.01358'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-02T05:02:25Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: Arxiv Preprint
publication_short: Arxiv Preprint

abstract: 3D Gaussian Splatting shows great potential in reconstructing photo-realistic 3D scenes. However, these methods typically bake illumination into their representations, limiting their use for physically-based rendering and scene editing. Although recent inverse rendering approaches aim to decompose scenes into material and lighting components, they often rely on simplifying assumptions that fail when editing. We present a novel approach that enables efficient global illumination for 3D Gaussians Splatting through screen-space ray tracing. Our key insight is that a substantial amount of indirect light can be traced back to surfaces visible within the current view frustum. Leveraging this observation, we augment the direct shading computed by 3D Gaussians with Monte-Carlo screen-space ray-tracing to capture one-bounce indirect illumination. In this way, our method enables realistic global illumination without sacrificing the computational efficiency and editability benefits of 3D Gaussians. Through experiments, we show that the screen-space approximation we utilize allows for indirect illumination and supports real-time rendering and editing. Code, data, and models will be made available at our project page.

# Summary. An optional shortened abstract.
summary: debug

tags:
- Inverse Rendering

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Project Page
  url: https://wuzirui.github.io/gs-ssr/



url_pdf: 'https://arxiv.org/abs/2504.01358'
url_code: 'https://github.com/wuzirui/gs-ssr'
url_dataset: ''
url_poster: ''
url_project: 'https://wuzirui.github.io/gs-ssr/'
# url_slides: ''
# url_source: ''
url_video: 'https://youtu.be/i0SmXJH1uwI?si=2Joi0OdjFyYE15oG'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**GS-SSR**](https://wuzirui.github.io/gs-ssr/)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: “
---
