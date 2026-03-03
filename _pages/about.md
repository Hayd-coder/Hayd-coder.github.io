---
permalink: /
title: "Home"
excerpt: "About Sun Changhao"
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

# 👤 About Me

{: style="margin-top: 0.8em; margin-bottom: 10px;"}

<div class="section-divider"></div>

<div class="highlight-box" markdown="1">
I am a second-year undergraduate at **Xidian University**, majoring in **Network Engineering** in the School of Cyberspace Security and Information Technology. I rank <span style="color:red">**1st/60**</span> in my major with an average GPA of <span style="color:red">**92.4**</span> across core courses. My academic achievements include CET-4 with a score of 613 and CET-6 with a score of 532.

<div class="header-tags">
  <strong>Research Interests:</strong>
  <span class="tag">Trustworthy Multi-modal Deep Learning</span>
  <span class="tag tag--green">Multi-view Learning</span>
  <span class="tag tag--purple">Uncertainty Quantification</span>
  <span class="tag tag--orange">Data Mining</span>
</div>
<span class='anchor' id='educations'></span>

# 📖 Educations

{: style="margin-top: 0.8em; margin-bottom: 10px;"}

<div class="section-divider"></div>

<div class="edu-card">
<img src="/images/xidian.png" alt="Xidian University" class="edu-logo">
<div class="edu-content" markdown="1">
🎓 **[Xidian University](https://www.xidian.edu.cn/)** · Xi'an, China
<br> *B.Eng. in Network Engineering* &emsp; *Sep. 2023 - Jun. 2027 (expected)*
<br> Top-ranked student with GPA of **92.4/100** and ranking **1st/60** in my major. Core courses include: Computer Organization and Principles (97), Computer Networks (94), Database Systems (97), Operating Systems (94), Advanced Mathematics (97, 92).
</div>
</div>

<div class="edu-card">
<img src="/images/benxigaozhong.jpg" alt="Benxi Senior High School" class="edu-logo">
<div class="edu-content" markdown="1">
🏫 **Benxi Senior High School** · Benxi, Liaoning, China
<br> *2021 - 2023*
<br> Excellent academic performance with strong focus on STEM disciplines.
</div>
</div>

<!--
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

<span class='anchor' id='publications'></span>

# 📝 Research

{: style="margin-top: 0.8em; margin-bottom: 10px;"}

<div class="section-divider"></div>

<div class="pub-card pub-card--submitted" markdown="1">
[**Adaptive Multi-view Sparsity Learning for Dimensionally Unbalanced Data**](https://arxiv.org/abs/)
<br> **S. Sun** (First Author)
<br> <span style="color:#d35400; font-weight:bold;">Submitted to IEEE Transactions on Image Processing (TIP)</span>
<br> *Proposed a novel deep learning framework combining adaptive structural pruning with sparse alignment for unbalanced multi-view learning. Achieved 99.5% classification accuracy on MSRCV1 dataset and improved clustering accuracy by 12% on CUB dataset while reducing FLOPS to 45% of SOTA.*
<br> **Key Contributions:** 
<br> 1. Multi-view Sparse Normalization Layer with $L_1$ penalty for cross-view feature fusion
<br> 2. Parameter-free Neuron Analysis Pruning mechanism based on eigenvalue distribution
<br> 3. Validation on toy example and 7 real-world datasets including downstream semantic segmentation tasks
</div>

<div class="pub-card pub-card--submitted" markdown="1">
[**Trustworthy Stock Price Prediction via Deep Evidential Regression**](https://github.com/Hayd-coder/DESR-Stock-Prediction)
<br> **S. Sun** (First Author)
<br> <span style="color:#d35400; font-weight:bold;">Framework for Quantifying Prediction Confidence and Risk</span>
<br> *Developed a framework for trustworthy stock price prediction by introducing evidential regression to explicitly quantify data and model uncertainty. Improved information coefficient Information Ratio (ICIR) by 48% over baseline methods.*
<br> **Key Contributions:**
<br> 1. Novel application of evidential regression for sequential prediction tasks
<br> 2. Dynamic evidence fusion strategy based on Normal-Inverse-Gamma (NIG) distribution
<br> 3. Plug-and-play uncertainty module for improving baseline model stability
</div>

<span class='anchor' id='projects'></span>

# 🚀 Featured Projects

{: style="margin-top: 0.8em; margin-bottom: 10px;"}

<div class="section-divider"></div>

<div class="pub-card pub-card--submitted" markdown="1">
[**AI-Powered Trustworthy Stock Price Prediction Platform**](https://github.com/Hayd-coder/DESR-Stock-Prediction)
<br> **Project Lead** &emsp; *Mar. 2025 - Jun. 2025*
<br> <span style="color:#d35400; font-weight:bold;">Won Special Prize in "Spark Cup" University Innovation Competition</span>
<br> *Deployed trustworthy stock price prediction model as a web application with real-time A-stock prediction capability.*
<br> **Key Features:**
<br> 1. Integration with Tonghua Securities API for real-time market data and live prediction
<br> 2. Confidence interval estimation for investment decision support
<br> 3. Integration with Gemini LLM for intelligent interpretation of quantitative predictions and personalized investment advice
<br> <a href="https://github.com/Hayd-coder/DESR-Stock-Prediction" class="btn--research btn--code">💻 Code</a> <a href="https://github.com/Hayd-coder/DESR-Stock-Prediction" class="btn--research btn--project">🌐 Project</a>
</div>

<span class='anchor' id='internships'></span>

# 💻 Experience

{: style="margin-top: 0.8em; margin-bottom: 10px;"}

<div class="section-divider"></div>

<div class="intern-card">
<img src="/images/xidian.png" alt="Xidian University" class="intern-logo">
<div class="intern-content" markdown="1">
🔬 **Xidian University, School of Cyberspace Security and Information Technology**
<br> *Undergraduate Research Student* &emsp; Sep. 2024 - Present
<br> Conducting research on multi-view learning and adaptive sparsity learning. Currently developing novel approaches for handling imbalanced multi-dimensional data in machine learning applications.
</div>
</div>

<span class='anchor' id='honors-and-awards'></span>

# 🥇 Awards & Honors

{: style="margin-top: 0.8em; margin-bottom: 10px;"}

<div class="section-divider"></div>

<div class="award-item" markdown="1">
🏆 *2025.12*: **National Scholarship** (2024-2025 Academic Year)
</div>
<div class="award-item" markdown="1">
🏅 *2025.12*: **Excellent Student Standard Bearer** (School-level Award)
</div>
<div class="award-item" markdown="1">
🥇 *2024.12*: **Second Prize**, National Undergraduate Mathematics Competition (Shaanxi Province)
</div>
<div class="award-item" markdown="1">
🥇 *2023.06*: **Second Prize**, National College English Competition (Shaanxi Province)
</div>
<div class="award-item" markdown="1">
🎖️ *2025.07*: **Provincial-level Innovation and Entrepreneurship Project** (Successfully Completed)
</div>
<div class="award-item" markdown="1">
⭐ *2025.06*: **Special Prize**, "Spark Cup" University Innovation Competition (Stock Prediction Platform Project)
</div>

<span class='anchor' id='activities'></span>

# 🎨 Hobbies

{: style="margin-top: 0.8em; margin-bottom: 10px;"}

<div class="section-divider"></div>

<div class="intern-card" markdown="1">
🏋️ **Fitness Enthusiast** - Dedicated to maintaining a healthy lifestyle through regular gym workouts
<br> 🏊 **Swimming** - Passionate about swimming as both a sport and recreational activity
<br> � **Play Guitar** - Passionate guitarist who enjoys playing various music genres and constantly improving musical skills
</div>

<span class='anchor' id='activities'></span>

# 🎭 Activities

{: style="margin-top: 0.8em; margin-bottom: 10px;"}

<div class="section-divider"></div>

<div class="intern-card" markdown="1">
🎤 **Vice Captain, Xidian University Debate Society**
<br> Leading debate team and participating in multiple competitions. Awarded **"Best Debater"** title multiple times for outstanding performance.
</div>

<div style="text-align: right; color: #999; font-size: 0.85em; margin-top: 10px;">
  <em>This homepage was last updated on March 3, 2026.</em>
</div>

<br>
<br>
<br>
<br>
<br>
