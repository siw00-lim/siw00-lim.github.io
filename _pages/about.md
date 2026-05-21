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

# 😃 About me

I'm an Integrated Ph.D. student at [**Artificial Intelligence & Machine Learning (U-AIM) Lab.**](http://sanctusfactory.com/u-aim/) in KAIST, under the supervision of Prof. Chang D. Yoo. My research focuses on **3D scene representation and neural rendering**, with particular interest in **Gaussian Splatting** and methods that bridge classical computer vision and modern deep learning for high-fidelity 3D reconstruction.

My research interests include:

- 3D Vision & Neural Rendering
- Gaussian Splatting
- Computer Vision
- Deep Learning


# 🔥 News

- *2026.05*: 🎉 One paper (**GADA**) accepted to **ICML 2026**
<!-- 아래는 자유롭게 더 추가하세요 (옛날 → 최근 순서가 위에서 아래로 보이는 게 일반적입니다) -->
<!-- - *YYYY.MM*: 🎉 ... -->


# 📝 Publications 

## 2026

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src='images/gada.jpg' alt="GADA" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[[C1] GADA: Geometry-Aware Deformable Aggregation for Image-Based Gaussian Splatting](https://openreview.net/pdf?id=AZLj6ObEDF)

**Siwoo Lim**, Sunjae Yoon, Gwanhyeong Koo, Chang D. Yoo

**ICML** 2026

[[project page]](https://siw00-lim.github.io/GADA-Project-Page/)

- A warping-based Gaussian Splatting framework that recovers high-frequency details by actively searching for displaced pixel cues with deformable offsets, achieving 2.13× faster rendering than the IBGS baseline.
</div>
</div>


# 🎖 Honors and Awards

<!-- 받으신 상 / 장학금 / 인증서 등을 여기에 채워주세요. 예시:
- *2024.10* **Best Paper Award**, ...
- *2022.09* TensorFlow Developer Certificate
-->


# 📖 Educations

- *YYYY.MM - Present*, **Integrated Ph.D.** in Electrical Engineering. (KAIST)
- *YYYY.MM - YYYY.MM*, **B.S.** in [학부 전공] ([학부 학교])

<!-- 입학/졸업 연도를 정확히 채워주세요. -->


# 💬 Invited Talks

<!-- 초청 강연이 있었다면 추가, 없다면 이 섹션 통째로 지우세요. -->


# 💻 Internships

<!-- 인턴십 경험이 있었다면 추가, 없다면 이 섹션 통째로 지우세요. 예시:
- *2024.06 - 2024.08*, [회사명](https://...), 부서/팀, 국가.
-->
