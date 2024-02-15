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
Hello, my name is Yinhua Piao, and I am a Ph.D. student in computer science at Seoul National University (SNU). I received my Bachelor’s degree in Computer Science from Jilin University in 2018 and my Master’s degree in Computer Science from the [Bio & Health Informatics (BHI) lab](https://bhi-kimlab.github.io/) at SNU in 2020. Currently, I am pursuing a Doctoral degree and working with [Professor Sun Kim](https://bhi-kimlab.github.io/members/sun_kim.html) in the BHI Lab at SNU. 

My research interests lie in developing computational methods to solve complex problems in healthcare and bioinformatics. Specifically, I focus on applying machine learning and data mining techniques to analyze and interpret large-scale healthcare data, identify biomarkers, and improve personalized clinical treatments.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=mQEG6VcAAAAJ'>google scholar citations <strong><span id='total_cit'>??+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=mQEG6VcAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2024.02*: &nbsp;🎉🎉 I won the 30th Samsung HumanTech Paper Award. 
- *2023.08*: &nbsp;🎉🎉 co-work is accepted by CSBJ 2023.
- *2023.05*: &nbsp;🎉🎉 co-work is accepted by ACL 2023.

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

<ul>
  <li>
    <code class="language-plaintext highlighter-rouge">CSBJ 2023</code>
    <!-- <span style="color:red">(Long paper)</span> -->
    <a href="https://doi.org/10.1016/j.csbj.2023.08.016">Exploring Chemical Space for Lead Identification by Propagating on Chemical Similarity Network</a>
    <br> Jungseob Yi, Sangseon Lee, Sangsoo Lim, Changyun Cho, <strong>Yinhua Piao</strong>, Marie Yeo, Dongkyu Kim, Sun Kim, Sunho Lee | <a href="https://github.com/J-Sub/ChemNP"><strong>Project</strong></a>
  </li>

  <li>
    <code class="language-plaintext highlighter-rouge">ACL 2023</code>
    <!-- <span style="color:red">(Long paper)</span> -->
    <a href="https://arxiv.org/abs/2305.09756">Clinical Note Owns its Hierarchy: Multi-Level Hypergraph Neural Networks for Patient-Level Representation Learning</a>
    <br> Nayeon Kim*, <strong>Yinhua Piao*</strong>, Sun Kim | <a href="https://github.com/ny1031/TM-HGNN"><strong>Project</strong></a>
  </li>

  <li>
    <code class="language-plaintext highlighter-rouge">IJMS 2022</code>
    <!-- <span style="color:red">(Long paper)</span> -->
    <a href="https://www.mdpi.com/1422-0067/23/22/13919">DRPreter: Interpretable Anticancer Drug Response Prediction Using Knowledge-Guided Graph Neural Networks and Transformer</a>
    , Jihye Shin*, <strong>Yinhua Piao*</strong>, Dongmin Bang, Sun Kim, Kyuri Jo | <a href="https://github.com/babaling/DRPreter"><strong>Project</strong></a>
  </li>

  <li>
    <code class="language-plaintext highlighter-rouge">NeurIPS 2022</code>
    <!-- <span style="color:red">(GLFrontiers Workshop)</span> -->
    <a href="https://openreview.net/forum?id=z3SHKtoG5XZ">SPGP: Structure Prototype Guided Graph Pooling</a>
    , Sangseon Lee, Dohoon Lee, <strong>Yinhua Piao</strong>, Sun Kim
  </li>

  <li>
    <code class="language-plaintext highlighter-rouge">CSBJ 2022</code>
    <!-- <span style="color:red">(Survey paper)</span> -->
    <a href="https://www.sciencedirect.com/science/article/pii/S2001037022003300">On modeling and utilizing chemical compound information with deep learning technologies: A task-oriented approach</a>
    , Sangsoo Lim, Sangseon Lee, <strong>Yinhua Piao</strong>, MinGyu Choi, Dongmin Bang, Jeonghyeon Gu, Sun Kim
  </li>

  <li>
    <code class="language-plaintext highlighter-rouge">AAAI 2022</code>
    <!-- <span style="color:red">(Survey paper)</span> -->
    <a href="https://ojs.aaai.org/index.php/AAAI/article/view/21366">Sparse Structure learning via Graph Neural Networks for Inductive Document Classification</a>
    , <strong>Yinhua Piao</strong>, Sangseon Lee, Dohoon Lee, Sun Kim| <a href="https://github.com/qkrdmsghk/TextSSL"><strong>Project</strong></a>
  </li>

  <li>
    <code class="language-plaintext highlighter-rouge">Mathematics 2022</code>
    <!-- <span style="color:red">(Survey paper)</span> -->
    <a href="https://www.mdpi.com/2227-7390/9/7/772">Graph convolutional network for drug response prediction using gene expression data</a>
    , Seonghun Kim, Seockhun Bae, <strong>Yinhua Piao</strong>, Kyuri Jo | <a href="https://github.com/BML-cbnu/DrugGCN"><strong>Project</strong></a>
  </li>


</ul>

# 🎖 Honors and Awards
- *2024.02* Samsung HumanTech Paper Award. [\[link\]](https://cse.snu.ac.kr/node/54543)
- *2022.04* AIIS Retreat Best Poster Award. [\[link\]](https://aiis.snu.ac.kr/bbs/board.php?bo_table=sub5_1&wr_id=312)
- *2022.09* Samsung HumanTech Paper Award (Bronze Prize) [\[link\]](https://cse.snu.ac.kr/node/54543)
- *2022.02* AAAI Student Scholar Scholarship. 
- *2020.06~2022.01* SNU Global Scholarships II. [\[link\]](https://oia.snu.ac.kr/snu-global-scholarships-iii)

# 📖 Educations
- *2020.09 - 2023.05 (now)*, Ph.D. Candidate in Computer Science and Engineering, Seoul National University.
- *2018.09 - 2020.06*, M.S. Student in Computer Science and Engineering, Seoul National University.
- *2014.09 - 2018.06*, B.S. Student in Software Engineering, Jilin University.

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships -->
<!-- - *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->