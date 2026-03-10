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

<div align="center"><h1>SJZU
<sub><sup><em style="color: #382f90">Computer Vision and Remote Sensing Lab</em></sup></sub><br>
</h1></div>

**CVRS-YS801** is the Computer Vision and Remote Sensing Lab of **Shenyang Jianzhu University**, led by [**Prof. Yuan Shuai**](https://syjz.teacher.360eol.com/teacherBasic/preview?teacherId=23776).

Our research focuses on **Depth Estimation, Image Stitching, Object Detection**.
The organization hosts research code, experiments, and collaborative projects developed by members of the lab.

<h2 align="center">Member</h2>

<div style="display:flex; flex-wrap:wrap; justify-content:center; gap:30px; margin-top:20px;">
    <div style="text-align:center;">
        <a href="https://github.com/Dimon0000000">
            <img src="https://avatars.githubusercontent.com/u/85853517?v=4" width="120"
                style="border-radius:50%; box-shadow:0 4px 12px rgba(0,0,0,0.15);" />
            <br>
            <b>Dimon</b>
        </a>
    </div>
    <div style="text-align:center;">
        <a href="https://github.com/Haruko386">
            <img src="https://avatars.githubusercontent.com/u/140301008?v=4" width="120"
                style="border-radius:50%; box-shadow:0 4px 12px rgba(0,0,0,0.15);" />
            <br>
            <b>Haruko386</b>
        </a>
    </div>
    <div style="text-align:center;">
        <a href="https://github.com/WuSangui571">
            <img src="https://avatars.githubusercontent.com/u/93105459?v=4" width="120"
                style="border-radius:50%; box-shadow:0 4px 12px rgba(0,0,0,0.15);" />
            <br>
            <b>Sangui</b>
        </a>
    </div>
    <div style="text-align:center;">
        <a href="https://github.com/Ltohka">
            <img src="https://avatars.githubusercontent.com/u/72191648?v=4" width="120"
                style="border-radius:50%; box-shadow:0 4px 12px rgba(0,0,0,0.15);" />
            <br>
            <b>Tohka</b>
        </a>
    </div>
</div>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ARXIV</div><img src='images/cover/cover1.png' alt="cover1" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ApDepth: Aiming for Precise Monocular Depth Estimation Based on Diffusion Models](https://haruko386.github.io/research/article.pdf)

**Jiawei Wang**, Shuai Yuan, Mingbo Lei

\[[**Website**](https://haruko386.github.io/research/)\] \[[Paper](https://haruko386.github.io/research/article.pdf)\] \[[Demo](https://huggingface.co/spaces/developy/ApDepth)\] 

- We present Apdepth, a diffusion model, and associated fine-tuning protocol for monocular depth estimation.
- **Single-Step Inference**: We fine-tuned the diffusion model for single-step denoising inference, significantly reducing inference time.
- **Two-Stage Training Strategy**: We adopted a two-stage training strategy, with the first stage focusing on feature alignment within the model and the second stage emphasizing the model's learning of inference.
</div>
</div>
