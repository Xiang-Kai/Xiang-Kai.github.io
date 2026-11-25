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

Hi! I am Xiangkai Ma (马向恺). I'm currently a Ph.D. student at <a href="https://www.nju.edu.cn/en/">Nanjing University of China</a> since September 2024, a member of <a href="https://keysoftlab.nju.edu.cn/main.psp">State Key Laboratory for Novel Software Technology@NJU</a>, supervised by Professor <a href="https://cs.nju.edu.cn/lwz/index.htm">Wenzhong Li (李文中)</a> and <a href="https://cs.nju.edu.cn/58/1e/c2639a153630/page.htm">Sanglu Lu (陆桑璐)</a>. I received B.S. degree (Highest Honor) in Mathematics-Physics Fundamental Science from <a href="https://www.yingcai.uestc.edu.cn/xygk/xyjj.htm">Yingcai Honors College</a> at <a href="https://en.uestc.edu.cn/">University of Electronic Science and Technology of China</a> in 2022.

Over the past period of time (2022-2024), I focus on problems in time series analysis, where beautiful theory and practical methodology meet. My research focus in the field of time series analysis can be categorized into the following three directions:

- *Traditional time series analysis based on spectral disentanglement and multi-periodic pattern modeling, as **TS3Net** [2023] and **Pets** [2025];*
- *Fusion across multiple time series domains and cross-domain generalization, as **WQ4TS** [2024] and **TimeControl** [2024];*
- *Zero-shot time series forecasting and classification leveraging pre-trained vision models, as **TimeArtist** [2025].*

My current research focuses on embodied intelligence, including Vision-Language-Action (VLA) models, World Action Models (WAMs), and long-horizon embodied agents:

- *Unifying visual perception and action control through an implicit visual chain-of-thought, as **VITA** [2025].*
- *Bridging world-action modeling and latent motion semantics through Motion Chain-of-Thought, as **PILOT**.*
- *Learning from demonstration context while tracking execution progress for long-horizon manipulation, as **RoboDemo**.*

I am currently a Research Intern at <a href="https://research.joyai.com/">Joy Future Academy, JD</a>, Shenzhen. For research discussions and collaboration, please feel free to contact me at **xiangkai.ma@smail.nju.edu.cn**.

<span class="anchor" id="-educations"></span>

# Education

<ol class="experience-timeline" aria-label="Education timeline">
  <li class="experience-item">
    <div class="experience-date"><time datetime="2024-09">Sep. 2024</time> &ndash; Present</div>
    <div class="experience-content">
      <div class="experience-heading">
        <div>
          <h2><a href="https://www.nju.edu.cn/en/">Nanjing University</a></h2>
          <p class="experience-department"><a href="https://cs.nju.edu.cn/">School of Computer Science</a></p>
        </div>
        <div class="experience-logos">
          <img src="images/institutions/nju.svg" alt="Nanjing University emblem" loading="lazy">
          <img src="images/institutions/nju-cs.svg" alt="Nanjing University School of Computer Science emblem" loading="lazy">
        </div>
      </div>
      <p class="experience-degree">Ph.D. in Computer Science</p>
    </div>
  </li>
  <li class="experience-item">
    <div class="experience-date"><time datetime="2022-09">Sep. 2022</time> &ndash; <time datetime="2024-06">Jun. 2024</time></div>
    <div class="experience-content">
      <div class="experience-heading">
        <div>
          <h2><a href="https://www.nju.edu.cn/en/">Nanjing University</a></h2>
          <p class="experience-department"><a href="https://cs.nju.edu.cn/">Department of Computer Science and Technology</a></p>
        </div>
        <div class="experience-logos">
          <img src="images/institutions/nju.svg" alt="Nanjing University emblem" loading="lazy">
          <img src="images/institutions/nju-cs.svg" alt="Nanjing University School of Computer Science emblem" loading="lazy">
        </div>
      </div>
      <p class="experience-degree">Graduate Studies in Computer Science and Technology</p>
      <p class="experience-note">Selected for the integrated master's-to-Ph.D. program.</p>
    </div>
  </li>
  <li class="experience-item">
    <div class="experience-date"><time datetime="2018-09">Sep. 2018</time> &ndash; <time datetime="2022-06">Jun. 2022</time></div>
    <div class="experience-content">
      <div class="experience-heading">
        <div>
          <h2><a href="https://en.uestc.edu.cn/">University of Electronic Science and Technology of China</a></h2>
          <p class="experience-department"><a href="https://www.yingcai.uestc.edu.cn/">Yingcai Honors College</a></p>
        </div>
        <div class="experience-logos experience-logos--uestc">
          <img src="images/institutions/uestc.svg" alt="University of Electronic Science and Technology of China emblem" loading="lazy">
          <img src="images/institutions/yingcai.png" alt="Yingcai Honors College logo" class="institution-logo--dark" loading="lazy">
        </div>
      </div>
      <p class="experience-degree">B.S. in Mathematics-Physics Fundamental Science <strong>(with the highest honors)</strong></p>
    </div>
  </li>
