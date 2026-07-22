---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Physics-Based Inverse Rendering
subtitle: ''
summary: ''
authors:
- admin
tags: []
categories: []
date: '2025-06-01'
lastmod: 2026-07-22T00:00:00-04:00
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
publishDate: '2026-07-22T00:00:00.000000Z'
publication_types:
- '7'
abstract: 'This dissertation explores the challenges and solutions in physically-based
  inverse rendering, aiming to reconstruct detailed 3D scenes—including geometry,
  material properties, and lighting—from ordinary 2D images. The research journey
  began with the goal of making differentiable rendering more broadly applicable,
  particularly in scenarios where existing methods struggled with complex shapes,
  difficult initializations, or intricate material and lighting effects. The first
  step involved bringing differentiability to time-gated rendering, which is essential
  for advanced tasks such as Non-Line-of-Sight (NLOS) reconstruction that rely on
  the timing of light as it moves through a scene. To address the need for more flexible
  and robust geometric representations, a new inverse rendering pipeline was developed
  that combines the strengths of both implicit and explicit geometric representations.
  To accelerate initialization, neural rendering techniques (such as NeRF and NeuS)
  were incorporated to provide strong initial estimates for geometry, materials,
  and lighting, which are then refined using a physics-based differentiable renderer
  capable of handling complex global illumination. Finally, EnvMAP++ was introduced
  as a lightweight, parallax-aware lighting model, and Neural Implicit Evolution
  (NIE) was integrated for robust, topology-adaptive shape optimization, faithfully
  capturing the complex interplay between shape, glossy materials, and detailed local
  lighting. Collectively, these projects form a cohesive set of tools and methods
  that make physically-based inverse rendering more accurate, flexible, and reliable,
  helping to advance the field of computational scene understanding from images.'
publication: '*Ph.D. Dissertation, University of California, Irvine*'
links:
- name: eScholarship
  url: https://escholarship.org/uc/item/4j20k5cm
url_pdf: https://escholarship.org/content/qt4j20k5cm/qt4j20k5cm.pdf
---
