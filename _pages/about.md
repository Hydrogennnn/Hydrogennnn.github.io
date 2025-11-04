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

Jiedong Wang(王杰栋) is an undergraduate student at the College of Computer Science, Sichuan University(SCU), advised by Prof.[Hao Wang](https://cshaowang.github.io) of [XLearning](https://pengxi.me/) research group at SCU. 

His research focuses on Multi-view Learning and Continual Learning.

# 🔥 News
- *2025.4*: &nbsp;Two papers about Multi-view learning were accepted by International Joint Conference on Artificial Intelligence(IJCAI 2025)!

# 📝 Publications 
\* Equal contribution $\dagger$ Corresponding author
{% assign papers = site.data.papers %}

<!-- {% for paper in papers %}
<div class='paper-box'>
  <div class='paper-box-image'>
    <img src='{{ paper.img }}' alt='sym'>
  </div>
  <div class='paper-box-text'>
  {{ paper.src | markdownify}}
    <a href="{{ paper.link }}" target="_blank">{{ paper.title}}</a>
    <div class="authors">{{ paper.authors | markdownify }}</div>
  </div>
</div>
{% endfor %} -->

<div class='paper-box'>
  <div class='paper-box-image'>
    <img src='images/DualVAE.jpg' alt='sym'>
  </div>
  <div class='paper-box-text'>
    <p><strong>[IJCAI2025]</strong></p>
    <a href="https://doi.org/10.24963/ijcai.2025/701" target="_blank">
      Learning Robust Multi-view Representation Using Dual-masked VAEs
    </a>
    <div class="authors">
      <strong>Jiedong Wang</strong>, Kai Guo, Peng Hu, Xi Peng, Hao Wang$\dagger$
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <img src='images/CL2P.jpg' alt='sym'>
  </div>
  <div class='paper-box-text'>
    <p><strong>[IJCAI2025]</strong></p>
    <a href="https://doi.org/10.24963/ijcai.2025/586" target="_blank">
      Disentangling Multi-view Representations via Curriculum Learning with Learnable Prior
    </a>
    <div class="authors">
      Kai Guo, <strong>Jiedong Wang</strong>, Xi Peng, Peng Hu, Hao Wang$\dagger$
    </div>
  </div>
</div>



# 🎖 Honors and Awards
- *2023.11*: &nbsp;The 2023 ICPC Asia Hefei Regional Contest, Silver Medal.
- *2024.9*: &nbsp;National Scholarship(Undergraduate, Top 2%).
- *2025.10*: &nbsp;Outstanding Graduate of Sichuan Province.


<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js">
</script>
<span id="busuanzi_container_site_pv">    
	Total Views:<span id="busuanzi_value_site_pv"></span>
</span>