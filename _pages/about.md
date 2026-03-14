---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
    .experience-card {
        display: flex;
        align-items: center;
        background: #f9f9f9;
        border-radius: 12px;
        padding: 16px;
        margin-bottom: 0px;
        box-shadow: 0 4px 8px rgba(0,0,0,0.05);
        transition: transform 0.3s, box-shadow 0.3s;
    }
    .experience-card:hover {
       
        box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    }
    .experience-logo {
        width: 60px;
        height: 60px;
        margin-right: 20px;
        border-radius: 8px;
        object-fit: contain;
    }
    .experience-info {
        font-family: "Segoe UI", sans-serif;
    }
    .experience-info strong {
        font-size: 1.1em;
    }
    .experience-info a {
        text-decoration: none;
        color: #ca6f6f;
    }
    .experience-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 20px;
    }
    .experience-card {
        box-sizing: border-box;
    }
    .publication-card {
        display: flex;
        align-items: center;
        padding: 3px;
        border: 1.5px solid #ddd;
        border-radius: 8px;
        background: #fff;
        box-sizing: border-box;
        margin-bottom: 20px; 
        transition: transform 0.3s ease, box-shadow 0.3s ease;

        color: #5f6368; /* 正文整体更浅 */
    }
    .publication-card > div > strong,
    .publication-card > div > div > strong {
        color: #202124;
    }
    .publication-card i {
        color: #6b7280;
    }
    .publication-card:hover {
       
        box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    }

    .publication-card.featured {
        border-color: #f5bba7;       /* 更浅的哈密瓜色边框 */
        background: #fef5f1;         /* 非常浅的哈密瓜色背景 */
        box-shadow: 0 4px 8px rgba(242, 166, 120, 0.2); /* 更柔和的初始阴影 */
        z-index: 10;
    }

    .publication-card.featured:hover {
        box-shadow: 0 8px 16px rgba(242, 166, 120, 0.4); 
    }
    
    .publication-card.non-featured {
        display: flex; /* 默认隐藏非精选出版物 */
    }
    
    .pub-button-container {
        display: flex;
        gap: 10px;
        margin: 20px 0;
        flex-wrap: wrap;
    }
    
    .pub-button {
        background-color: #f0f0f0;
        border: 1px solid #ccc;
        border-radius: 20px;
        padding: 8px 16px;
        cursor: pointer;
        transition: all 0.3s ease;
    }
    
    .pub-button:hover {
        background-color: #e0e0e0;
    }
    
    .pub-button.active {
        background-color: #ca6f6f;
        color: white;
        border-color: #ca6f6f;
    }

    /* Projects cards: keep styles independent from publications */
    .project-card {
        display: flex;
        align-items: center;
        padding: 3px;
        border: 1.5px solid #ddd;
        border-radius: 8px;
        background: #fff;
        box-sizing: border-box;
        margin-bottom: 20px;
        transition: transform 0.3s ease, box-shadow 0.3s ease;

        color: #5f6368;
    }

    .project-card > div > strong,
    .project-card > div > div > strong {
        color: #202124;
    }

    .project-card i {
        color: #6b7280;
    }

    .project-card:hover {
        box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    }

</style>
<html> 
<head>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Permanent+Marker&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Fredericka+the+Great&display=swap');
        @import url('https://fonts.googleapis.com/css2?family=Homemade+Apple&display=swap');
        body {
            background-color:	 #FFFFFF;
            font-family: 'Arial Rounded MT Bold', 'Verdana', sans-serif;
            font-size: 15px;
        }
        .main-heading {
            font-family: 'Permanent Marker', cursive;
            text-align: center;
            color: #ca6f6f;
        }
        div.markdown-body a,a {
            text-decoration: none !important;
            color: #ca6f6f;
            transition: all 0.3s ease; /* 平滑过渡效果 */
        }
        div.markdown-body a:hover, a:hover {
            color: #c71585;            /* 悬浮时变深一点的颜色 */
            text-decoration: underline; /* 加上悬浮时的下划线 */
        }
    </style>
</head>
<body>
<h1 class="main-heading">Hi there <img src="images/Hi.gif" width="40px"> Welcome to my Homepage!</h1>
</body>
</html>

