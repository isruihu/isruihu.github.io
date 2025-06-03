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
I am a third-year PhD student in Computer Science at the Beijing Jiaotong University <a href="http://adam-bjtu.org/">ADaM Lab</a>, where I am advised by <a href="https://faculty.bjtu.edu.cn/9129/"> Prof. Jitao Sang </a>. Prior to starting my PhD, I obtained a Master's degree with a major in Computer Technology from Beijing Jiaotong University and a Bachelor's degree with a major in Software Engineering from Xiangtan University.

My research interest includes reliable machine Llarning and multimodal large language model.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MM 2023 Oral</div><img src='images/Echoes.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Echoes: Unsupervised Debiasing via Pseudo-bias Labeling in an Echo Chamber
**Rui Hu**, Yahan Tu, Jitao Sang

</div></div>
