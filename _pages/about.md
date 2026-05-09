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

<h1 style="font-size: 1.65rem; color: #174a7c; margin-bottom: 0.8rem;">
  👋 About Me
</h1>

<div style="
  background: linear-gradient(90deg, #eef6ff 0%, #f8fbff 100%);
  border-left: 4px solid #2b6cb0;
  border-radius: 10px;
  padding: 1.2rem 1.4rem;
  margin: 1rem 0 2rem 0;
  box-shadow: 0 8px 24px rgba(0, 0, 0, 0.04);
  line-height: 1.8;
  font-size: 1rem;
">

  <p>
    I am <strong>Peilin Liu</strong>, an undergraduate student in the 
    <strong>Excellent Engineer Program in Software Engineering</strong> at the 
    College of Software, Jilin University. I have worked on embodied intelligence, 
    large language models, multimodal spatial understanding, recommender systems, 
    federated learning, and time-series forecasting.
  </p>

  <p>
    I have research experience in natural language processing, recommender systems, 
    and multimodal understanding. Recently, my work has been accepted by 
    <strong>SIGIR 2026 (CCF A)</strong> and <strong>ACL 2026 (CCF A)</strong>. 
    I have also participated in research on multimodal video spatial understanding 
    benchmarks and efficient time-series forecasting.
  </p>

  <p>
    I served as a <strong>Program Committee Reviewer for ACM ICMR 2026</strong>.
  </p>
  
</div>

# 🔥 News

- *2026.05*: &nbsp;🎉 Our work received highly positive feedback during the **ACL 2026 Argument Mining (ArgMining)** review process and is currently under submission to **EMNLP 2026**.
- *2026.04*: &nbsp;🎉 Our paper **Self-Awareness before Action: Mitigating Logical Inertia via Proactive Cognitive Awareness** was accepted to **ACL 2026**.
- *2026.04*: &nbsp;🎉 Our paper **WPGRec: Wavelet Packet Guided Graph Enhanced Sequential Recommendation** was accepted to **SIGIR 2026**.
- *2026.04*: &nbsp;📌 Our benchmark work **PinpointQA** was released on arXiv, focusing on small object-centric spatial understanding in indoor videos. Within the first month after release, it received over 4,000 downloads on Hugging Face.

# 📝 Publications

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/wpgrec.png' alt="WPGRec" width="100%">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">

[WPGRec: Wavelet Packet Guided Graph Enhanced Sequential Recommendation](https://arxiv.org/abs/2604.21305)

**Peilin Liu**, Zhiquan Ji, Gang Yan

<span style="font-weight:800;">SIGIR 2026.</span> WPGRec is a wavelet packet guided graph-enhanced framework for sequential recommendation, aligning multi-resolution temporal modeling with subband-wise graph propagation and adaptive gated fusion.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/saba.png' alt="SABA" style="width:100%; height:210px; object-fit:cover; object-position:center;">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">

[Self-Awareness before Action: Mitigating Logical Inertia via Proactive Cognitive Awareness](https://arxiv.org/abs/2604.20413)

Fulong Fan<sup>†</sup>, **Peilin Liu<sup>†</sup>**, Liu FengZhe, Shuyan Yang, Gang Yan  
<sup>†</sup>Equal contribution.

<span style="font-weight:800;">ACL 2026.</span> SABA is a self-awareness-before-action reasoning framework that audits missing premises before final decision-making, improving long-context reasoning through information fusion and query-driven structured reasoning.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/pinpointqa.png' alt="PinpointQA" width="100%">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">

[PinpointQA: A Dataset and Benchmark for Small Object-Centric Spatial Understanding in Indoor Videos](https://rainchowz.github.io/PinpointQA/)

Zhiyu Zhou<sup>†</sup>, **Peilin Liu<sup>†</sup>**, Ruoxuan Zhang, Luyang Zhang, Cheng Zhang, Hongxia Xie, Wen-Huang Cheng  
<sup>†</sup>Equal contribution.

<span style="font-weight:800;">arXiv 2026.</span> PinpointQA is a dataset and benchmark for small object-centric spatial understanding in indoor videos. It evaluates whether multimodal models can verify target presence, identify the nearest reference object, generate fine-grained spatial descriptions, and produce structured spatial predictions, covering 1,024 scenes and 10,094 QA pairs.

  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div style="height:120px; overflow:hidden; display:flex; align-items:center;">
      <img src='images/awsarima.png' alt="AW-SARIMA" style="width:100%; transform:scale(1.18);">
    </div>
  </div>

  <div class='paper-box-text' markdown="1">

[AW-SARIMA: Efficient Hybrid Framework for Nonstationary Time Series Forecasting via DWT and Adaptive Thresholding](https://link.springer.com/chapter/10.1007/978-981-96-9875-2_4)

**Peilin Liu**, Zhiyu Zhou, Fangming Gu, Luyang Zhang, Yixing Song, Sheng Lu

<span style="font-weight:800;">ICIC 2025 Oral.</span> AW-SARIMA is a lightweight hybrid framework for nonstationary short-term time series forecasting. It combines DWT-based signal decomposition, adaptive threshold denoising, and SARIMA modeling to improve forecasting accuracy and robustness under noisy and data-limited scenarios.

  </div>
</div>

# 📖 Education

- *2023.09 - Present*, **B.Eng. in Software Engineering**, Excellent Engineer Program, College of Software, Jilin University.

# 🎖 Honors and Awards

- **National Scholarship**, Top 1%.
- **Outstanding Student of Jilin University**, Top 3%.
- **First-Class Scholarship of Jilin University**.
- **Outstanding Student of the College of Software, Jilin University**.
- **Academic and Technological Innovation Award**.

# 🏆 Competitions

- *2025*, National First Prize, National 3D Digital Innovation Design Competition.
- *2025*, National Second Prize, iCAN College Student Innovation and Entrepreneurship Competition, AI Challenge.
- *2024*, Honorable Mention, Mathematical Contest in Modeling (MCM).
- *2024*, Provincial First Prize, The 16th Chinese Mathematics Competitions, Non-Mathematics Group A.
- *2023*, Provincial First Prize, Contemporary Undergraduate Mathematical Contest in Modeling, Jilin Province.

# 💻 Works in Progress

- **KDD 2026 submission**, under review.
- **ECCV 2026 submission**, under review.
- **CIKM 2026 submission**, in preparation.
- **EMNLP 2026 submission**, in preparation.