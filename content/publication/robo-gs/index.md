---
title: 'Robo-GS: A Physics Consistent Spatial-Temporal Model for Robotic Arm with Hybrid Representation'

authors:
  - Haozhe Lou
  - Yurong Liu
  - Yike Pan
  - Yiran Geng
  - admin
  - Wenlong Ma
  - Chenglong Li
  - Lin Wang
  - Hengzhen Feng
  - Lu Shi
  - Liyi Luo
  - Yongliang Shi

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

# date: '20-07-01T00:00:00Z'
# doi: '10.1007/978-981-99-8850-1_1'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-08-27T08:44:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: arXiv Preprint 

abstract: Real2Sim2Real plays a critical role in robotic arm control and reinforcement learning, yet bridging this gap remains a significant challenge due to the complex physical properties of robots and the objects they manipulate. Existing methods lack a comprehensive solution to accurately reconstruct real-world objects with spatial representations and their associated physics attributes. We propose a Real2Sim pipeline with a hybrid representation model that integrates mesh geometry, 3D Gaussian kernels, and physics attributes to enhance the digital asset representation of robotic arms. This hybrid representation is implemented through a Gaussian-Mesh-Pixel binding technique, which establishes an isomorphic mapping between mesh vertices and Gaussian models. This enables a fully differentiable rendering pipeline that can be optimized through numerical solvers, achieves high-fidelity rendering via Gaussian Splatting, and facilitates physically plausible simulation of the robotic arm's interaction with its environment using mesh-based methods. The code,full presentation and datasets will be made publicly available at our website. 

# Summary. An optional shortened abstract.
summary: A Real2Sim pipeline with a hybrid representation model that integrates mesh geometry, 3D Gaussian kernels, and physics attributes to enhance the digital asset representation of robotic arms is proposed.

tags:
- Real2Sim2Real

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Project Page
  url: https://robostudioapp.com/

url_pdf: 'https://www.arxiv.org/abs/2408.14873'
url_code: 'https://robostudioapp.com/'
url_dataset: ''
url_poster: ''
url_project: 'https://robostudioapp.com/'
# url_slides: ''
# url_source: ''
url_video: 'https://www.youtube.com/watch?v=Aq2-2EW6JBk'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Robo-GS**](https://robostudioapp.com/)'
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
