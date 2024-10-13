---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'PBIR-NIE: Glossy Object Capture under Non-Distant Lighting'
subtitle: ''
summary: ''
authors:
- admin
- Fujun Luan
- Miloš Hašan
- Kai Zhang
- Sai Bi
- Zexiang Xu
- Iliyan Georgiev
- Shuang Zhao
tags: 
- differentiable rendering
- inverse rendering
- 3D reconstruction
- glossy object reconstruction
- non-distant lighting reconstruction
categories: []
date: '2024-08-01'
lastmod: 2024-09-28T16:54:17-07:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2024-09-28T23:54:16.638971Z'
publication_types:
- '0'
abstract: Glossy objects present a significant challenge for 3D reconstruction from multi-view input images under natural lighting. In this paper, we introduce PBIR-NIE, an inverse rendering framework designed to holistically capture the geometry, material attributes, and surrounding illumination of such objects. We propose a novel parallax-aware non-distant environment map as a lightweight and efficient lighting representation, accurately modeling the near-field background of the scene, which is commonly encountered in real-world capture setups. This feature allows our framework to accommodate complex parallax effects beyond the capabilities of standard infinite-distance environment maps. Our method optimizes an underlying signed distance field (SDF) through physics-based differentiable rendering, seamlessly connecting surface gradients between a triangle mesh and the SDF via neural implicit evolution (NIE). To address the intricacies of highly glossy BRDFs in differentiable rendering, we integrate the antithetic sampling algorithm to mitigate variance in the Monte Carlo gradient estimator. Consequently, our framework exhibits robust capabilities in handling glossy object reconstruction, showcasing superior quality in geometry, relighting, and material estimation.
publication: '*arXiv*'
doi: 10.48550/arXiv.2408.06878
links:
- name: arXiv
  url: https://arxiv.org/abs/2408.06878
---