</ol>

<span class="anchor" id="-internships"></span>

# Internship

<ol class="experience-timeline experience-timeline--internship" aria-label="Internship timeline">
  <li class="experience-item">
    <div class="experience-date"><time datetime="2026-04">Apr. 2026</time> &ndash; Present</div>
    <div class="experience-content">
      <div class="experience-heading">
        <div>
          <h2>Research Intern</h2>
          <p class="experience-department"><a href="https://research.joyai.com/">Joy Future Academy, JD</a>, Shenzhen</p>
        </div>
        <div class="experience-logos"><img src="images/institutions/jd.png" alt="JD logo" class="institution-wordmark institution-wordmark--jd" loading="lazy"></div>
      </div>
      <p class="experience-description">Conducting research on embodied foundation models and agents, with a focus on integrating World Action Models (WAMs) and Latent Action Models (LAMs) through motion-semantic reasoning (<a href="https://pilot-wam-2026.github.io/">PILOT</a>), and developing in-context learning and persistent demonstration-intent and execution-progress memories for long-horizon embodied models and agents (<a href="https://robodemo-2027.github.io/">RoboDemo</a>).</p>
    </div>
  </li>
</ol>

# 🔥 News
- *2026.11*: Our paper RoboDemo is now available, with the code and weights openly released ([project website](https://robodemo-2027.github.io/)).
- *2026.7*: Our paper PILOT is now available, with the code and weights openly released ([project website](https://pilot-wam-2026.github.io/)).
- *2026.7*: Our paper has been accepted by ACM Multimedia 2026 (MM 2026).
- *2026.02*: &nbsp;🎉🎉 Our paper has been accepted by IEEE Conference on Computer Vision and Pattern Recognition (CVPR26). 
- *2026.01*: &nbsp;🎉🎉 Our paper has been accepted by ACM Transactions on Knowledge Discovery from Data (TKDD). 
- *2025.12*: &nbsp;🎉🎉 Our paper has been accepted by IEEE International Conference on Computer Communications (INFOCOM26). 
- *2024.08*: &nbsp;🎉🎉 Our paper has been accepted by ACM Transactions on Knowledge Discovery from Data (TKDD).
- *2024.02*: &nbsp;🎉🎉 Our paper has been accepted by 40st IEEE International Conference on Data Engineering (ICDE24). 

# 📝 Publications 

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% RoboDemo -->

<div class='paper-box'><div class='paper-box-image'><div class="paper-figure"><div class="badge">Under Review</div><a href="images/robodemo-framework.svg" aria-label="View RoboDemo Figure 2 at full size"><img src="images/robodemo-framework.png" alt="RoboDemo Figure 2: demonstration-intent and interaction-progress memories with Dual-Cascaded Test-Time Training." width="1600" height="987" loading="lazy"></a></div></div>
<div class='paper-box-text' markdown="1">

RoboDemo: Reconciling Demonstration Intent and Execution Progress for Long-Horizon Manipulation

**Xiangkai Ma**, Zhihao Yuan, Linbo Zhai, Xinyi Wang, Junjie Wang, Sheng Xu, Guiliang Liu, Han Zhang, Chuyi Chen, Jifeng Gao, Wenzhong Li

[**Paper**](files/robodemo.pdf) |
[**Demo & Website**](https://robodemo-2027.github.io/) |
[**Project & Code**](https://github.com/robodemo-2027/RoboDemo) |
[**Model Weights**](https://huggingface.co/collections/mxk1998/robodemo-6afc7693656d0965ce5466bc) |
[**Release & Guides**](https://robodemo-2027.github.io/#resources)
</div>
</div>

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% PILOT -->

<div class='paper-box'><div class='paper-box-image'><div class="paper-figure"><div class="badge">Under Review</div><a href="images/pilot-framework.svg" aria-label="View PILOT Figure 3 at full size"><img src="images/pilot-framework.png" alt="PILOT Figure 3: world-model and action-perceiver branches with Representational Deduction and a Causal Dynamics Engine." width="1600" height="884" loading="lazy"></a></div></div>
<div class='paper-box-text' markdown="1">

Motion Chain of Thought: Disentangling Motion Semantics from Visual Appearance for Robotic Manipulation

**Xiangkai Ma**, Xinyi Wang, Junjie Wang, Sheng Xu, Mingyang Li, Yue Ma, Han Zhang, Yuzheng Zhuang, Wenzhong Li, Zhihao Yuan

[**Paper**](files/pilot.pdf) |
[**Demo & Website**](https://pilot-wam-2026.github.io/) |
[**Project & Code**](https://github.com/pilot-wam-2026/pilot-code) |
[**Model Weights**](https://huggingface.co/mxk1998/WM4A) |
[**Release & Guides**](https://pilot-wam-2026.github.io/#resources)
</div>
</div>

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% VITA -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026 (ccf-a)</div><img src='images/vita.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Unifying Perception and Action: A Hybrid-Modality Pipeline with Implicit Visual Chain-of-Thought for Robotic Action Generation

**Xiangkai Ma**, Lekai Xing, Han Zhang, Wenzhong Li, Sanglu Lu

Conference: [**2026 IEEE/CVF Computer Vision and Pattern Recognition Conference**](https://openaccess.thecvf.com/content/CVPR2026/papers/Ma_Unifying_Perception_and_Action_A_Hybrid-Modality_Pipeline_with_Implicit_Visual_CVPR_2026_paper.pdf)

[**Paper**](https://arxiv.org/pdf/2511.19859) |
[**arXiv**](https://arxiv.org/abs/2511.19859) |
[**Demo & Website**](https://xiang-kai.github.io/vita-cvpr26.github.io/) |
[**Project & Code**](https://github.com/Xiang-Kai/VITA)
</div>
</div>

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% TimesBook -->

<div class='paper-box'><div class='paper-box-image'><div class="paper-figure"><div class="badge">MM 2026 (ccf-a)</div><a href="images/timesbook-framework.svg" aria-label="View TimesBook Figure 2 at full size"><img src="images/timesbook-framework.png" alt="TimesBook Figure 2: cross-modal alignment, masked variate composer, multimodal codebook, and fusion classifier." width="1600" height="886" loading="lazy"></a></div></div>
<div class='paper-box-text' markdown="1">

TimesBook: Cross-Modal Visual Augmentation for Few-Shot Multivariate Time Series Classification

Junjie Wang, **Xiangkai Ma**, Mingkai Lin, Haoming Li, Sanglu Lu, Wenzhong Li

Conference: **2026 ACM Multimedia**

[**Paper**](files/timesbook-mm2026.pdf)
</div>
</div>

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% Demus -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INFOCOM 2026 (ccf-a)</div><img src='images/demus.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

DeMus: Large Multimodal Model Serving at the Edge with Diffusion-Based Scheduling

Han Zhang, **Xiangkai Ma**, Tiantian Wang, Mingkai Lin, Wenzhong Li

Conference: [**2026 IEEE Conference on Computer Communications**](https://ieeexplore.ieee.org/document/11571478)

[**Paper**](files/demus-infocom2026.pdf)
</div>
</div>

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% TimeArtist -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/timeartist.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Temporal-Visual Semantic Alignment: A Unified Architecture for Transferring Spatial Priors from Vision Models to Zero-Shot Temporal Tasks

**Xiangkai Ma**, Han Zhang, Wenzhong Li, Sanglu Lu

[**Paper**](https://arxiv.org/pdf/2511.19856) |
[**arXiv**](https://arxiv.org/abs/2511.19856) 
</div>
</div>

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% WQ4TS -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TKDD (ccf-b)</div><img src='images/wq4ts.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

A Wave is Worth 100 Words: Investigating Cross-Domain Transferability in Time Series

**Xiangkai Ma**, Xiaobin Hong, Wenzhong Li, Sanglu Lu

Journal: [**ACM Transactions on Knowledge Discovery from Data**](https://dl.acm.org/journal/tkdd)

[**Paper**](https://arxiv.org/pdf/2412.00772) |
[**arXiv**](https://arxiv.org/abs/2412.00772) |
[**Project & Code**](https://github.com/Xiang-Kai/WQ4TS)
</div>
</div>

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% Pets -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/pets.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Energy-Aware Pattern Disentanglement: A Generalizable Pattern Assisted Architecture for Multi-task Time Series Analysis

**Xiangkai Ma**, Xiaobin Hong, Wenzhong Li, Sanglu Lu

[**Paper**](https://arxiv.org/pdf/2504.14209) |
[**arXiv**](https://arxiv.org/abs/2504.14209) |
[**Project & Code**](https://github.com/Xiang-Kai/Pets) 
</div>
</div>

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% TimeControl -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/timecontrol.PNG' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Domain Fusion Controllable Generalization for Cross-Domain Time Series Forecasting from Multi-Domain Integrated Distribution

**Xiangkai Ma**, Xiaobin Hong, Mingkai Lin, Han Zhang, Wenzhong Li, Sanglu Lu

[**Paper**](https://arxiv.org/pdf/2412.03068) |
[**arXiv**](https://arxiv.org/abs/2412.03068) |
[**Project & Code**](https://github.com/Xiang-Kai/TimeControl)
</div>
</div>

<!-- %%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%% TS3Net -->

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICDE 2024 (ccf-a)</div><img src='images/ts3net.PNG' alt="sym" width="100%"></div></div>
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
