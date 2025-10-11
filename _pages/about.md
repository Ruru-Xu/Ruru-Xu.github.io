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

I am a PhD student at Istanbul Technical University, Computer Engineering, where I have studied since 2021. I work as a researcher in the 2232 International Fellowship for Outstanding Researchers Program of TUBITAK (Project No: 118C353) and the ITU BAP research funds (Project ID: 47296). My research focuses on MRI reconstruction using deep learning and reinforcement learning methods. My professor is [Ilkay Oksuz](https://drive.google.com/file/d/1HO0SB8UNbSZ3Pqn97XBQZtE-UhqxmA1x/view).

From 2018 to 2020, I was an exchange student at the Lab of Interactive Media Computing at Fudan University. During this time, I was working on projects related to autonomous driving, which involved object detection, pedestrian recognition, Instance segmentation, path planning, etc., working under the guidance of Professor Cheng Jin.

From 2017 to 2020, I pursued my Master's studies at the SICT(Shanghai Institute of Computing Technology), with a research direction in computer vision. My professor is Xinli Min.

From 2017 to 2020, I interned at Shanghai Shen Teng Technology Co., Ltd. . My work there involved contributing to smart city-related projects.

In 2016, I earned my Bachelor's degree in Computer Science and Technology.

Gap year: 2016~2017, Backpacker, traveling alone.

Gap year: 2020~2021, Epidemic Volunteer

My research areas include:
- Medical Image Analysis
- MRI Reconstruction
- Instance Segmentation
- Object Detection
- Computer Vision


<span class='anchor' id='-xl'></span>

# 🎓 Education

- *2021.03 - now*, <img src='images/itu-logo.png' width='20' height='20' /> <a href="https://www.itu.edu.tr/en">Istanbul Technical University</a>, Computer Engineering, PhD Candidate 

- *2018.04 - 2020.03*, <img src='images/fudan-logo.png' width='20' height='20' /> <a href="https://www.fudan.edu.cn/en/">Fudan University</a>, Lab of Interactive Media Computing, Exchange learning

- *2017.09 - 2020.03*, <img src='images/SICT-logo.png' width='20' height='20' /> <a href="https://www.sh-sict.com/">SICT(Shanghai Institute of Computing Technology)</a>, Engineering Computer Software and Theory, Master's degree

- *2012.09 - 2016.07*, <img src='images/Liaocheng-logo.png' width='20' height='20' /> <a href="https://www.lcu.edu.cn/">Liaocheng University</a>, Computer Science and Technology, Bachelor's degree

<span class='anchor' id='-gzsx'></span>

# 💻 Work Experience
<div style="flex: 1; min-width: 300px; max-width: 32%;">
  <div class='paper-box-image'>
    <div>
      <div class="badge">Life during Master's studies</div>
      <video width="100%" controls>
        <source src="video/work-life1.mp4" type="video/mp4">
      </video>
    </div>
  </div>
- 2017.09 - 2020.03, Shanghai Shen Teng Technology Co., Ltd. Student Intern, Working on smart city related projects in the R&D department

</div>


<span class='anchor' id='-gzsx'></span>

# 📋 TOEFL score 
- *Score: 108 · Jan 2021*, Reading:28, Listening:26, Speaking:24, Writing:30
 
<span class='anchor' id='-lwzl'></span>

# 📝 Publications

### Journal Papers
---
<div class='paper-box'>

<div class='anchor' markdown="1">
-	`Xu R`, Oksuz I. "Optimized K-Space Under-sampling for Brain MRI Reconstruction with Reinforcement Learning." Pattern Recognition Letters (Q1; IF:3.9) [Under Review, Revise stage]
</div>

<div class='anchor' markdown="1">
-	Wang F,..etc... `Xu R, Oksuz I`..etc... . "Towards Universal Learning-based Model for Cardiac Image Reconstruction: Summary of the CMRxRecon2024 Challenge" (Top Journal: Nature Machine Intelligence; IF:23.9) Under Review
  [[online]](https://arxiv.org/abs/2503.03971) | Citations: 1
</div>

<div class='anchor' markdown="1">
-	`Xu R`, Oksuz I. "A Reinforcement Learning Approach for Optimized MRI Sampling with Region-Specific Fidelity.” Neurocomputing (2025). (Q1; IF:5.5) 
  [[Online]](https://www.sciencedirect.com/science/article/pii/S092523122500788X) [[Code]](https://github.com/Ruru-Xu/KSRO) | Citations: 1 
</div>

<div class='anchor' markdown="1">
-	`Xu R`, Oksuz I. "Segmentation-aware MRI subsampling for efficient cardiac MRI reconstruction with reinforcement learning." Image and Vision Computing 150 (2024): 105200. (Q1; IF:4.2) 
  [[online]](https://www.sciencedirect.com/science/article/pii/S0262885624003056) | Citations: 5
</div>



</div>



### Conference Papers
---

<div style="display: flex; flex-direction: column; gap: 30px;">
  
  <!-- MICCAI 2025 Paper 1 -->
  <div style="display: flex; gap: 20px; align-items: flex-start; border-bottom: 1px solid #e0e0e0; padding-bottom: 30px;">
    <div style="flex: 0 0 250px;">
      <div class="badge" style="background-color: #ff6b6b; color: white; padding: 4px 8px; border-radius: 4px; display: inline-block; margin-bottom: 10px; font-size: 12px;">MICCAI 2025</div>
      <img src='images/miccai2025paper1.png' alt="MICCAI 2025 Paper 1" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
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
  <div style="display: flex; gap: 20px; align-items: flex-start; border-bottom: 1px solid #e0e0e0; padding-bottom: 30px;">
    <div style="flex: 0 0 250px;">
      <div class="badge" style="background-color: #ff6b6b; color: white; padding: 4px 8px; border-radius: 4px; display: inline-block; margin-bottom: 10px; font-size: 12px;">MICCAI 2025</div>
      <img src='images/miccai2025paper2.png' alt="MICCAI 2025 Paper 2" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
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
  <div style="display: flex; gap: 20px; align-items: flex-start; border-bottom: 1px solid #e0e0e0; padding-bottom: 30px;">
    <div style="flex: 0 0 250px;">
      <div class="badge" style="background-color: #4ecdc4; color: white; padding: 4px 8px; border-radius: 4px; display: inline-block; margin-bottom: 10px; font-size: 12px;">MICCAI 2024</div>
      <img src='images/miccai2024paper.png' alt="MICCAI 2024 Paper" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
    </div>
    
    <div style="flex: 1;">
      <p style="margin: 0 0 15px 0; line-height: 1.6;">
        - <code>Xu R</code>, Özer C, Oksuz I. <strong>"HyperCMR: Enhanced Multi-Contrast CMR Reconstruction with Eagle Loss."</strong> (MICCAI 2024 CMRxRecon Challenge paper)
      </p>
      <p style="margin: 0;">
        <a href="https://link.springer.com/chapter/10.1007/978-3-031-87756-8_15">[Online]</a> 
        <a href="https://www.youtube.com/watch?v=tBZq-MMEHPw">[Video]</a> 
        <a href="https://github.com/Ruru-Xu/HyperCMR">[Code]</a> | <em>Citations: 4</em>
      </p>
    </div>
  </div>
  
  
  <!-- MICCAI 2022 Paper -->
  <div style="display: flex; gap: 20px; align-items: flex-start;">
    <div style="flex: 0 0 250px;">
      <div class="badge" style="background-color: #95e1d3; color: white; padding: 4px 8px; border-radius: 4px; display: inline-block; margin-bottom: 10px; font-size: 12px;">MICCAI 2022</div>
      <img src='images/miccai2022paper.png' alt="MICCAI 2022 Paper" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
    </div>
    
    <div style="flex: 1;">
      <p style="margin: 0 0 15px 0; line-height: 1.6;">
        - <code>Xu R</code>, Oksuz I. <strong>"Efficient MRI reconstruction with reinforcement learning for automatic acquisition stopping."</strong> (MICCAI 2022, STACOM Workshop)
      </p>
      <p style="margin: 0;">
        <a href="https://link.springer.com/chapter/10.1007/978-3-031-23443-9_31">[Online]</a> 
        <a href="https://www.youtube.com/watch?v=f32xa3Vds3o">[Video]</a> | <em>Citations: 2</em>
      </p>
    </div>
  </div>
  
</div>



<div class='paper-box'>
<div class='anchor' markdown="1">
-	`Xu R`, An J, Su L, and Min X. "Banknotes serial number coding recognition." In 2019 IEEE International Conference on Big Data (Big Data), pp. 5101-5107. IEEE, 2019.
  [[Online]](https://ieeexplore.ieee.org/abstract/document/9006506) | Citations: 2
</div>
</div>


### Master's Thesis
---
<div class='paper-box-text' markdown="1">
-	Research and Implementation of Intelligent Evaluation Algorithm of Street Cleanliness Based on Vision
  [[Online]](http://www.cnki.net/KCMS/detail/detail.aspx?dbcode=CMFD&dbname=CMFD202101&filename=1021521998.nh&uniplatform=OVERSEA&v=1mKWbzyM1RA2069qUjrH98S7LHHip8KOCXlh8GfkcqZJAEF2V2My6eNROWkmA2id) Chinese Master's Theses Full-text Database · Mar 2, 2020
</div>



<span class='anchor' id='-ryjx'></span>

# 🏅 MICCAI Challenge

<div style="display: flex; flex-direction: column; gap: 30px;">
  
  <!-- CMRxRecon 2025 Challenge - Task 1 -->
  <div style="display: flex; gap: 20px; align-items: flex-start; border-bottom: 1px solid #e0e0e0; padding-bottom: 30px;">
    <div style="flex: 0 0 250px;">
      <img src='images/CMRxRecon2025-1.jpg' alt="CMRxRecon 2025 Task 1" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
    </div>
    
    <div style="flex: 1;">
      <p style="margin: 0 0 15px 0; line-height: 1.6;">
        <strong><a href="https://cmrxrecon.github.io/2025/Home.html">MICCAI 2025 CMRxRecon Challenge</a></strong><br>
        <code>5th Place Award</code> in Regular Task 1: CMR reconstruction model for multi-center evaluation
      </p>
      <p style="margin: 0;">
        <a href="https://www.synapse.org/Synapse:syn59814210/wiki/635078">[Certification]</a>
      </p>
    </div>
  </div>
  
  
  <!-- CMRxRecon 2025 Challenge - Task 2 -->
  <div style="display: flex; gap: 20px; align-items: flex-start; border-bottom: 1px solid #e0e0e0; padding-bottom: 30px;">
    <div style="flex: 0 0 250px;">
      <img src='images/CMRxRecon2025-2.jpg' alt="CMRxRecon 2025 Task 2" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
    </div>
    
    <div style="flex: 1;">
      <p style="margin: 0 0 15px 0; line-height: 1.6;">
        <strong><a href="https://cmrxrecon.github.io/2025/Home.html">MICCAI 2025 CMRxRecon Challenge</a></strong><br>
        <code>3rd Place Award</code> in Regular Task 2: CMR reconstruction model for multiple diseases evaluation
      </p>
      <p style="margin: 0;">
        <a href="https://www.synapse.org/Synapse:syn59814210/wiki/635078">[Certification]</a>
      </p>
    </div>
  </div>
  
  
  <!-- CMRxRecon 2024 Challenge -->
  <div style="display: flex; gap: 20px; align-items: flex-start;">
    <div style="flex: 0 0 250px;">
      <img src='images/CMRxRecon2024-1.jpg' alt="CMRxRecon 2024" style="width: 100%; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.1);">
    </div>
    
    <div style="flex: 1;">
      <p style="margin: 0 0 15px 0; line-height: 1.6;">
        <strong><a href="https://cmrxrecon.github.io/2024/Home.html">MICCAI 2024 CMRxRecon Challenge</a></strong><br>
        🏆 <code>Top 6</code> in Task 1: Multi-contrast CMR reconstruction<br>
        🏆 <code>Top 5</code> in Task 2: Random sampling CMR reconstruction
      </p>
      <p style="margin: 0;">
        <a href="https://www.synapse.org/Synapse:syn54951257/wiki/630047">[Certification]</a>
      </p>
    </div>
  </div>
  
</div>



<span class='anchor' id='-xshy'></span>

# 🏛️ Academic Conference
- *2025.09*, MICCAI 2025, Oral Presentation
- *2024.10*, MICCAI 2024, Oral Presentation
- *2022.09*, MICCAI 2022, Online Presentation




<span class='anchor' id='-gzsx'></span>

# ✨ Hobbies
<div style="flex: 1; min-width: 300px; max-width: 32%;">
  <div class='paper-box-image'>
    <div>
      <video width="100%" controls>
        <source src="video/hobbies1.mp4" type="video/mp4">
      </video>
    </div>
  </div>

</div>













































