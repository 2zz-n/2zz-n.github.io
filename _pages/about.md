---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

# 🤔 About Me
<span class='anchor' id='about-me'></span>

I am currently a second-year Ph.D. student at the School of Computer Science, Shanghai Jiao Tong University, advised by Prof. [Li Niu](https://www.ustcnewly.com/). My research focuses on AIGC and MLLM. Besides academic research, I enjoy working out and playing badminton.

# 🔥 News
- *2026.04*: &nbsp;🎉🎉 Our paper [RGDiffusion](https://github.com/bcmi/Object-Reflection-Generation-Dataset-DEROBA) is accepted by ICME 2026!
- *2025.02*: &nbsp;🎉🎉 Our paper [GPSDiffusion](https://github.com/bcmi/GPSDiffusion-Object-Shadow-Generation) is accepted by CVPR 2025!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025 Accepted</div><img src='images/shadow.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Shadow Generation Using Diffusion Model with Geometry Prior](https://github.com/bcmi/GPSDiffusion-Object-Shadow-Generation)

Haonan Zhao, Qingyang Liu, Xinhao Tao, Li Niu, Guangtao Zhai

- We enhance diffusion-based shadow generation by incorporating geometric priors to improve realism. We first predict a rotated bounding box and matched shadow shapes for the foreground object, then inject this geometric guidance into ControlNet for more plausible shadow synthesis.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICME 2026 Accepted</div><img src='images/reflection.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reflection Generation for Composite Image Using Diffusion Model](https://github.com/bcmi/Object-Reflection-Generation-Dataset-DEROBA)

Haonan Zhao, Qingyang Liu, Jiaxuan Chen, Li Niu

- We propose a method that injects reflection placement and appearance priors into a foundation diffusion model, utilizing a type-aware design to handle diverse reflection categories. Moreover, we construct the first large-scale object reflection dataset DEROBA for realistic reflection generation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2026 Submitted</div><img src='images/timo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Timo: Temporal Interval Modeling for Subject-Driven Video Generation

Haonan Zhao, Jiaxuan Chen, Bingjie Gao, Haoran Jiang, Qingyang Liu, Shuochen Chang, Xiaodong Cun, Li Niu

- We proposed Timo, an interval-aware video generation framework featuring Interval-Masked Cross-Attention and Adaptive Gaussian ROPE, achieving state-of-the-art temporal control precision for subject-driven video generation.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MMAsia 2025 Accepted</div><img src='images/dual-space.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Dual-space Adaptive Fusion for Self-supervised Text-guided Image Editing](https://dl.acm.org/doi/full/10.1145/3743093.3770946)

Qingyang Liu\*, Haonan Zhao\*, Li Niu (\*=Co-first author)

- We propose a dual-space adaptive editing framework that appropriately fuses the source and target elements in two spaces in a self-supervised manner. The entire process does not require additional data or manual parameter tuning.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PRCV 2025 Accepted</div><img src='images/latent-basis.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning to Combine Latent Basis for Diffusion-Based Image Attribute Editing](https://link.springer.com/chapter/10.1007/978-981-95-5740-0_37)

Qingyang Liu\*, Haonan Zhao\*, Li Niu (\*=Co-first author)

- We propose a diffusion-based image editing method that learns to combine latent basis vectors in a subspace for precise attribute editing. Our approach avoids extra training and uses a novel contrastive loss to improve editing accuracy and preserve other image attributes.
</div>
</div>

# 🎖 Awards
- Outstanding Student Scholarship, Outstanding Student Cadre

# 📖 Educations
- *2024.09 - Present*, Ph.D., School of Computer Science, Shanghai Jiao Tong University.
- *2021.09 - 2024.06*, M.S., School of Mathematical Sciences, University of Chinese Academy of Sciences.
- *2017.09 - 2021.06*, B.S., School of Science, China University of Mining and Technology (Beijing).

# 🌟 Offline Mode (*Life*) {#offline-mode}
- 💖 Since 2024.11.23
- 🎮 Esports enthusiast: League of Legends (Diamond rank) and VALORANT (Immortal rank).
