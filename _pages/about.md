---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .edu-row {
    display: flex;
    align-items: center;
    gap: 20px;
    margin-bottom: 40px;
  }
  .edu-info {
    flex: 1;
    font-size: 1.1em;
  }
  .logo-wrap {
    flex-shrink: 0;
    width: 100px;      /* 或者 max-width:100px 都行 */
    height: 80px;      /* 这里统一设高 */
    display: flex;     /* 让图片在这里居中 */
    align-items: center;
    justify-content: center;
  }
  .logo-wrap img {
    max-height: 100%;  /* 图片最多撑满容器高度 */
    width: auto;       /* 等比缩放 */
    object-fit: contain;
  }
</style>

<style>
  dl {
    margin-bottom: 60px; /* 调整这个值以获得合适的间距 */
    clear: both;
  }

  /* 全局文本颜色 */
  body {
    color: #333; /* 主要文本颜色 */
  }

  /* 链接颜色 */
  a {
    color: #0066cc; /* 链接颜色 */
  }

  /* 作者名字颜色 */
  strong {
    color: #000; /* 作者名字颜色 */
  }

  /* 年份标题颜色 */
  .year-title {
    color: #666;
  }

  /* 会议标签样式 */
  .conference-label {
    position: absolute;
    top: 10px;
    left: -5px;
    background-color: #2c3e50;  /* 深蓝色背景 */
    color: white;  /* 白色文字 */
    padding: 6px 12px;
    border-radius: 6px;
    font-size: 0.95em;
    font-weight: 600;
    letter-spacing: 0.5px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
    z-index: 1;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
    font-style: italic;  /* 添加斜体 */
  }

  /* 鼠标悬停效果 */
  .conference-label:hover {
    background-color: #34495e;  /* 悬停时稍微变亮 */
    transition: background-color 0.2s ease;
  }

  dl dt img {
    width: 400px; /* 设定统一宽度 */
    height: 200px; /* 设定统一高度 */
    object-fit: cover; /* 确保图片不会被裁剪 */
    display: block;
    margin: 10px 10px 10px 0px; /* 适当的间距 */
    
    /* 添加美化效果 */
    border-radius: 8px; /* 让图片有轻微的圆角 */
    border: 2px solid #ddd; /* 添加淡灰色的边框 */
    box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.2); /* 添加轻微阴影 */
    padding: 5px; /* 给图片一些内边距，让它不贴着边框 */
    background-color: #fff; /* 设置背景色，让图片更加干净 */
  }

  dl dt {
    position: relative;
  }

  hr {
    border: 1px solid #ebebeb; /* 调整分隔线的颜色和样式 */
    /* margin: 10px;  */
    clear: both; 
  }

  dl dd {
  margin-top: 5px; 
  margin-bottom: 5px;
}

  dl dd strong {
  font-weight: bold;
  color: black;
  }

  .co-first {
    color: red;
  }

  .down {
    transform: rotate(180deg);
  }

</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

# 🤵🏻 About Me