I am an undergraduate (2023–2027) at Southwest Jiaotong University. My research interests include reinforcement learning, agentic LLMs, and social recommendation.

I work at [Cityu](https://www.cityu.edu.hk/ace/) with [Prof. Songhua Hu](https://songhuahu-umd.github.io/).
Previously I worked at [ETS lab@THU](https://www.ets.svm.tsinghua.edu.cn/) with [Prof.Yang Liu](https://www.svm.tsinghua.edu.cn/essay/80/2107.html) 
Currently I conduct the Agent memory research at [ailab](https://ai45.shlab.org.cn/).

News
---------------
- *[A2GBD](https://github.com/Dcx-swjtu/A2GBD) is accepted in WWW 2026 &#128293;*
- *Our work achieved 7th place globally in the lightweight deployment track of Tencent 2025 OpenMind's Honor of Kings competition. &#128293;*
- *[DwT](https://arxiv.org/abs/2504.09479) is accepted in MM 2025
- *In charge of [Cybersecurity Club](https://ctf.show/). Feel free to reach out if you'd like to join.*

Experience
--------------

  <div class="experience-card">
      <img src="images/Cityu.png" alt="Cityu logo" class="experience-logo">
      <div class="experience-info">
          <strong>City University of Hong Kong</strong><br>
          June 2025 - Now<br>
          Research Intern, advised by <a href="https://songhuahu-umd.github.io/"><em>Prof. Songhua Hu</em></a>
      </div>
  </div>


  <div class="experience-card">
      <img src="images/ailab.jpg" alt="ailab logo" class="experience-logo">
      <div class="experience-info">
          <strong>Shanghai ailab</strong><br>
          Dec 2025 - Now<br>
          Research Intern at <a href="https://ai45.shlab.org.cn/"><em>ai45</em></a> Lab
      </div>
  </div>
  
<div class="experience-container">
  <div class="experience-card">
      <img src="images/thu.png" alt="thu logo" class="experience-logo">
      <div class="experience-info">
          <strong>THU ETS Lab</strong><br>
          Jan 2025 - Dec 2025<br>
          Research Intern at <a href="https://www.ets.svm.tsinghua.edu.cn/"><em>ETS Lab</em></a>, working on LLMs for Transportation and Mobility
      </div>
  </div>
  
  <div class="experience-card">
      <img src="images/SWJTU.jpg" alt="SWJTU logo" class="experience-logo">
      <div class="experience-info">
          <strong>Southwest Jiaotong University</strong><br>
          Jan 2024 - July 2027<br>
          <b>Academic Innovation Scholarship</b><br>
          B.E. at <a href="https://ctt.swjtu.edu.cn/xygknew/jtgcx.htm"><em>School of Transportation and Logistics, Southwest Jiaotong University</em></a>, advised by <a            href="https://faculty.swjtu.edu.cn/litianrui/zh_CN/index.htm"><em>Prof. Tianrui Li</em></a>
      </div>
  </div>
</div>

Publications
--------------

<div class="publication-card">
  <div style="display: flex; align-items: center;">
    <img src="images/WoG.png" alt="wog" width="200" height="100" style="margin-right: 20px;">
    <div>
        <strong>World Guidance: World Modeling in Condition Space for Action Generation</strong><br>
        <i style="font-size: 13px;">
            <a href="https://selen-suyue.github.io" target="_blank"><strong>Yue Su</strong></a>, 
            <a href="https://ch3cook-fdu.github.io/" target="_blank">Sijin Chen</a>,
            <a href="https://scholar.google.com/citations?user=sACkOGEAAAAJ&hl=en" target="_blank">Haixin Shi</a>, 
            <a href="https://mingyulau.github.io/" target="_blank">Mingyu Liu</a>,
            <a href="https://scholar.google.com/citations?user=8nrJ1vsAAAAJ&hl=en" target="_blank">Zhengshen Zhang</a>,
            <a href="" target="_blank">Ningyuan Huang</a>,
            <a href="https://scholar.google.com/citations?user=3EXYkZcAAAAJ&hl=zh-CN" target="_blank">Weiheng Zhong</a>,
            <a href="https://zbzhu99.github.io/" target="_blank">Zhengbang Zhu</a>,
            <a href="https://scholar.google.com/citations?user=i8wNtSgAAAAJ&hl=en" target="_blank">Yuxiao Liu</a>&dagger;,
            <a href="https://xh-liu.github.io/" target="_blank">Xihui Liu</a>&dagger;
        </i><br>
        We propose WoG (World Guidance), a world modeling paradigm  in condition space for action generation: less is more.
        <br>
        <b><i style="color:#83a1c7;">Arxiv Preprint &nbsp;</i></b>
        <a href="https://arxiv.org/abs/2602.22010"><em>[arXiv]</em></a>
        <a href="https://github.com/Selen-Suyue/WoG"><em>[code]</em></a>
        <a href="https://selen-suyue.github.io/WoGNet/"><em>[website]</em></a>
    </div>
  </div>
</div>

<div class="publication-card">
  <div style="display: flex; align-items: center;">
    <video width="200" height="120" style="margin-right: 20px; border-radius: 8px;" autoplay loop muted playsinline>
      <source src="images/clap.mp4" type="video/mp4">
    </video>
    <div>
        <strong>CLAP: Contrastive Latent Action Pretraining for Learning Vision-Language-Action Models from Human Videos</strong><br>
        <i style="font-size: 13px;">
            <a href="https://lin-shan.com/" target="_blank">Chubin Zhang</a>*,
            <a href="https://scholar.google.com/citations?user=mt5mvZ8AAAAJ&hl=en" target="_blank">Jianan Wang</a>*, 
            <a href="" target="_blank">Zifeng Gao</a>, 
            <a href="https://selen-suyue.github.io" target="_blank"><strong>Yue Su</strong></a>, 
            <a href="" target="_blank">Tiranru Dai</a>,
            <a href="https://homepage.zhouc.ai/" target="_blank">Cai Zhou</a>, <br>
            <a href="https://ivg.au.tsinghua.edu.cn/Jiwen_Lu/" target="_blank">Jiwen Lu</a>,
            <a href="https://andytang15.github.io/" target="_blank">Yansong Tang</a>&dagger;
        </i><br>
        Learning Vision-Language-Action Models from Human Videos.
        <br>
        <b><i style="color:#83a1c7;">ArXiv Preprint &nbsp;</i></b>
        <a href="https://arxiv.org/abs/2601.04061"><em>[arXiv]</em></a>
        <a href=""><em>[code]</em></a>
        <a href="https://lin-shan.com/CLAP/#"><em>[website]</em></a>
    </div>
  </div>
</div>


<script src="assets/js/show_publications.js"></script>

Projects
--------
<div class="project-card">
 <div style="display: flex; align-items: center;">
    <img src="images/maniunicon.png" alt="Maniunicon" width="200" height="100" style="margin-right: 20px;">
    <div>
        <strong>ManiUniCon: A Unified Control Interface for Robotic Manipulation</strong><br>
ManiUniCon is a comprehensive, multi-process robotics control framework designed for robotic manipulation tasks. It provides a unified interface for controlling various robot arms, integrating sensors, and executing policies in real-time. <br>
      <a href="https://github.com/Universal-Control/ManiUniCon"><em>[code]</em></a>
    </div>
</div>
</div>
<div class="project-card">
 <div style="display: flex; align-items: center;">
    <img src="images/MetaPalace.png" alt="MetaPalace" width="200" height="100" style="margin-right: 20px;">
    <div>
        <strong>MetaPalace: Let you in a meta world of The Palace Museum</strong><br>
We've done what the Old Palace official website couldn't: offering 3D artifact views with single-view reconstruction and an interactive LLM-powered tour guider using RAG technology. <br>
      <a href="https://metapalace.xj63.fun/"><em>[website]</em></a> 
      <a href="https://github.com/xj63/MetaPalaceSite"><em>[front-end code]</em></a>
      <a href="https://github.com/Selen-Suyue/MetaPalace"><em>[back-end code]</em></a>
    </div>
</div>
</div>


Awards
--------
- Academic Innovation Scholarship 2025

Talks
--------

