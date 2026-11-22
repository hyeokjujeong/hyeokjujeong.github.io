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

<span class='anchor' id='about-me'></span>

I am a Master's student in Mechanical Engineering at **Seoul National University**, advised by Prof. Frank C. Park in the Robotics Laboratory. I received my B.S. in Mechanical Engineering and Computer Science and Engineering (double major, *summa cum laude*) from Seoul National University in 2025.

My research focuses on **robot learning for manipulation**. I am interested in how generative policies (diffusion, flow matching) can exploit the structure that robot systems already possess, such as SE(3) geometry, symmetry, and task context, rather than relearning it from data, and in making such methods hold up on real robots, especially in compliant, contact-rich manipulation.

I have worked on SE(3)-equivariant diffusion sampling, memory architectures for contextual MDPs, vision-language-action models with variable compliance, and distillation for data-efficient policy learning.

**I am applying to PhD programs starting in Fall 2027.** Feel free to reach out via email!


# News
- *2026.11*: Our team ranked in the top 15 of the **NVIDIA V2D Challenge (Track 3)** and was invited to present our contact-simulation approach at the CoRL 2026 tutorial.
- *2026.09*: **CompVLA** is accepted to **CoRL 2026**.
- *2026.09*: Teaching assistant for *Introduction to Robotics* at SNU, with all sessions held in English.
- *2026.05*: **MATE** is released on [arXiv](https://arxiv.org/abs/2605.17431).
- *2026.01*: **Value Gradient Sampler** is accepted to **AISTATS 2026**.
- *2025.09*: Started my M.S. at Seoul National University.


# Publications
<sup>\*</sup> equal contribution, <sup>†</sup> corresponding author

## Conference Papers

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CoRL 2026</div><img src='images/compvla.png' alt="CompVLA" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**CompVLA: A Variable Compliance Vision-Language-Action Model for Contact-rich Manipulation**](https://openreview.net/forum?id=9SnXCYklB0)

Jongmin Kim<sup>\*</sup>, Junsu Ha<sup>\*</sup>, Che-Sang Park<sup>\*</sup>, Minchang Song, **Hyeokju Jeong**, Himchan Hwang, Jianlong Fu<sup>†</sup>, Frank C. Park<sup>†</sup>

[**Project Page**](https://compvla.github.io/) | [**Paper**](https://openreview.net/forum?id=9SnXCYklB0) | [**arXiv**](https://arxiv.org/abs/2609.23614)
- A VLA model that predicts variable compliance alongside actions for contact-rich manipulation on a real robot.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AISTATS 2026</div><img src='images/vgs.png' alt="VGS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Value Gradient Sampler: Learning Invariant Value Functions for Equivariant Diffusion Sampling**](https://proceedings.mlr.press/v300/hwang26a.html)

Himchan Hwang<sup>\*</sup>, **Hyeokju Jeong<sup>\*</sup>**, Dong Kyu Shin<sup>\*</sup>, Che-Sang Park, Sehee Kweon, Sangwoong Yoon<sup>†</sup>, Frank C. Park<sup>†</sup>

[**Paper**](https://proceedings.mlr.press/v300/hwang26a.html) | [**arXiv**](https://arxiv.org/abs/2502.13280)
- A diffusion sampler derived from optimal control that learns invariant value functions, yielding equivariant sampling.
</div>
</div>

## Preprints and Papers Under Review

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/mate.png' alt="MATE" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**MATE: Solving Contextual Markov Decision Processes with Memory of Accumulated Transition Embeddings**](https://arxiv.org/abs/2605.17431)

Himchan Hwang, **Hyeokju Jeong**, Gene Chung, Seungyeon Kim, Sangwoong Yoon<sup>†</sup>, Frank C. Park<sup>†</sup>

[**arXiv**](https://arxiv.org/abs/2605.17431)
- A permutation-invariant memory architecture that aggregates transition embeddings to infer the context of contextual MDPs.
</div>
</div>

- **Student as Strong as Teacher: Scaling Synthetic Data in Knowledge Distillation of Classifiers**<br>
  Taegyun Ahn<sup>\*</sup>, Sehee Kweon<sup>\*</sup>, Sanghoon Lee<sup>\*</sup>, **Hyeokju Jeong**, Himchan Hwang, Frank C. Park<sup>†</sup>, Sangwoong Yoon<sup>†</sup>. *Under review*


# Research Experience
- *2023.07 - Present*, **Robotics Laboratory, Seoul National University** (Advisor: Prof. Frank C. Park)<br>
  Graduate Research Assistant (previously Undergraduate Researcher). Generative policies and VLA models for compliant, contact-rich manipulation with real-robot deployment on a Franka Research 3; invariant and equivariant learning for sampling and policy representation.
- *2026.09 - 2026.11*, **NVIDIA Video to Data (V2D) Challenge, Track 3**<br>
  Team member. Built parts of a pipeline from egocentric human video to robot manipulation policy: stereo depth estimation (FoundationStereo), frame selection for object reconstruction (SAM 3D, MV-SAM3D), and torsional friction in the simulation contact model to fix grasp failures on thin objects.
- *2024.01 - 2024.12*, **Robot Vision Laboratory, Seoul National University** (Advisor: Prof. Jongwoo Lim)<br>
  Undergraduate Research Intern. View-dependent appearance modeling in 3D Gaussian Splatting; SLAM-coupled reconstruction of time-varying scenes.
- *2023.02 - 2023.06*, **AI-driven Simulation and Design Laboratory, Seoul National University** (Advisor: Prof. Do-Nyun Kim)<br>
  Undergraduate Researcher. Anomaly detection with convolutional autoencoders.


# Education
- *2025.09 - Present*, M.S. in Mechanical Engineering, Seoul National University. GPA 4.00/4.00 (4.15/4.30)
- *2019.03 - 2025.08*, B.S. in Mechanical Engineering and B.S. in Computer Science and Engineering (double major), Seoul National University, *summa cum laude*. GPA 3.94/4.00 (4.06/4.30)


# Teaching
- *Fall 2025, Fall 2026*, Teaching Assistant, **Introduction to Robotics**, Dept. of Mechanical Engineering, Seoul National University (Fall 2026 sessions conducted entirely in English)

{% comment %}
# Honors and Awards
- *2026.11* NVIDIA V2D Challenge, CoRL 2026 (Track 3): top 15 of 50 teams, invited talk
- *2025.08* *Summa cum laude*, Seoul National University
- *2024.03* SNU Development Fund Scholarship, Seoul National University
- *2023.09* National Scholarship for Science and Engineering, Korea Student Aid Foundation
- *2019 - 2025* Merit-based Scholarship, Seoul National University (Fall 2019; Spring 2023, 2024, 2025)
{% endcomment %}