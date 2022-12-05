---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Analytic Spherical Harmonic Gradients for Real-Time Rendering with Many Polygonal
  Area Lights
subtitle: ''
summary: ''
authors:
- lifan-wu
- admin
- shuang-zhao
- ravi-ramamoorthi
tags:
- area lighting
- differentiable rendering
- analytic gradients
- spherical harmonics
categories: []
date: '2020-08-01'
lastmod: 2022-12-04T20:54:41-08:00
featured: false
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
publishDate: '2022-12-05T04:54:41.374302Z'
publication_types:
- '2'
abstract: Recent work has developed analytic formulae for spherical harmonic (SH)
  coefficients from uniform polygonal lights, enabling near-field area lights to be
  included in Precomputed Radiance Transfer (PRT) systems, and in offline rendering.
  However, the method is inefficient since coefficients need to be recomputed at each
  vertex or shading point, for each light, even though the SH coefficients vary smoothly
  in space. The complexity scales linearly with the number of lights, making many-light
  rendering difficult. In this paper, we develop a novel analytic formula for the
  spatial gradients of the spherical harmonic coefficients for uniform polygonal area
  lights. The result is a significant generalization, involving the Reynolds transport
  theorem to reduce the problem to a boundary integral for which we derive a new analytic
  formula, showing how to reduce a key term to an earlier recurrence for SH coefficients.
  The implementation requires only minor additions to existing code for SH coefficients.
  The results also hold implications for recent efforts on differentiable rendering.
  We show that SH gradients enable very sparse spatial sampling, followed by accurate
  Hermite interpolation. This enables scaling PRT to hundreds of area lights with
  minimal overhead and real-time frame rates. Moreover, the SH gradient formula is
  a new mathematical result that potentially enables many other graphics applications.
publication: '*ACM Trans. Graph.*'
doi: 10.1145/3386569.3392373
links:
- name: Paper
  url: https://shuangz.com/projects/diffsh-sg20/diffsh-sg20.pdf
- name: Video
  url: https://vimeo.com/429735943
- name: Code
  url: https://shuangz.com/projects/diffsh-sg20/diffsh-sg20-code.zip
- name: URL
  url: https://doi.org/10.1145/3386569.3392373
---
