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

<style>
/* 响应式设计 */
@media (max-width: 768px) {
  .responsive-flex {
    flex-direction: column !important;
  }
  .responsive-flex > div:first-child {
    flex: 1 1 100% !important;
    max-width: 100% !important;
  }
  .stats-grid {
    grid-template-columns: repeat(2, 1fr) !important;
  }
}

/* 悬停效果 */
.hover-card {
  transition: all 0.3s ease;
}
.hover-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 4px 12px rgba(0,0,0,0.15) !important;
}

/* Badge 统一样式 */
.custom-badge {
  background-color: #ff6b6b;
  color: white;
  padding: 4px 8px;
  border-radius: 4px;
  display: inline-block;
  margin-bottom: 10px;
  font-size: 12px;
  font-weight: bold;
}
.badge-2025 { background-color: #ff6b6b; }
.badge-2024 { background-color: #4ecdc4; }
.badge-2022 { background-color: #95e1d3; }
.badge-work { background-color: #6c5ce7; }
.badge-hobby { background-color: #fdcb6e; }

/* 引用数高亮 */
.citation-high {
  color: #e74c3c;
  font-weight: bold;
}

/* 数据看板样式 */
.stats-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
  margin: 30px 0;
}

.stat-card {
  color: white;
  padding: 25px;
  border-radius: 12px;
  text-align: center;
  box-shadow: 0 4px 15px rgba(0,0,0,0.2);
  transition: transform 0.3s ease;
}

.stat-card:hover {
  transform: translateY(-8px);
}

.stat-number {
  font-size: 36px;
  font-weight: bold;
  margin-bottom: 10px;
}

.stat-label {
  font-size: 14px;
  opacity: 0.9;
}

/* 新闻条目样式 */
.news-item {
  padding: 10px 0;
  border-bottom: 1px dashed #e0e0e0;
}

.news-item:last-child {
  border-bottom: none;
}

/* 论文高亮卡片 */
.highlight-paper {
  padding: 15px;
  border-left: 5px solid;
  margin-bottom: 15px;
  border-radius: 5px;
}

.paper-nature {
  background: #fff3cd;
  border-color: #ffc107;
}

.paper-q1 {
  background: #d1ecf1;
  border-color: #0c5460;
}

/* 返回顶部按钮 */
#backToTop {
  position: fixed;
  bottom: 40px;
  right: 40px;
  background-color: #3498db;
  color: white;
  border: none;
  border-radius: 50%;
  width: 50px;
  height: 50px;
  font-size: 20px;
  cursor: pointer;
  display: none;
  z-index: 1000;
  box-shadow: 0 2px 10px rgba(0,0,0,0.2);
  transition: all 0.3s ease;
}

#backToTop:hover {
  background-color: #2980b9;
  transform: translateY(-5px);
}

/* 图片/视频样式 */
.media-container {
  border-radius: 8px;
  box-shadow: 0 2px 8px rgba(0,0,0,0.1);
  overflow: hidden;
}
</style>




<div style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; padding: 15px; border-radius: 8px; text-align: center; margin-bottom: 30px;">
  <a href="#highlights" style="color: white; margin: 0 15px; text-decoration: none;">🌟 Highlights</a> |
  <a href="#news" style="color: white; margin: 0 15px; text-decoration: none;">🔥 News</a> |
  <a href="#-xl" style="color: white; margin: 0 15px; text-decoration: none;">🎓 Education</a> |
  <a href="#-lwzl" style="color: white; margin: 0 15px; text-decoration: none;">📝 Publications</a> |
  <a href="#-ryjx" style="color: white; margin: 0 15px; text-decoration: none;">🏅 Challenges</a> |
  <a href="#-hobbies" style="color: white; margin: 0 15px; text-decoration: none;">✨ Hobbies</a>
</div>




<span class='anchor' id='about-me'></span>

I am a PhD student at Istanbul Technical University, Computer Engineering, where I have studied since 2021. I work as a researcher in the 2232 International Fellowship for Outstanding Researchers Program of TUBITAK (Project No: 118C353) and the ITU BAP research funds (Project ID: 47296). My research focuses on MRI reconstruction using deep learning and reinforcement learning methods. My professor is [Ilkay Oksuz](https://drive.google.com/file/d/1HO0SB8UNbSZ3Pqn97XBQZtE-UhqxmA1x/view).

From 2018 to 2020, I was an exchange student at the Lab of Interactive Media Computing at Fudan University. During this time, I was working on projects related to autonomous driving, which involved object detection, pedestrian recognition, Instance segmentation, path planning, etc., working under the guidance of Professor Cheng Jin.

From 2017 to 2020, I pursued my Master's studies at the SICT(Shanghai Institute of Computing Technology), with a research direction in computer vision. My professor is Xinli Min.

From 2017 to 2020, I interned at Shanghai Shen Teng Technology Co., Ltd. . My work there involved contributing to smart city-related projects.

In 2016, I earned my Bachelor's degree in Computer Science and Technology.

Gap year: 2016~2017, Backpacker, traveling alone.

Gap year: 2020~2021, Epidemic Volunteer

**🔬 Research Interests:**  
Medical Image Analysis · MRI Reconstruction · Reinforcement Learning · Instance Segmentation · Object Detection · Computer Vision

<span class='anchor' id='highlights'></span>

# 🌟 Research Highlights

<div class="stats-grid">

<div class="stat-card" style="background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);">
  <div class="stat-number">10+</div>
  <div class="stat-label">Publications</div>
</div>

<div class="stat-card" style="background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);">
  <div class="stat-number">14+</div>
  <div class="stat-label">Total Citations</div>
</div>

<div class="stat-card" style="background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);">
  <div class="stat-number">3</div>
  <div class="stat-label">MICCAI Awards</div>
</div>

<div class="stat-card" style="background: linear-gradient(135deg, #43e97b 0%, #38f9d7 100%);">
  <div class="stat-number">4</div>
  <div class="stat-label">Conference Talks</div>
</div>

</div>

<span class='anchor' id='news'></span>

# 🔥 News

<div style="background: #f8f9fa; padding: 20px; border-radius: 8px; margin: 20px 0;">

<div class="news-item">
  <strong>[2026.02]</strong> 🎤 Paper accepted for in-person presentation at <strong>SCMR 2026</strong>, Brazil
</div>

<div class="news-item">
  <strong>[2025.09]</strong> 🎉 Two papers accepted at <strong>MICCAI 2025</strong> with oral presentations!
</div>

<div class="news-item">
  <strong>[2025.03]</strong> 🥉 Won <strong>3rd place</strong> in CMRxRecon Challenge Task 2
</div>

<div class="news-item">
  <strong>[2025.03]</strong> 🥇 Won <strong>5th place</strong> in CMRxRecon Challenge Task 1
</div>

<div class="news-item">
  <strong>[2025.01]</strong> 📄 Paper accepted in <strong>Neurocomputing</strong> (Q1, IF: 6.5)
</div>

<div class="news-item">
  <strong>[2024.10]</strong> 🎤 Oral presentation at <strong>MICCAI 2024</strong>
</div>

</div>

<span class='anchor' id='-xl'></span>

# 🎓 Education

- *2021.03 - now*, <img src='images/itu-logo.png' width='20' height='20' /> <a href="https://www.itu.edu.tr/en">Istanbul Technical University</a>, Computer Engineering, PhD Candidate

- *2018.04 - 2020.03*, <img src='images/fudan-logo.png' width='20' height='20' /> <a href="https://www.fudan.edu.cn/en/">Fudan University</a>, Lab of Interactive Media Computing, Exchange learning

- *2017.09 - 2020.03*, <img src='images/SICT-logo.png' width='20' height='20' /> <a href="https://www.sh-sict.com/">SICT (Shanghai Institute of Computing Technology)</a>, Engineering Computer Software and Theory, Master's degree

- *2012.09 - 2016.07*, <img src='images/Liaocheng-logo.png' width='20' height='20' /> <a href="https://www.lcu.edu.cn/">Liaocheng University</a>, Computer Science and Technology, Bachelor's degree

<span class='anchor' id='-gzsx'></span>

# 💻 Work Experience

<div style="display: flex; flex-direction: column; gap: 30px;">

<!-- Work Experience 1 -->
<div class="responsive-flex hover-card" style="display: flex; gap: 20px; align-items: flex-start; padding-bottom: 30px;">

<div style="flex: 0 0 250px;">
  <div class="custom-badge badge-work">Life during Master's studies</div>
  <video width="100%" controls class="media-container">
    <source src="video/work-life1.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<div style="flex: 1;">
  <p style="margin: 0; line-height: 1.6;">
<strong>📅 2017.09 - 2020.03 | Student Intern</strong><br>
<strong>🏢 Shanghai Shen Teng Technology Co., Ltd. - R&D Department</strong><br><br>
    
    Working on smart city related projects in the R&D department. Contributed to intelligent city infrastructure development, focusing on computer vision applications for urban management and monitoring systems.
    <br><br>
    
    <strong>🏆 Algorithm Competition Achievements (During Master's Studies)</strong><br><br>
    
    In my spare time, I actively participated in challenging algorithm competitions:
    <br><br>
    
    <strong>1. Huawei Cloud AI Competition · Garbage Sorting Challenge Cup (2019)</strong><br>
    &nbsp;&nbsp;&nbsp;&nbsp;• Ranked <strong>32nd out of 2,611 teams</strong><br>
    &nbsp;&nbsp;&nbsp;&nbsp;• GitHub: <a href="https://github.com/Ruru-Xu/project4--Garbage-sorting" target="_blank">Garbage Sorting Project</a>
    <br><br>
    
    <strong>2. Tianchi Competition · Tianjin South Digital Manufacturing Algorithm Challenge</strong><br>
    &nbsp;&nbsp;&nbsp;&nbsp;• Ranked <strong>53rd out of 2,157 teams worldwide</strong><br>
    &nbsp;&nbsp;&nbsp;&nbsp;• GitHub: <a href="https://github.com/Ruru-Xu/project5--Monitoring-of-restricted-goods-in-logistics" target="_blank">Monitoring of Restricted Goods in Logistics</a>
    <br><br>
    
    <strong>3. China National Mathematical Contest in Modeling for Graduate Students</strong><br>
    &nbsp;&nbsp;&nbsp;&nbsp;• Awarded <strong>Third-Class Prize</strong><br>
    &nbsp;&nbsp;&nbsp;&nbsp;• Officially recorded on Master's degree transcript
  </p>
</div>

</div>

</div>

<span class='anchor' id='-toefl'></span>

# 📋 TOEFL Score

- *Score: 108 · Jan 2021*, Reading: 28, Listening: 26, Speaking: 24, Writing: 30

<span class='anchor' id='-lwzl'></span>

# 📝 Publications

### Journal Papers
---

<div class='paper-box'>
  <div class='anchor' markdown="1">

- `Xu R`, Oksuz I. “Undersampled K-Space Information Recovery with Long-Range Temporal Memory for Multi-Coil MRI Reconstruction.” [**Top journal: MIA**, IF: 11.8, Under Review]

</div>

<div class='anchor' markdown="1">

- `Xu R`, Oksuz I. "Optimized K-Space Under-sampling for Brain MRI Reconstruction with Reinforcement Learning." **Pattern Recognition Letters** (Q1; IF:3.9) [Under Review, Revise stage]

</div>

<div class='anchor' markdown="1">

- Wang F,..etc... `Xu R, Oksuz I`..etc... . "Towards Universal Learning-based Model for Cardiac Image Reconstruction: Summary of the CMRxRecon2024 Challenge" (**Top Journal: TMI**; IF:9.8) [Under Review, Revise stage]
  [[Online]](https://arxiv.org/abs/2503.03971) | Citations: <span class="citation-high">1</span>

</div>

<div class='anchor' markdown="1">

- `Xu R`, Oksuz I. "A Reinforcement Learning Approach for Optimized MRI Sampling with Region-Specific Fidelity." **Neurocomputing** (2025). (Q1; IF:6.5)
  [[Online]](https://www.sciencedirect.com/science/article/pii/S092523122500788X) [[Code]](https://github.com/Ruru-Xu/KSRO) | Citations: <span class="citation-high">2</span>

</div>

<div class='anchor' markdown="1">

- `Xu R`, Oksuz I. "Segmentation-aware MRI subsampling for efficient cardiac MRI reconstruction with reinforcement learning." **Image and Vision Computing** (2024). (Q1; IF:4.2)
  [[Online]](https://www.sciencedirect.com/science/article/pii/S0262885624003056) | Citations: <span class="citation-high">5</span>

</div>
</div>

### 🎤 Conference Papers

---

<div style="display: flex; flex-direction: column; gap: 30px;">

<!-- MICCAI 2025 Paper 1 -->
<div class="responsive-flex hover-card" style="display: flex; gap: 20px; align-items: flex-start; border-bottom: 1px solid #e0e0e0; padding-bottom: 30px;">
  <div style="flex: 0 0 250px;">
    <div class="custom-badge badge-2025">MICCAI 2025</div>
    <img src='images/miccai2025paper1.png' alt="MICCAI 2025 Paper 1" class="media-container" style="width: 100%;">
  </div>
  <div style="flex: 1;">
    <p style="margin: 0 0 15px 0; line-height: 1.6;">
      - <code>Xu R</code>, Oksuz I. <strong>"Adaptive k-space Radial Sampling for Cardiac MRI with Reinforcement Learning"</strong> (MICCAI 2025 STACOM Workshop)
    </p>
    <p style="margin: 0;">
      <a href="http://arxiv.org/abs/2508.04727">[Online]</a>
      <a href="https://www.youtube.com/watch?v=ui6kDZYIO44&t=101s&ab_channel=RuruXu">[Video]</a>
      <a href="https://github.com/Ruru-Xu/RL-kspace-Radial-Sampling">[Code]</a>
    </p>
  </div>
</div>

<!-- MICCAI 2025 Paper 2 -->
<div class="responsive-flex hover-card" style="display: flex; gap: 20px; align-items: flex-start; border-bottom: 1px solid #e0e0e0; padding-bottom: 30px;">
  <div style="flex: 0 0 250px;">
    <div class="custom-badge badge-2025">MICCAI 2025</div>
    <img src='images/miccai2025paper2.png' alt="MICCAI 2025 Paper 2" class="media-container" style="width: 100%;">
  </div>
  <div style="flex: 1;">
    <p style="margin: 0 0 15px 0; line-height: 1.6;">
      - <code>Xu R</code>, Oksuz I. <strong>"HierAdaptMR: Cross-Center Cardiac MRI Reconstruction with Hierarchical Feature Adapters"</strong> (MICCAI 2025 CMRxRecon Challenge paper)
    </p>
    <p style="margin: 0;">
      <a href="https://arxiv.org/abs/2508.13026">[Online]</a>
      <a href="https://github.com/Ruru-Xu/HierAdaptMR">[Code]</a>
    </p>
  </div>
</div>

<!-- MICCAI 2024 Paper -->
<div class="responsive-flex hover-card" style="display: flex; gap: 20px; align-items: flex-start; border-bottom: 1px solid #e0e0e0; padding-bottom: 30px;">
  <div style="flex: 0 0 250px;">
    <div class="custom-badge badge-2024">MICCAI 2024</div>
    <img src='images/miccai2024paper.png' alt="MICCAI 2024 Paper" class="media-container" style="width: 100%;">
  </div>
  <div style="flex: 1;">
    <p style="margin: 0 0 15px 0; line-height: 1.6;">
      - <code>Xu R</code>, Özer C, Oksuz I. <strong>"HyperCMR: Enhanced Multi-Contrast CMR Reconstruction with Eagle Loss."</strong> (MICCAI 2024 CMRxRecon Challenge paper)
    </p>
    <p style="margin: 0;">
      <a href="https://link.springer.com/chapter/10.1007/978-3-031-87756-8_15">[Online]</a>
      <a href="https://www.youtube.com/watch?v=tBZq-MMEHPw">[Video]</a>
      <a href="https://github.com/Ruru-Xu/HyperCMR">[Code]</a> | Citations: <span class="citation-high">4</span>
    </p>
  </div>
</div>

<!-- MICCAI 2022 Paper -->
<div class="responsive-flex hover-card" style="display: flex; gap: 20px; align-items: flex-start; border-bottom: 1px solid #e0e0e0; padding-bottom: 30px;">
  <div style="flex: 0 0 250px;">
    <div class="custom-badge badge-2022">MICCAI 2022</div>
    <img src='images/miccai2022paper.png' alt="MICCAI 2022 Paper" class="media-container" style="width: 100%;">
  </div>
  <div style="flex: 1;">
    <p style="margin: 0 0 15px 0; line-height: 1.6;">
      - <code>Xu R</code>, Oksuz I. <strong>"Efficient MRI reconstruction with reinforcement learning for automatic acquisition stopping."</strong> (MICCAI 2022, STACOM Workshop)
    </p>
    <p style="margin: 0;">
      <a href="https://link.springer.com/chapter/10.1007/978-3-031-23443-9_31">[Online]</a>
      <a href="https://www.youtube.com/watch?v=f32xa3Vds3o">[Video]</a> | Citations: <span class="citation-high">2</span>
    </p>
  </div>
</div>

<!-- IEEE Big Data 2019 -->
<div class="responsive-flex hover-card" style="display: flex; gap: 20px; align-items: flex-start;">
  <div style="flex: 0 0 250px;">
    <div class="custom-badge" style="background-color: #a29bfe;">IEEE Big Data 2019</div>
    <div style="width: 100%; height: 150px; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); border-radius: 8px; display: flex; align-items: center; justify-content: center; color: white; font-weight: bold; font-size: 18px;">
      IEEE Big Data
    </div>
  </div>
  <div style="flex: 1;">
    <p style="margin: 0 0 15px 0; line-height: 1.6;">
      - <code>Xu R</code>, An J, Su L, and Min X. <strong>"Banknotes serial number coding recognition."</strong> In 2019 IEEE International Conference on Big Data (Big Data), pp. 5101-5107. IEEE, 2019.
    </p>
    <p style="margin: 0;">
      <a href="https://ieeexplore.ieee.org/abstract/document/9006506">[Online]</a> | Citations: <span class="citation-high">2</span>
    </p>
  </div>
</div>

</div>

### 📖 Master's Thesis

---

<div class='paper-box-text' markdown="1">

- Research and Implementation of Intelligent Evaluation Algorithm of Street Cleanliness Based on Vision  
[[Online]](http://www.cnki.net/KCMS/detail/detail.aspx?dbcode=CMFD&dbname=CMFD202101&filename=1021521998.nh&uniplatform=OVERSEA&v=1mKWbzyM1RA2069qUjrH98S7LHHip8KOCXlh8GfkcqZJAEF2V2My6eNROWkmA2id) Chinese Master's Theses Full-text Database · Mar 2, 2020

</div>

<span class='anchor' id='-ryjx'></span>

# 🏅 MICCAI Challenge

> 🎯 **Consistently ranked Top 5** in MICCAI CMRxRecon Challenge (2024-2025), demonstrating expertise in cardiac MRI reconstruction across multiple tasks and evaluation criteria.

<div style="display: flex; flex-direction: column; gap: 30px;">

<!-- CMRxRecon 2025 Challenge - Special Task -->
<div class="responsive-flex hover-card" style="display: flex; gap: 20px; align-items: flex-start; border-bottom: 1px solid #e0e0e0; padding-bottom: 30px;">
  <div style="flex: 0 0 250px;">
    <div class="custom-badge badge-2025">SCMR 2026</div>
    <img src='images/CMRxRecon2025-special.jpg' alt="CMRxRecon 2025 Special Tasks" class="media-container" style="width: 100%;">
  </div>
  <div style="flex: 1;">
    <p style="margin: 0 0 15px 0; line-height: 1.6;">
      <strong><a href="https://cmrxrecon.github.io/2025/Home.html">MICCAI 2025 CMRxRecon Challenge</a></strong><br>
      🥇 <code style="background-color: #ffeaa7; padding: 2px 6px; border-radius: 3px;">Top 5 teams on leaderboard in Two Special Tasks, Final rank will be announced at the SCMR 2026, Brazil. We will have oral presentation</code>
    </p>
  </div>
</div>

<!-- CMRxRecon 2025 Challenge - Task 1 -->
<div class="responsive-flex hover-card" style="display: flex; gap: 20px; align-items: flex-start; border-bottom: 1px solid #e0e0e0; padding-bottom: 30px;">
  <div style="flex: 0 0 250px;">
    <div class="custom-badge badge-2025">MICCAI 2025</div>
    <img src='images/CMRxRecon2025-1.jpg' alt="CMRxRecon 2025 Task 1" class="media-container" style="width: 100%;">
  </div>
  <div style="flex: 1;">
    <p style="margin: 0 0 15px 0; line-height: 1.6;">
      <strong><a href="https://cmrxrecon.github.io/2025/Home.html">MICCAI 2025 CMRxRecon Challenge</a></strong><br>
      🥇 <code style="background-color: #ffeaa7; padding: 2px 6px; border-radius: 3px;">5th Place Award</code> in Regular Task 1: CMR reconstruction model for multi-center evaluation
    </p>
    <p style="margin: 0;">
      <a href="https://www.synapse.org/Synapse:syn59814210/wiki/635078">[Certification]</a>
    </p>
  </div>
</div>

<!-- CMRxRecon 2025 Challenge - Task 2 -->
<div class="responsive-flex hover-card" style="display: flex; gap: 20px; align-items: flex-start; border-bottom: 1px solid #e0e0e0; padding-bottom: 30px;">
  <div style="flex: 0 0 250px;">
    <div class="custom-badge badge-2025">MICCAI 2025</div>
    <img src='images/CMRxRecon2025-2.jpg' alt="CMRxRecon 2025 Task 2" class="media-container" style="width: 100%;">
  </div>
  <div style="flex: 1;">
    <p style="margin: 0 0 15px 0; line-height: 1.6;">
      <strong><a href="https://cmrxrecon.github.io/2025/Home.html">MICCAI 2025 CMRxRecon Challenge</a></strong><br>
      🥉 <code style="background-color: #ffeaa7; padding: 2px 6px; border-radius: 3px;">3rd Place Award</code> in Regular Task 2: CMR reconstruction model for multiple diseases evaluation
    </p>
    <p style="margin: 0;">
      <a href="https://www.synapse.org/Synapse:syn59814210/wiki/635078">[Certification]</a>
    </p>
  </div>
</div>

<!-- CMRxRecon 2024 Challenge -->
<div class="responsive-flex hover-card" style="display: flex; gap: 20px; align-items: flex-start;">
  <div style="flex: 0 0 250px;">
    <div class="custom-badge badge-2024">MICCAI 2024</div>
    <img src='images/CMRxRecon2024-1.jpg' alt="CMRxRecon 2024" class="media-container" style="width: 100%;">
  </div>
  <div style="flex: 1;">
    <p style="margin: 0 0 15px 0; line-height: 1.6;">
      <strong><a href="https://cmrxrecon.github.io/2024/Home.html">MICCAI 2024 CMRxRecon Challenge</a></strong><br>
      🏆 <code style="background-color: #ffeaa7; padding: 2px 6px; border-radius: 3px;">Top 6</code> in Task 1: Multi-contrast CMR reconstruction<br>
      🏆 <code style="background-color: #ffeaa7; padding: 2px 6px; border-radius: 3px;">Top 5</code> in Task 2: Random sampling CMR reconstruction
    </p>
    <p style="margin: 0;">
      <a href="https://www.synapse.org/Synapse:syn54951257/wiki/630047">[Certification]</a>
    </p>
  </div>
</div>

</div>

<span class='anchor' id='-xshy'></span>

# 🏛️ Academic Conference

- *2026.02*, SCMR 2026, Abstract paper accepted for an in-person presentation
- *2025.09*, MICCAI 2025, Oral Presentation
- *2024.10*, MICCAI 2024, Oral Presentation
- *2022.09*, MICCAI 2022, Oral Presentation

<span class='anchor' id='-hobbies'></span>

# ✨ Life Beyond Research

<div style="display: flex; flex-direction: column; gap: 30px;">

<div class="responsive-flex hover-card" style="display: flex; gap: 20px; align-items: flex-start;">

<div style="flex: 0 0 250px;">
  <div class="custom-badge badge-hobby">Life Beyond Research</div>
  <video width="100%" controls class="media-container">
    <source src="video/hobbies1.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>

<div style="flex: 1;">
  <p style="margin: 0; line-height: 1.8;">
    <strong>🎯 Personal Interests & Activities</strong><br><br>  
    🚴‍♀️ <strong>Favorite Sport:</strong> Long-distance cycling (Cycled over 5,000 km across multiple provinces and cities during my three-year Master's studies)<br>
    ✈️ <strong>Favorite Travel Style:</strong> Solo backpacking adventures (Traveled independently across half of China)<br>
    📚 <strong>Favorite Reading:</strong> Ancient Chinese poetry and literature (Served as editor of the school literary society for three years in high school)<br>
    🤝 <strong>Most Memorable Volunteer Experience:</strong> Turkey Earthquake Relief Volunteer
  </p>
</div>

</div>

</div>

<!-- 返回顶部按钮 -->
<button id="backToTop" title="Go to top">↑</button>

<script>
// 返回顶部功能
var backToTopButton = document.getElementById("backToTop");

window.onscroll = function() {
  if (document.body.scrollTop > 300 || document.documentElement.scrollTop > 300) {
    backToTopButton.style.display = "block";
  } else {
    backToTopButton.style.display = "none";
  }
};

backToTopButton.onclick = function() {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
};

// 平滑滚动效果
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
  anchor.addEventListener('click', function (e) {
    e.preventDefault();
    const target = document.querySelector(this.getAttribute('href'));
    if (target) {
      target.scrollIntoView({
        behavior: 'smooth',
        block: 'start'
      });
    }
  });
});
</script>










