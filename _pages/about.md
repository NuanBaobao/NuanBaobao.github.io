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

Hi！I am a first year Master student at University of Electronic Science and Technology of China. My advisor is <a href='https://scholar.google.com/citations?user=-kSTt40AAAAJ&hl=zh-CN'>Shuhang Gu</a>. I received the B.S. degree from the ShangDong University in 2023.  

My research interest is BEV perception, mage/video generation and so on. 

**If you have any suggestions for cooperation in these filed, please feel free to contact me.**

# 🔥 News
- *2024.07*: &nbsp;🎉🎉 Our work "[PerlDiff: Controllable Street View Synthesis Using Perspective-Layout Diffusion Models](https://arxiv.org/abs/2407.06109)" is published on Arxiv. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PerlDiff</div><img src='images/perldiff.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[PerlDiff: Controllable Street View Synthesis Using Perspective-Layout Diffusion Models](https://arxiv.org/abs/2407.06109)

**Jinhua Zhang**,  Hualian Sheng, Sijia Cai, Bing Deng, Qiao Liang, Wen Li, Ying Fu, Jieping Ye, Shuhang Gu

[**arXiv**](https://arxiv.org/abs/2407.06109)/[**code**](https://github.com/LabShuHangGU/PerlDiff)/[**bibtex**]([https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=tyYxiXoAAAAJ&citation_for_view=tyYxiXoAAAAJ:u5HHmVD_uO8C](https://scholar.google.com/scholar_lookup?arxiv_id=2407.06109))

- Our PerlDiff employs 3D geometric priors to guide the generation of street view images with precise object-level control within the network learning process, resulting in a more robust and controllable output. Moreover, it demonstrates superior controllability compared to alternative layout control methods. Empirical results justify that our PerlDiff markedly enhances the precision of generation on the NuScenes and KITTI.
</div>
</div>

