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

Hi! I am Xiangkai Ma (马向恺). I'm currently a Ph.D. student at <a href="https://www.nju.edu.cn/en/">Nanjing University of China</a> from 2024 Spring, a member of <a href="https://keysoftlab.nju.edu.cn/main.psp">State Key Laboratory for Novel Software Technology@NJU</a>, supervised by Professor <a href="https://cs.nju.edu.cn/lwz/index.htm">Wenzhong Li (李文中)</a> and <a href="https://cs.nju.edu.cn/58/1e/c2639a153630/page.htm">Sanglu Lu (陆桑璐)</a>. I received B.S. degree (Highest Honor) in Mathematics-Physics Fundamental Science from <a href="https://www.yingcai.uestc.edu.cn/xygk/xyjj.htm">Yingcai Honors College</a> at <a href="https://en.uestc.edu.cn/">University of Electronic Science and Technology of China</a> in 2022.

Over the past period of time (2022-2024), I focus on problems in time series analysis, where beautiful theory and practical methodology meet. My research focus in the field of time series analysis can be categorized into the following three directions:

- *Traditional time series analysis based on spectral disentanglement and multi-periodic pattern modeling, as **TS3Net** [2023] and **Pets** [2025];*
- *Fusion across multiple time series domains and cross-domain generalization, as **WQ4TS** [2024] and **TimeControl** [2024];*
- *Zero-shot time series forecasting and classification leveraging pre-trained vision models, as **TimeArtist** [2025].*

Recently, I have been deeply captivated by the vast application potential of embodied robots (such as RoboTwin 2.0, Pi0.5, etc.) in real-world scenarios and hope to pursue research related to Vision-Language-Action (VLA) during my upcoming doctoral studies (2025-2028). Under the guidance of <a href="[https://cs.nju.edu.cn/lwz/index.htm/](https://cs.nju.edu.cn/c9/41/c2639a51521/page.htm)">Prof. Wenzhong Li</a>, my initial foray into the field of embodied intelligence is:

- *Unifying visual perception and action control through an implicit visual chain-of-thought, as **VITA** [2025].*

# 🔥 News
- *2025.11*: &nbsp;🎉🎉 Our paper receives Minor Revision from ACM Transactions on Knowledge Discovery from Data (CCF-B). 
- *2025.10*: &nbsp;🎉🎉 Our paper receives Minor Revision from IEEE Transactions on Knowledge and Data Engineering (CCF-A). 
- *2024.08*: &nbsp;🎉🎉 Our paper has been accepted by ACM Transactions on Knowledge Discovery from Data (CCF-B), congratulations to Xiaobin Hong!
- *2024.02*: &nbsp;🎉🎉 Our paper has been accepted by 40st IEEE International Conference on Data Engineering (CCF-A). 

# 📝 Preprints 

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% VITA -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review 2025</div><img src='images/vita.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Unifying Perception and Action: A Hybrid-Modality Pipeline with Implicit Visual Chain-of-Thought for Robotic Action Generation

**Xiangkai Ma**, Lekai Xing, Han Zhang, Wenzhong Li, Sanglu Lu

[**Paper**](https://arxiv.org/pdf/2511.19859) |
[**arXiv**](https://arxiv.org/abs/2511.19859) |
[**Demo & Website**](https://vita-cvpr26.github.io/) |
[**Project & Code**](https://github.com/vita-cvpr26/vita)
</div>
</div>

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% TimeArtist -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review 2025</div><img src='images/timeartist.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Temporal-Visual Semantic Alignment: A Unified Architecture for Transferring Spatial Priors from Vision Models to Zero-Shot Temporal Tasks

**Xiangkai Ma**, Han Zhang, Wenzhong Li, Sanglu Lu

[**Paper**](https://arxiv.org/pdf/2511.19856) |
[**arXiv**](https://arxiv.org/abs/2511.19856) 
</div>
</div>

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% Pets -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review 2024</div><img src='images/pets.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Energy-Aware Pattern Disentanglement: A Generalizable Pattern Assisted Architecture for Multi-task Time Series Analysis

**Xiangkai Ma**, Xiaobin Hong, Wenzhong Li, Sanglu Lu

[**Paper**](https://arxiv.org/pdf/2504.14209) |
[**arXiv**](https://arxiv.org/abs/2504.14209) |
[**Project & Code**](https://github.com/Xiang-Kai/Pets) 
</div>
</div>

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% TimeControl -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review 2024</div><img src='images/timecontrol.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Domain Fusion Controllable Generalization for Cross-Domain Time Series Forecasting from Multi-Domain Integrated Distribution

**Xiangkai Ma**, Xiaobin Hong, Mingkai Lin, Han Zhang, Wenzhong Li, Sanglu Lu

[**Paper**](https://arxiv.org/pdf/2412.03068) |
[**arXiv**](https://arxiv.org/abs/2412.03068) |
[**Project & Code**](https://github.com/TimeControl-2025/TimeControl) 
</div>
</div>

# 📝 Publications 

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% WQ4TS -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TKDD</div><img src='images/wq4ts.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

A Wave is Worth 100 Words: Investigating Cross-Domain Transferability in Time Series

**Xiangkai Ma**, Xiaobin Hong, Wenzhong Li, Sanglu Lu

Journal: [**ACM Transactions on Knowledge Discovery from Data**](https://dl.acm.org/journal/tkdd)

[**Paper**](https://arxiv.org/pdf/2412.00772) |
[**arXiv**](https://arxiv.org/abs/2412.00772) |
[**Project & Code**](https://anonymous.4open.science/r/WQ4TS)
</div>
</div>

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% TS3Net -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICDE 2024</div><img src='images/ts3net.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

TS3Net: Triple Decomposition with Spectrum Gradient for Long-Term Time Series Analysis

**Xiangkai Ma**, Xiaobin Hong, Wenzhong Li, Sanglu Lu

Conference: [**2024 IEEE 40th International Conference on Data Engineering**](https://ieeexplore.ieee.org/xpl/conhome/1000178/all-proceedings) 

[**Paper**](https://ieeexplore.ieee.org/document/10597845) |
[**Project & Code**](https://github.com/Xiang-Kai/TS3Net)
</div>
</div>

# 🎖 Honors and Awards
- *2025* Academic Scholarship in NJU. 
- *2024* Scholarship for Outstanding Graduate Students in NJU. 
- *2023* Postgraduate Scholarship in NJU. 
- *2022* Honors Bachelor's Degree in UESTC. 

# 📞 Services
- *Spring 2025*: Jiangsu Province Graduate Summer School (Interdisciplinary Big Data Mining Theory and Applications), NJU, Teaching Assistant
- *Spring 2024*: Jiangsu Province Graduate Summer School (Interdisciplinary Big Data Mining Theory and Applications), NJU, Teaching Assistant
- *Conference Reviewer*: AAAI 2026, ICLR 2026.

# 📖 Educations
- *2024.09 - 2028.06 (Now)*, Nanjing University, School of Computer Science.
- *2022.09 - 2024.06*, Nanjing University, Department of Computer Science and Technology. 
- *2018.09 - 2022.06*, University of Electronic Science and Technology of China. YingCai Honors College.
