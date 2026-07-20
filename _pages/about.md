---
permalink: /
# title: "Haihua Lin - Personal Homepage"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<h1 id="introduction">Hi there <img src="images/Hi.gif" width="40px" /> Welcome to my Homepage!</h1>

## About Me

I am a **first-year master's student** at Soochow University, majoring in Computer Technology. My research interests focus on **Natural Language Processing**.

<h2 id="news">News</h2>

<ul>
  
</ul>

<h2 id="publications">Selected Publications</h2>

<!-- Add your publications here with the following format:
<div class="publication-card">
  <div class="image-wrapper" onclick="openLightbox('images/your_paper.png')">
    <img src="images/your_paper.png" alt="Paper Title" class="paper-image" />
  </div>
  <div class="publication-details">
    <span style="color:#ca6f6f; font-weight:500;">Paper Title</span><br/>
    <div class="author-links" style="font-size: 13px">
      Author 1, <strong>Your Name</strong>, Author 3
    </div>
    <div style="font-size: 13px;">Conference/Journal Name</div>
    <div class="paper-links" style="font-size:13px;">
      <a href="#" class="abstract-toggle" onclick="toggleAbstract(event, 'abstract-1')">[Abstract]</a>
      <a href="paper_link">[Paper]</a>
      <a href="code_link">[Code]</a>
    </div>
    <div id="abstract-1" class="abstract-container">
      <div class="abstract-content">Your abstract here...</div>
    </div>
  </div>
</div>
-->

<h2 id="awards">Awards</h2>

<ul>
  <li><strong>2025</strong> - Shantou University Comprehensive Scholarship (Third Prize)</li>
  <li><strong>2024</strong> - National Encouragement Scholarship</li>
  <li><strong>2024</strong> - Shantou University Comprehensive Scholarship (Third Prize)</li>
  <li><strong>2024</strong> - Third Prize in National Mathematical Modeling Contest for College Students (Guangdong Provincial Division)</li>
</ul>

<h2 id="competitions">Competitions</h2>

<ul>
  <li><strong>2026</strong> - Second Prize in Lanqiao Cup National Software and Information Technology Competition (National Level)</li>
  <li><strong>2026</strong> - Silver Award in Baidu Star Programming Competition (Provincial Level)</li>
  <li><strong>2026</strong> - Silver Award in Mati Cup Programming Competition (Provincial Level)</li>
  <li><strong>2025</strong> - Second Prize in RAICOM Robot Developer Competition (National Level)</li>
  <li><strong>2025</strong> - Third Prize in Chuanzhi Cup National IT Skills Competition (National Level)</li>
  <li><strong>2025</strong> - Individual Third Prize in National Team Programming Ladder Competition (National Finals)</li>
  <li><strong>2025</strong> - Team Second Prize in National Team Programming Ladder Competition (National Finals)</li>
  <li><strong>2025</strong> - Merit Award in China Collegiate Programming Contest (Guangdong Provincial)</li>
  <li><strong>2024</strong> - Third Prize in National Mathematical Modeling Contest for College Students (Guangdong Provincial Division)</li>
  <li><strong>2024</strong> - Second Prize in National College Computer Skills Challenge (Provincial Level)</li>
  <li><strong>2024</strong> - Second Prize in National College Students Mathematics Competition (Provincial Level)</li>
</ul>

<h2 id="experience">Experience</h2>

<table style="border-collapse: collapse; width: 100%;">
  <tr>
    <td style="border: none; padding: 10px;">
      <img src="images/soochow.jpg" alt="Soochow University logo" width="60" style="vertical-align: middle; margin-right: 15px;" />
      <strong>Soochow University</strong> — M.S. in Computer Technology (Sep 2026 - June 2029)
    </td>
  </tr>
  <tr>
    <td style="border: none; padding: 10px;">
      <img src="images/shantou.png" alt="Shantou University logo" width="60" style="vertical-align: middle; margin-right: 15px;" />
      <strong>Shantou University</strong> — B.E. in Computer Science and Technology (Oct 2022 - Jul 2026)
    </td>
  </tr>
</table>

<h2 id="contact">Contact Me</h2>

My preferred emails: <a href="mailto:1994953194@qq.com">1994953194@qq.com</a> / <a href="mailto:linda1994953@gmail.com">linda1994953@gmail.com</a>

<!-- Lightbox Overlay -->
<div id="lightbox-overlay" onclick="closeLightbox()" style="display:none; position:fixed; top:0; left:0; width:100%; height:100%; background:rgba(250,250,250,0.88); justify-content:center; align-items:center; z-index:10000;">
  <img id="lightbox-image" src="" alt="Enlarged view" style="max-width:90%; max-height:90%; border:2px solid #e0e0e0; box-shadow:0 4px 20px rgba(0,0,0,0.12); border-radius:8px;" />
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
