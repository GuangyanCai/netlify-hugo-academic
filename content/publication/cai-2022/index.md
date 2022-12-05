---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Physics-Based Inverse Rendering using Combined Implicit and Explicit Geometries
subtitle: ''
summary: ''
authors:
- admin
- kai-yan
- zhao-dong
- ioannis-gkioulekas
- shuang-zhao
tags: 
- differentiable rendering
- inverse rendering
- 3D reconstruction
categories: []
date: '2022-01-01'
lastmod: 2022-12-04T20:54:40-08:00
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: 'Smart'
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2022-12-05T04:54:40.156583Z'
publication_types:
- '2'
abstract: Mathematically representing the shape of an object is a key ingredient for
  solving inverse rendering problems. Explicit representations like meshes are efficient
  to render in a differentiable fashion but have difficulties handling topology changes.
  Implicit representations like signed-distance functions, on the other hand, offer
  better support of topology changes but are much more difficult to use for physics-based
  differentiable rendering. We introduce a new physics-based inverse rendering pipeline
  that uses both implicit and explicit representations. Our technique enjoys the benefit
  of both representations by supporting both topology changes and differentiable rendering
  of complex effects such as environmental illumination, soft shadows, and interreflection.
  We demonstrate the effectiveness of our technique using several synthetic and real
  examples.
publication: '*Computer Graphics Forum*'
doi: https://doi.org/10.1111/cgf.14592
links:
- name: Paper
  url: https://shuangz.com/projects2/psdr-meshsdf-egsr22/psdr-meshsdf-egsr22.pdf
- name: Supplement
  url: https://shuangz.com/projects2/psdr-meshsdf-egsr22/psdr-meshsdf-egsr22_supp.pdf
- name: Code
  url: https://shuangz.com/projects2/psdr-meshsdf-egsr22/code_data.zip
- name: URL
  url: https://onlinelibrary.wiley.com/doi/abs/10.1111/cgf.14592
---
