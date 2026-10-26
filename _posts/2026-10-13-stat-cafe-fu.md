---
title: "Stat Cafe - Ziang Fu"
excerpt: "Control-Geometry Straightening for Latent Planning"
layout: single
classes: wide
category: 
  - Stat Cafe
layouts_gallery:
  - url: /assets/images/stat_cafe/Fu_Oct_20_2026/IMG_0639.jpg
    image_path: /assets/images/stat_cafe/Fu_Oct_20_2026/IMG_0639.jpg
    alt: "IMG_0639.jpg"
  - url: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image.jpeg
    image_path: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image.jpeg
    alt: "20261020_Image.jpeg"
  - url: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-1.jpeg
    image_path: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-1.jpeg
    alt: "20261020_Image-1.jpeg"
  - url: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-2.jpeg
    image_path: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-2.jpeg
    alt: "20261020_Image-2.jpeg"
  - url: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-3.jpeg
    image_path: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-3.jpeg
    alt: "20261020_Image-3.jpeg"
  - url: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-4.jpeg
    image_path: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-4.jpeg
    alt: "20261020_Image-4.jpeg"
  - url: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-5.jpeg
    image_path: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-5.jpeg
    alt: "20261020_Image-5.jpeg"
  - url: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-6.jpeg
    image_path: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-6.jpeg
    alt: "20261020_Image-6.jpeg"
  - url: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-7.jpeg
    image_path: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-7.jpeg
    alt: "20261020_Image-7.jpeg"
  - url: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-8.jpeg
    image_path: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-8.jpeg
    alt: "20261020_Image-8.jpeg"
  - url: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-9.jpeg
    image_path: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-9.jpeg
    alt: "20261020_Image-9.jpeg"
  - url: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-10.jpeg
    image_path: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-10.jpeg
    alt: "20261020_Image-10.jpeg"
  - url: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-11.jpeg
    image_path: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-11.jpeg
    alt: "20261020_Image-11.jpeg"
  - url: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-12.jpeg
    image_path: /assets/images/stat_cafe/Fu_Oct_20_2026/20261020_Image-12.jpeg
    alt: "20261020_Image-12.jpeg"
---


<img src="https://github.com/tamusgsa/tamusgsa.github.io/blob/master/assets/images/stat_cafe/Fu_Oct_20_2026/IMG_0640.jpg?raw=true" alt="Header" width="330" style="float: right;"/> 



### Control-Geometry Straightening for Latent Planning

- Time: Tuesday, 10/20/2026 from 11:10AM to 12:25PM
- Location: BLOC 448


[RSVP Link](<https://urldefense.com/v3/__https://forms.gle/uJLXGqXS5LU1UQjh7__;!!KwNVnqRv!AyrP3Ret1Iq2rUsLY-M0aTUpYgS35D-20c3GjiSEjCilAv5QnrvUOXGCyvZZbX2sPOtlxmlvmbV0wBV9x3-1tpg$>)

[Zoom Link](<https://tamu.zoom.us/j/95358404036?pwd=aKGbZrMI8DlOuTvKXaabFQPyrYsPnM.1>)

### Description

Joint-embedding predictive architectures enable planning with latent world models, but accurate transition prediction alone does not ensure that the planning objective is easy to optimize. We introduce Control-Geometry Straightening (CGS), a single auxiliary loss that learns planner-friendly representations by directly straightening control geometry for sampling-efficient planning. CGS matches pairwise cosine similarities among actions to those among corresponding latent differences only using local transitions from pixel–action pairs. The loss can be applied across world-model architectures using end-to-end learned or pretrained representations. Under linear-dynamics, our theoretical analysis connects this objective to temporal straightening and more balanced terminal-cost curvature across the full planning horizon, yielding finite-budget guarantees for MPPI, local contraction results for CEM, and convergence bounds for gradient descent. Across four control environments and multiple planners, CGS improves planning with fewer sampled candidates and refinement steps, achieving success-rate gains up to 20 and 12.6 percentage points over LeWorldModel (LeWM) and its temporal-straightening variant (LeWM+TS), respectively, with sampling-based planners using 128 candidates per update. Probes, comparisons with DINO-WM architecture, and planner-side ablations clarify how latent motion organization, state dependence, and dynamical context shape planning behavior. Straightening control geometry thus makes good action sequences easier to find under limited planning budgets.


### Our Speaker

Ziang Fu is a second-year PhD student in the Department of Statistics at Texas A&M University. His research mainly focuses on statistical foundation in world models, JEPA, representation geometry, multimodal reasoning, and optimization. He obtained his BS in Statistics from Beijing Normal University, China.



<!--
### Presentation
<iframe src="https://drive.google.com/file/d/1tN9MfS-UIcedYkMafjpg1VxsRcSM0t8T/preview" width="640" height="480" allow="autoplay"></iframe>
-->

<!--
### Recording
<iframe width="560" height="315" src="https://www.youtube.com/embed/hEnEmymzzU0?si=wj7aBvE_v2OlDE-k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
-->


### Gallery

{% include gallery id="layouts_gallery" %}


