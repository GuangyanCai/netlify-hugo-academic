---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Image-space Adaptive Sampling for Fast Inverse Rendering
subtitle: ''
summary: ''
authors:
- Kai Yan
- Cheng Zhang
- sébastien-speierer
- Guangyan Cai
- yufeng-zhu
- Zhao Dong
- Shuang Zhao
tags: []
categories: []
date: '2025-07-01'
lastmod: 2025-07-30T23:34:02-04:00
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
publishDate: '2025-07-31T03:34:02.338701Z'
publication_types:
- '1'
abstract: Inverse rendering is crucial for many scientific and engineering disciplines.
  Recent progress in differentiable rendering has led to efficient differentiation
  of the full image formation process with respect to scene parameters, enabling gradient-based
  optimization.However, computational demands pose a significant challenge for differentiable
  rendering, particularly when rendering all pixels during inverse rendering from
  high-resolution/multi-view images. This computational cost leads to slow performance
  in each iteration of inverse rendering. Meanwhile, naively reducing the sampling
  budget by uniformly sampling pixels to render in each iteration can result in high
  gradient variance during inverse rendering, ultimately degrading overall performance.Our
  goal is to accelerate inverse rendering by reducing the sampling budget without
  sacrificing overall performance. In this paper, we introduce a novel image-space
  adaptive sampling framework to accelerate inverse rendering by dynamically adjusting
  pixel sampling probabilities based on gradient variance and contribution to the
  loss function. Our approach efficiently handles high-resolution images and complex
  scenes, with faster convergence and improved performance compared to uniform sampling,
  making it a robust solution for efficient inverse rendering.
publication: '*Proceedings of the Special Interest Group on Computer Graphics and
  Interactive Techniques Conference Conference Papers*'
doi: 10.1145/3721238.3730627
links:
- name: URL
  url: https://dl.acm.org/doi/10.1145/3721238.3730627
---