My name is Rui Zhu (Ray, 朱睿), an 3<sup>rd</sup>-year undergraduate student at School of Intelligence Science and Technology in Nanjing University, where I am very fortunate to be advised by [Prof. Lan-Zhe Guo](https://www.lamda.nju.edu.cn/guolz/).

<!-- <span class="pronunciation" style="cursor: pointer;" onclick="this.nextElementSibling.style.display = this.nextElementSibling.style.display === 'none' ? 'block' : 'none'; this.querySelector('.toggle-symbol').textContent = this.nextElementSibling.style.display === 'block' ? '▼' : '►';"><span class="toggle-symbol" style="margin-right: 5px;">►</span><span style="color: gray;">How to pronounce?</span></span>
<span style="display: none;">My name is pronounced as "Gwan-chung Wan". The "Gwan" rhymes with "man", and "chung" sounds like "chung" in "chunk".</span> -->

Also, I am a member of D<sup>3</sup> Lab at College of William and Mary, working closely with [Yang Li](https://littlestone111.github.io/) and [Prof. Hai-Peng Chen](https://haipeng-chen.github.io/).

<div style="text-align: left; margin: 20px 0;">
  <img src="../images/signature.png" alt="Signature" style="max-width: 300px; height: auto;">
</div>

# 🎓 Research 
<!-- "All things are interconnected, this is the essence of nature."  -->

<!-- <dt style="text-align: center; margin: 0; padding: 0;">
  <img src="../images/research.png" style="display: block; max-width: 700px; width: 100%; height: auto; margin: 0 auto;">
</dt> -->

My long-term goal is to build a safe, reliable, and efficient AI system, achieving artificial general intelligence (AGI). Most recently, my research mainly focuses on (Multimodal) Large Language Models (LLMs) and their applications:


a) How to design advanced algorithms for improve the reasoning abilities in LLMs? 
- *e.g.*, Supervised Fine-Tuning, Reinforcement Learning, Test-Time Scaling

b) How to improve the efficiency of reasoning? 
- *e.g.*, Fast/Slow Thinking, Over-Thinking, Long CoT Compression

c) How to apply LLMs in more real-world tasks? 
- *e.g.*, Math Reasoning, Legal Reasoning, Visual Reasoning


<br/>

# 📖 Education

<div class="edu-row">
  <div class="edu-info">
    <strong>2022.09 - 2026.06</strong><br/>
    Undergraduate, School of Intelligence Science and Technology, Nanjing University
  </div>
  <div class="logo-wrap">
    <img src="../images/NJU.png" alt="Nanjing University Logo" />
  </div>
</div>

<div class="edu-row">
  <div class="edu-info">
    <strong>2019.09 - 2022.06</strong><br/>
    High School, Nantong High School (江苏省南通中学)
  </div>
  <div class="logo-wrap">
    <img src="../images/tongzhong.png" alt="High School Logo" />
  </div>
</div>

# 🔥 News


<div style="max-height: 250px; overflow-y: auto;">
<ul>
  <!-- <li><em>2025.05:</em> 🎉 Some papers were accepted by <strong>ICML 2025</strong> with <strong class="co-first"> Two Spotlights (Top 2.6%)</strong>. See you in Vancouver!</li>
  <li><em>2024.11:</em> 🎈I was honored with <strong>Lei Jun Excellence Scholarship</strong> ~ <strong>100k</strong> (The <strong><u>Highest</u></strong> Scholarship at Wuhan University, <strong><u>Top-4</u></strong> among All Undergraduates, Award Rate ~ <strong>0.01%</strong>)</li>
  <li><em>2024.04:</em> 🚀 Explore our pre-print: a deep look at using Graph Neural Networks in Epidemic Modeling. Check our collected <a href="https://github.com/Emory-Melody/awesome-epidemic-modeling-papers">paper list</a>.</li> -->
  <li><em>2025.05:</em> 🚀 I built this personal website! Hope you like it.</li>
</ul>
</div>

<br/>

# 📃 Publications

**&dagger; Equal Contribution**   

<!-- <div style="text-align: left; margin: 20px 0; font-size: 1.2em; color: #666;">
2025 
</div>

<dl>
  <dt><img align="left"  width="400"
  hspace="10" wspace="20" src="../images/flsurvey.png">
  <span class="conference-label">TPAMI 2024</span>
  </dt>
  <dd><a href="https://arxiv.org/abs/2311.06750"><strong>Federated Learning for Generalization, Robustness, Fairness: A Survey and Benchmark</strong></a></dd>
  <dd>Wenke Huang, Mang Ye, Zekun Shi, <strong>Guancheng Wan</strong>, He Li, Bo Du,  Qiang Yang
  </dd>
    <dd>IEEE Transactions on Pattern Analysis and Machine Intelligence (<strong>TPAMI</strong>), 2024</dd>
    <dd><a href="https://github.com/WenkeHuang/MarsFL">Project Page</a></dd>
</dl> -->
Wait to be updated...

<br/>


# 🎡 Service

