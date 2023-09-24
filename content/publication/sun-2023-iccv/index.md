---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Neural-PBIR Reconstruction of Shape, Material, and Illumination
subtitle: ''
summary: ''
authors:
- Cheng Sun
- admin
- Zhengqin Li
- Kai Yan
- Cheng Zhang
- Carl Marshall
- jiabin-huang
- Shuang Zhao
- Zhao Dong
author_notes:
- "Equal contribution"
- "Equal contribution"
tags: 
- differentiable rendering
- inverse rendering
- 3D reconstruction
- neural surface reconstruction
categories: []
date: '2023-10-01'
lastmod: 2023-09-16T04:39:00-07:00
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
publishDate: '2023-09-16T11:39:00.470595Z'
publication_types:
- '1'
abstract: Reconstructing the shape and spatially varying surface appearances of a physical-world object as well as its surrounding illumination based on 2D images (e.g., photographs) of the object has been a long-standing problem in computer vision and graphics. In this paper, we introduce a robust object reconstruction pipeline combining neural based object reconstruction and physics-based inverse rendering (PBIR). Specifically, our pipeline firstly leverages a neural stage to produce high-quality but potentially imperfect predictions of object shape, reflectance, and illumination. Then, in the later stage, initialized by the neural predictions, we perform PBIR to refine the initial results and obtain the final high-quality reconstruction. Experimental results demonstrate our pipeline significantly outperforms existing reconstruction methods quality-wise and performance-wise.

publication: '*Proceedings of the IEEE/CVF International Conference on Computer Vision
  (ICCV)*'
links:
- name: Project
  url: https://neural-pbir.github.io/
- name: Paper
  url: https://arxiv.org/abs/2304.13445
---
