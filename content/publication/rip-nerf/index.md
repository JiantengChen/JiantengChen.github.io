---
title: 'Rip-NeRF: Anti-aliasing Radiance Fields with Ripmap-Encoded Platonic Solids'

authors:
  - Junchen Liu
  - Wenbo Hu
  - Zhuo Yang
  - admin
  - Guoliang Wang
  - Xiaoxue Chen
  - Yantong Cai
  - Huan-ang Gao
  - Hao Zhao

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

# date: '20-07-01T00:00:00Z'
# doi: '10.1007/978-981-99-8850-1_1'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['conference']

# Publication name and optional abbreviated publication name.
publication: ACM Transactions on Graphics SIGGRAPH 2024
publication_short: In *SIGGRAPH 2024* 

abstract: Despite significant advancements in Neural Radiance Fields (NeRFs), the renderings may still suffer from aliasing and blurring artifacts, since it remains a fundamental challenge to effectively and efficiently characterize anisotropic areas induced by the cone-casting procedure. This paper introduces a Ripmap-Encoded Platonic Solid representation to precisely and efficiently featurize 3D anisotropic areas, achieving high-fidelity anti-aliasing renderings. Central to our approach are two key components":" Platonic Solid Projection and Ripmap encoding. The Platonic Solid Projection factorizes the 3D space onto the unparalleled faces of a certain Platonic solid, such that the anisotropic 3D areas can be projected onto planes with distinguishable characterization. Meanwhile, each face of the Platonic solid is encoded by the Ripmap encoding, which is constructed by anisotropically pre-filtering a learnable feature grid, to enable featurzing the projected anisotropic areas both precisely and efficiently by the anisotropic area-sampling. Extensive experiments on both well-established synthetic datasets and a newly captured real-world dataset demonstrate that our Rip-NeRF attains state-of-the-art rendering quality, particularly excelling in the fine details of repetitive structures and textures, while maintaining relatively swift training times.

# Summary. An optional shortened abstract.
summary: A Ripmap-Encoded Platonic Solid representation to precisely and efficiently featurize 3D anisotropic areas, achieving high-fidelity anti-aliasing renderings and excelling in the fine details of repetitive structures and textures.

tags:
- Anti-Aliasing

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2405.02386'
url_code: 'https://github.com/JunchenLiu77/Rip-NeRF'
url_dataset: 'https://drive.google.com/file/d/1lmLJ7VN-Fbyohgdcrl7WMDj3gPk3WgUg/edit'
url_poster: ''
url_project: 'https://junchenliu77.github.io/Rip-NeRF/'
# url_slides: ''
# url_source: ''
url_video: 'https://www.youtube.com/watch?v=VeZTbQwMFRs'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Rip-NeRF**](https://junchenliu77.github.io/Rip-NeRF/)'
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