## Conference Committee Member
<!-- - Reviewer for ICML'2025, ICLR'2025, NeurIPS'2024/2025, AISTATS'2025
- Reviewer for CVPR'2024/2025, ICCV'2025, ECCV'2024 -->
- Reviewer for IJCAI'2025, ECAI'2025

<!-- ##  Journal Reviewer
- IEEE TIFS, TIP, TKDE, TNNLS
- ACM TKDD
- Pattern Recognition (PR)
- Data-centric Machine Learning Research (DMLR) -->


<br/>

# 🎖 Honors


Wait to be updated...

<!-- - *2024.11* **Lei Jun Excellence Scholarship** (**<u>雷军卓越奖学金</u>**) **~100k** (The **<u>Highest</u>** Scholarship at Wuhan University, **<u>Top-4</u>** among All Undergraduates, Award Rate: 10/65000+ ~ **0.01%**)  *Wuhan University*

- *2023.09* **National Scholarship** **(<u>Twice</u>)** (**<u>国家奖学金</u>**) (Award Rate: <strong>0.2% nation-wide</strong>) *Ministry of Education, China* 

- *2022.09* **National Scholarship** (**<u>国家奖学金</u>**) (Award Rate: <strong>0.2% nation-wide</strong>) *Ministry of Education, China* 

- *2024.10* **Luojia Undergraduate Innovation Research Fund** (首批珞珈本科生研究基金) ~50k (4 Students department-wide)  *Wuhan University*

- *2024.06* **Lei Jun Computer Innovation and Development Fund** and  **Research Fund** (雷军创新发展基金、雷军研究基金) (3 Students department-wide)  *Wuhan University*

- *2024.06* <a href="https://scholarship2024.sensetime.com/cn/">**SenseTime Scholarship**</a> (商汤奖学金) ~20k (**25 Students nation-wide**) *SenseTime*

- *2024.04* <a href="https://mp.weixin.qq.com/s/zdx8hH8-g0FScgZvkYQRnw">**CS Pioneer**</a> (计科先锋年度人物) (10 Students department-wide)  *Wuhan University*

- *2023.10* **CCF (China Computer Federation) Elite Collegiate Award** (CCF优秀大学生) (102 Students nation-wide) *China Computer Federation*

- *2023.10* **Pacemaker to Merit Student** (三好学生标兵) (Award Rate: 60/65000+ ~ <strong>0.1%</strong>) *Wuhan University* -->


<br/>




<dl>

<a href="https://clustrmaps.com/site/1c5xx" title="Visit tracker"><img src="//clustrmaps.com/map_v2.png?cl=080808&w=400&t=tt&d=3hrSiEfTSebpoQwhY5yp6m-0m9AQYdzpwqX6vag6R4c&co=ffffff&ct=808080" /></a>

</dl>




<!-- # Miscellaneous

<details>
  <summary><strong>Talks and Shares</strong></summary>
<dd><a href="https://www.bilibili.com/video/BV1gZ42177VL/?spm_id_from=333.337.search-card.all.click&vd_source=0b7a3cc3d3ec288abaca83b9a7e036af"><strong>泛化图学习与本科生科研经历分享</strong></a></dd>




</details>


<details>
  <summary><strong>Undergraduate research resource and enrollment process</strong></summary>

<dd><a href="https://zxeupbuzh9y.feishu.cn/docx/ZDEsdpZtPosRWOxcBnkcF8Hknkd"><strong>Link</strong></a></dd>


</details>



<details>
  <summary><strong>Poems that inspire me</strong></summary>
  <dd><strong>白鹭立雪，愚者看鹭，聪者观雪，智者见白</strong> —— A white egret stands in the snow. The foolish see only the egret, the wise observe the snow, and the enlightened perceive the whiteness.</dd>
  <dd><strong>世界不黑也不白, 而是一道精致的灰</strong> —— The world is neither black nor white, but a delicate shade of gray. </dd>
    <dd><strong>风吹到哪页读哪页</strong> —— The wind blows to which page, read which page.. </dd>
</details> -->




