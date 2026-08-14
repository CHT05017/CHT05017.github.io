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

<div style="font-family: 'Times New Roman', Times, serif;" markdown="1">

<h1 style="color: rgb(31, 78, 121); font-family: 'Times New Roman', Times, serif;">
  Education
</h1>

<h3 style="color: rgb(166, 45, 45); font-family: 'Times New Roman', Times, serif;">
  Peking University
</h3>
  
**Ph.D. Student in Signal Processing**, *Starting Fall 2027*

Research Interests: **AI4Communications**, **Machine Learning**, **Computer Vision**

<p>
  <span style="color: rgba(0, 0, 0, 0.5);">
    <em>
      School of Electronics<br>  
    </em>
  </span>
</p>

---

<h3 style="color: rgb(166, 45, 45); font-family: 'Times New Roman', Times, serif;">
  Jilin University
</h3>

**B.Eng. in Electronic Information Engineering**, 2023 – Present  

<p>
  <span style="color: rgba(0, 0, 0, 0.5);">
    <em>  
      College of Electronic Science and Engineering<br>
    </em>
  </span>
</p>

<h1 style="color: rgb(31, 78, 121); font-family: 'Times New Roman', Times, serif;">
   Honors and Awards
</h1>

*2026.5*, **Huawei Scholarship (华为奖学金)**, Huawei Technologies Co., Ltd.
  
*2026.4*, **High-Level Competitions Scholarship (高水平竞赛奖学金)**, Jilin University  
  
*2025.9*, **National Scholarship (国家奖学金)**, Ministry of Education of China  
  
*2025.5*, **Finalist Award (Top 2.3%)**, Mathematical Contest in Modeling (美国大学生数学建模竞赛)  

*2025.4*, **Undergraduate Innovation Training Program (国家级大学生创新训练计划)--Project Completed**, Jilin University

*2025.3*, **Quanyangquan Scholarship (泉阳泉奖学金)**, Jilin Quanyangquan Co., Ltd.

*2024.11*, **Dongrong Scholarship (东荣奖学金)**, Dongyoung Scholarship Foundation

*2024.11*，**Annually Top Ten Students of College of Electronic Science and Engineering (电子学院年度十佳学生)**, Jilin University

*2024.9*, **National Scholarship (国家奖学金)**, Ministry of Education of China

*2024.8*, **Grand Prize in NECCS Finals (全国大学生英语竞赛, 总决赛特等奖)**, FLTRP (外研社)

<style>
  #research-experience {
    font-family: "Times New Roman", Times, serif;
  }

  .research-group {
    margin: 1.4rem 0 2rem;
  }

  .research-group-title {
    margin: 0 0 0.85rem;
    color: rgb(166, 45, 45);
  }

  .research-card {
    margin-bottom: 1rem;
    padding: 1rem 1.15rem;
    background: rgba(31, 78, 121, 0.035);
    border: 1px solid rgba(31, 78, 121, 0.14);
    border-left: 4px solid rgb(31, 78, 121);
    border-radius: 6px;
  }

  .research-meta {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    gap: 0.45rem 0.75rem;
    margin-bottom: 0.45rem;
    color: rgba(0, 0, 0, 0.58);
    font-size: 0.92rem;
  }

  .venue-badge {
    padding: 0.12rem 0.5rem;
    color: rgb(166, 45, 45);
    background: rgba(166, 45, 45, 0.08);
    border-radius: 999px;
    font-weight: 700;
  }

  .research-title {
    margin: 0 0 0.45rem;
    color: #222;
    font-size: 1.04rem;
    line-height: 1.45;
  }

  .research-role {
    margin: 0.25rem 0 0.65rem;
    color: rgba(0, 0, 0, 0.68);
  }

  .research-topics {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
    margin-top: 0.55rem;
  }

  .topic-tag {
    padding: 0.15rem 0.55rem;
    color: rgb(31, 78, 121);
    background: rgba(31, 78, 121, 0.08);
    border-radius: 999px;
    font-size: 0.86rem;
  }

  .internship-card {
    border-left-color: rgb(166, 45, 45);
  }

  @media (max-width: 600px) {
    .research-card {
      padding: 0.9rem;
    }
  }
