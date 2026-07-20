---
permalink: /about-zh/
# title: "林海华 - 个人主页"
author_profile: true
---

<div style="text-align: right; margin-bottom: 10px;">
  <a href="/" style="font-size: 14px; padding: 5px 15px; border: 1px solid #ccc; border-radius: 4px; text-decoration: none; color: #333;">EN</a>
</div>

<h1 id="introduction">你好 <img src="images/Hi.gif" width="40px" /> 欢迎来到我的主页！</h1>

## 关于我

我是**苏州大学**的**研一硕士生**，专业是计算机技术，研究方向为**自然语言处理**。

<h2 id="news">新闻</h2>

<ul>
  
</ul>

<h2 id="publications">代表性论文</h2>

<!-- 在此添加您的论文，格式如下：
<div class="publication-card">
  <div class="image-wrapper" onclick="openLightbox('images/your_paper.png')">
    <img src="images/your_paper.png" alt="论文标题" class="paper-image" />
  </div>
  <div class="publication-details">
    <span style="color:#ca6f6f; font-weight:500;">论文标题</span><br/>
    <div class="author-links" style="font-size: 13px">
      作者1, <strong>您的姓名</strong>, 作者3
    </div>
    <div style="font-size: 13px;">会议/期刊名称</div>
    <div class="paper-links" style="font-size:13px;">
      <a href="#" class="abstract-toggle" onclick="toggleAbstract(event, 'abstract-1')">[摘要]</a>
      <a href="paper_link">[论文]</a>
      <a href="code_link">[代码]</a>
    </div>
    <div id="abstract-1" class="abstract-container">
      <div class="abstract-content">在此输入摘要...</div>
    </div>
  </div>
</div>
-->

<h2 id="awards">荣誉奖项</h2>

<ul>
  
</ul>

<h2 id="competitions">竞赛经历</h2>

<ul>
  <li><strong>2026</strong> - 第十六届蓝桥杯全国软件和信息技术专业人才大赛 全国二等奖</li>
  <li><strong>2026</strong> - 百度之星程序设计大赛 省级银奖</li>
  <li><strong>2026</strong> - 马蹄杯程序设计大赛 省级银奖</li>
  <li><strong>2025</strong> - RAICOM机器人开发者大赛 全国二等奖</li>
  <li><strong>2025</strong> - 传智杯全国IT技能大赛 全国三等奖</li>
  <li><strong>2025</strong> - 团体程序设计天梯赛 全国总决赛个人三等奖</li>
  <li><strong>2025</strong> - 团体程序设计天梯赛 全国总决赛团体二等奖</li>
  <li><strong>2025</strong> - 中国大学生程序设计竞赛（广东省赛）优胜奖</li>
  <li><strong>2024</strong> - 全国大学生数学建模竞赛 广东省三等奖</li>
  <li><strong>2024</strong> - 全国大学生计算机技能应用大赛 省级二等奖</li>
  <li><strong>2024</strong> - 全国大学生数学竞赛 省级二等奖</li>
</ul>

<h2 id="experience">教育经历</h2>

<table style="border-collapse: collapse; width: 100%;">
  <tr>
    <td style="border: none; padding: 10px;">
      <img src="images/soochow.jpg" alt="苏州大学校徽" width="60" style="vertical-align: middle; margin-right: 15px;" />
      <strong>苏州大学</strong> — 计算机技术硕士（2026年9月 - 2029年6月）
    </td>
  </tr>
  <tr>
    <td style="border: none; padding: 10px;">
      <img src="images/shantou.png" alt="汕头大学校徽" width="60" style="vertical-align: middle; margin-right: 15px;" />
      <strong>汕头大学</strong> — 计算机科学与技术学士（2022年10月 - 2026年7月）
    </td>
  </tr>
</table>

<h2 id="contact">联系方式</h2>

邮箱：<a href="mailto:1994953194@qq.com">1994953194@qq.com</a> / <a href="mailto:linda1994953@gmail.com">linda1994953@gmail.com</a>

<!-- Lightbox Overlay -->
<div id="lightbox-overlay" onclick="closeLightbox()" style="display:none; position:fixed; top:0; left:0; width:100%; height:100%; background:rgba(250,250,250,0.88); justify-content:center; align-items:center; z-index:10000;">
  <img id="lightbox-image" src="" alt="放大查看" style="max-width:90%; max-height:90%; border:2px solid #e0e0e0; box-shadow:0 4px 20px rgba(0,0,0,0.12); border-radius:8px;" />
</div>

<script>
  function toggleAbstract(event, abstractId) {
    event.preventDefault();
    const container = document.getElementById(abstractId);
    if (container.style.display === 'block') {
      container.style.display = 'none';
    } else {
      container.style.display = 'block';
    }
  }
  function openLightbox(src) {
    const overlay = document.getElementById('lightbox-overlay');
    const img = document.getElementById('lightbox-image');
    img.src = src;
    overlay.style.display = 'flex';
    document.body.style.overflow = 'hidden';
  }
  function closeLightbox() {
    document.getElementById('lightbox-overlay').style.display = 'none';
    document.body.style.overflow = '';
  }
  document.addEventListener('keydown', (e) => {
    if (e.key === 'Escape') closeLightbox();
  });
</script>
