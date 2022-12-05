---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Differentiable Time-Gated Rendering
subtitle: ''
summary: ''
authors:
- lifan-wu
- admin
- ravi-ramamoorthi
- shuang-zhao
author_notes:
- "Equal contribution"
- "Equal contribution"
tags: 
- differentiable rendering
- inverse rendering
- time-gated rendering
categories: []
date: '2021-12-01'
lastmod: 2022-12-04T20:54:41-08:00
featured: true
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
publishDate: '2022-12-05T04:54:40.778695Z'
publication_types:
- '2'
abstract: The continued advancements of time-of-flight imaging devices have enabled
  new imaging pipelines with numerous applications. Consequently, several forward
  rendering techniques capable of accurately and efficiently simulating these devices
  have been introduced. However, general-purpose differentiable rendering techniques
  that estimate derivatives of time-of-flight images are still lacking. In this paper,
  we introduce a new theory of differentiable time-gated rendering that enjoys the
  generality of differentiating with respect to arbitrary scene parameters. Our theory
  also allows the design of advanced Monte Carlo estimators capable of handling cameras
  with near-delta or discontinuous time gates.We validate our theory by comparing
  derivatives generated with our technique and finite differences. Further, we demonstrate
  the usefulness of our technique using a few proof-of-concept inverse-rendering examples
  that simulate several time-of-flight imaging scenarios.
publication: '*ACM Trans. Graph.*'
doi: 10.1145/3478513.3480489
links:
- name: Paper
  url: https://shuangz.com/projects/dtgr-sa21/dtgr-sa21.pdf
- name: Talk Slides
  url: https://shuangz.com/projects/dtgr-sa21/dtgr-sa21.pptx
- name: Supplement
  url: https://shuangz.com/projects/dtgr-sa21/dtgr-sa21_supp.zip
- name: Code
  url: https://shuangz.com/projects/dtgr-sa21/dtgr-sa21_code.zip
- name: URL
  url: https://doi.org/10.1145/3478513.3480489
---