</style>

<section id="research-experience">

  <h1 style="color: rgb(31, 78, 121);">
    Research Experience
  </h1>

  <div class="research-group">
    <h3 class="research-group-title">Manuscripts Under Review</h3>

    <article class="research-card">
      <div class="research-meta">
        <span>May 2026</span>
        <span class="venue-badge">NeurIPS 2026</span>
        <span>Under Review</span>
      </div>

      <p class="research-title">
        <strong>
          HypMoE-ReID: Hyperspherical Mixture-of-Experts for
          Large-Scale Person Re-Identification
        </strong>
      </p>

      <p class="research-role">
        <strong>Co-first Author</strong> · 共同第一作者
      </p>

      <div class="research-topics">
        <span class="topic-tag">Sparse Computing</span>
        <span class="topic-tag">Mixture-of-Experts</span>
        <span class="topic-tag">Person Re-Identification</span>
      </div>
    </article>
  </div>

  <div class="research-group">
    <h3 class="research-group-title">Published Articles</h3>

    <article class="research-card">
      <div class="research-meta">
        <span>February 2026</span>
        <span class="venue-badge">CVPR 2026</span>
        <span>Conference Paper</span>
      </div>

      <p class="research-title">
        <strong>
          Vision-Language Attribute Disentanglement and Reinforcement
          for Lifelong Person Re-Identification
        </strong>
      </p>

      <p class="research-role">
        <strong>Co-first Author</strong> · 共同第一作者
      </p>

      <div class="research-topics">
        <span class="topic-tag">Lifelong Learning</span>
        <span class="topic-tag">Multimodal Learning</span>
        <span class="topic-tag">Person Re-Identification</span>
      </div>
    </article>

    <article class="research-card">
      <div class="research-meta">
        <span>January 2026</span>
        <span class="venue-badge">arXiv 2026</span>
        <span>Preprint</span>
      </div>

      <p class="research-title">
        <strong>
          Simon-SR: Spatially Adaptive Modulation and Visual Prompt
          Adaptation for Text-Reinforced Super-Resolution
        </strong>
      </p>

      <p class="research-role">
        <strong>Co-first Author</strong> · 共同第一作者
      </p>

      <div class="research-topics">
        <span class="topic-tag">Multimodal Learning</span>
        <span class="topic-tag">Image Restoration</span>
        <span class="topic-tag">Super-Resolution</span>
      </div>
    </article>

    <article class="research-card">
      <div class="research-meta">
        <span>September 2025</span>
        <span class="venue-badge">IET Image Processing</span>
        <span>Journal Article</span>
      </div>

      <p class="research-title">
        <strong>
          Optimization of Module Transferability in Single Image
          Super-Resolution: Universality Assessment and Cycle Residual Blocks
        </strong>
      </p>

      <p class="research-role">
        <strong>First Author</strong> · 第一作者
      </p>

      <div class="research-topics">
        <span class="topic-tag">Image Restoration</span>
        <span class="topic-tag">Super-Resolution</span>
        <span class="topic-tag">Transferability</span>
      </div>
    </article>
  </div>

  <div class="research-group">
    <h3 class="research-group-title">Research Internship</h3>

    <article class="research-card internship-card">
      <div class="research-meta">
        <span>June 2025 &ndash; June 2026</span>
        <span class="venue-badge">Peking University</span>
      </div>

      <p class="research-title">
        <strong>Research Intern</strong><br>
        Wangxuan Institute of Computer Technology
      </p>

      <p class="research-role">
        北京大学王选计算机研究所 · 科研实习生
      </p>

      <div class="research-topics">
        <span class="topic-tag">High-Level Vision</span>
        <span class="topic-tag">Learning Theory</span>
      </div>
    </article>
  </div>

</section>
</div>
