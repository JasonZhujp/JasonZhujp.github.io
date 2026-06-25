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

I am currently a second-year PhD Student at the School of Data Science and Engineering, East China Normal University, under the supervision of [Prof. Weining Qian](https://scholar.google.com.hk/citations?hl=zh-CN&user=KqqoR6gAAAAJ) and [Prof. Xiang Li](https://lixiang3776.github.io/) in the PLANING (graPh mining and LANguage processING) lab.

My research interests include:
- **Agentic Reinforcement Learning**: algorithms and applications in agentic tool use, skill augmentation.
- **Large Language Models**: applications in graph RAG, toxicity detection.
- **Graph Neural Networks**: graph prompt tuning, graph active learning, graph self-supervised learning.

★★★ Feel free to reach out to me for academic discussions and collaborations!


<span class='anchor' id='publications'></span>

<!-- # 🔥 News
- *2025.05* 🥂🥂 Our paper [MetaTox](https://arxiv.org/abs/2412.15268) is accepted by ACL 2025! See you in Vienna!
- *2025.01* 🥂🥂 Our paper [HQA-GAE](https://dl.acm.org/doi/abs/10.1145/3696410.3714656) is accepted by WWW 2025! See you in Sydney!
- *2025.01* 📸📸 Our paper [ACAQL](https://ieeexplore.ieee.org/abstract/document/10836919) is accepted by TKDE 2025! The system has been applied to Credit Card Center of Bank of Shanghai. -->

{% include_relative includes/pub.md %}


# 🏆 Honors and Awards
- *2022-2026* Graduate Academic Scholarship, East China Normal University
- *2022.06* Outstanding Graduate, East China University of Science and Technology
- *2018-2022* Academic Excellence Scholarship, East China University of Science and Technology 

<span class='anchor' id='educations'></span>

# 📖 Educations
- *2022.09 - now*, PhD candidate, Data Science and Engineering, East China Normal University (via postgraduate recommendation and successive postgraduate and doctoral program) <img src='./images/logos/ecnu.png' style='width: 2.3em;'>
- *2018.09 - 2022.06*, Undergraduate, School of Information Science and Engineering, East China University of Science and Technology  <img src='./images/logos/ecust.png' style='width: 2.5em;'>


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<span class='anchor' id='internships'></span>

# 💻 Internships
- *2025.09 - 2026.06*, <img src='./images/logos/meituan.png' style='width: 2.1em;'> Meituan Longcat Team <img src='./images/logos/longcat.png' style='width: 2.1em;'>, Shanghai, China. Contributed to [Longcat-flash-thinking-2601](https://arxiv.org/abs/2601.16725), specializing in environment and task synthesis for agentic tool-use in post-training.

- *2026.07 - now*, <img src='.images/logos/baidu.png' style='width: 2.1em;'> Baidu AI Cloud <img src='./images/logos/aicloud.png' style='width: 2.1em;'>, Agent Policy Group, Beijing, China. Research intern.