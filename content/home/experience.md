---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Work Experience
subtitle: Research-related

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Research Intern
    company: Meta Reality Labs
    company_url: https://tech.fb.com/ar-vr/
    company_logo: meta
    location: Redmond, WA
    date_start: '2022-06-21'
    date_end: '2022-09-09'
    description: |2-
        * Investigated the baking artifacts in material reconstruction with inverse rendering and proposed a method to mitigate them.
        * Participated in building a hybrid pipeline that combines NeRF and physics-based differentiable rendering to do high quality 3D reconstruction. 
        * Showcased our reconstruction results at [Meta Connect 2022](https://www.facebook.com/RealityLabs/videos/3281891035412216/) (starting at 1:13:20).
        * Published our work at ICCV 2023 [(link)](/publication/sun-2023-iccv).

  - title: Research Intern
    company: Adobe Research
    company_url: https://research.adobe.com/
    company_logo: adobe
    location: San Jose, CA
    date_start: '2023-06-26'
    date_end: '2023-09-08'
    description: |2-
        * Developed a novel, cost-effective lighting representation called Envmap++ for accurate reconstruction of glossy objects in indoor environments.
        * Conducted research on improving the fidelity of glossy object reconstruction under complex indoor illumination conditions.
        * Sumitted to arXiv [(link)](publication/cai-pbirnie-glossy-object-2024/)

design:
  columns: '2'
---
