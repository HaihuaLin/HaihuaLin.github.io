---
permalink: /
# title: "Haihua Lin - Personal Homepage"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
  /* 字体优化 - 增加Nunito备选 */
  body {
    font-family: 'Arial Rounded MT Bold', 'Nunito', 'Verdana', sans-serif;
  }

  /* 标题样式优化 */
  .main-heading {
    font-family: 'Permanent Marker', cursive;
    text-align: center;
    color: #ca6f6f;
    font-size: 2.2em;
    margin-bottom: 15px;
    letter-spacing: 0.5px;
  }

  h2 {
    color: #ca6f6f;
    font-size: 1.5em;
    border-bottom: 2px solid #f5bba7;
    padding-bottom: 8px;
    margin-top: 35px;
    margin-bottom: 20px;
  }

  /* 正文行高优化 */
  p, li {
    line-height: 1.8;
    color: #333;
  }

  /* 列表项优化 */
  ul {
    padding-left: 0;
    list-style: none;
  }

  ul li {
    padding: 12px 0;
    border-bottom: 1px dashed #eee;
    font-size: 14.5px;
  }

  ul li:last-child {
    border-bottom: none;
  }

  /* 年份标签样式 */
  ul li strong {
    display: inline-block;
    background: #ca6f6f;
    color: white;
    padding: 2px 10px;
    border-radius: 4px;
    font-size: 12px;
    margin-right: 10px;
    font-weight: 500;
  }

  /* 经验卡片优化 */
  .experience-card {
    display: flex;
    align-items: center;
    background: #f9f9f9;
    border-radius: 12px;
    padding: 20px;
    margin-bottom: 15px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    transition: transform 0.3s, box-shadow 0.3s;
    border: 1px solid #eee;
  }

  .experience-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 20px rgba(0,0,0,0.12);
  }

  .experience-logo {
    width: 65px;
    height: 65px;
    margin-right: 20px;
    border-radius: 10px;
    object-fit: contain;
  }

  .experience-info {
    font-family: 'Arial Rounded MT Bold', 'Nunito', 'Verdana', sans-serif;
  }

  .experience-info strong {
    font-size: 1.05em;
    color: #333;
  }

  .experience-info a {
    text-decoration: none;
    color: #ca6f6f;
  }

  .experience-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 15px;
  }

  /* 链接样式优化 */
  div.markdown-body a, a {
    text-decoration: none !important;
    color: #ca6f6f;
    transition: all 0.3s ease;
    border-bottom: 1px solid transparent;
  }

  div.markdown-body a:hover, a:hover {
    color: #c71585 !important;
    border-bottom-color: #c71585;
  }

  /* 邮箱样式 */
  .contact-email {
    display: inline-block;
    background: #f9f9f9;
    padding: 10px 18px;
    border-radius: 8px;
    margin: 5px;
    font-weight: 500;
    border: 1px solid #eee;
    transition: all 0.3s ease;
  }

  .contact-email:hover {
    background: #fff5f5;
    border-color: #f5bba7;
    transform: translateY(-2px);
  }

  /* Publication card */
  .publication-card {
    display: flex;
    align-items: flex-start;
    padding: 16px;
    border: 1.5px solid #ddd;
    border-radius: 8px;
    background: #fff;
    box-sizing: border-box;
    margin-bottom: 20px;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    min-height: 30px;
  }

  .publication-card:hover {
    box-shadow: 0 8px 16px rgba(0,0,0,0.1);
  }

  .paper-links a {
    color: #ca6f6f !important;
    text-decoration: none;
  }

  .paper-links a:hover {
    color: #c71585 !important;
  }

  /* Abstract section styles */
  .abstract-container {
    background-color: #f5f5f5;
    border-radius: 8px;
    padding: 12px;
    margin-top: 8px;
    display: none;
  }

  .abstract-content {
    font-size: 13px;
    line-height: 1.6;
  }

  .abstract-toggle {
    cursor: pointer;
    font-weight: normal;
    display: inline-block;
    font-size: 13px;
  }

  /* Lightbox overlay */
  #lightbox-overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(250, 250, 250, 0.9);
    backdrop-filter: blur(5px);
    display: none;
    justify-content: center;
    align-items: center;
    z-index: 10000;
  }

  #lightbox-image {
    max-width: 90%;
    max-height: 90%;
    border: 2px solid #e0e0e0;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.15);
    border-radius: 8px;
  }

  .paper-image {
    width: 100%;
    height: auto;
    max-height: 100%;
    object-fit: contain;
    object-position: center;
    transition: transform 0.2s;
    border-radius: 4px;
  }

  .paper-image:hover {
    transform: scale(1.05);
  }

  .image-wrapper {
    width: 200px;
    height: auto;
    min-height: 120px;
    margin-right: 20px;
    cursor: pointer;
    border-radius: 6px;
    overflow: hidden;
    flex-shrink: 0;
    align-self: flex-start;
    display: flex;
    align-items: center;
    justify-content: center;
  }
</style>

<h1 id="introduction" class="main-heading">Hi there <img src="images/Hi.gif" width="40px" /> Welcome to my Homepage!</h1>

## About Me

I am a **first-year master's student** at Soochow University, majoring in Computer Technology. My research interests focus on **Natural Language Processing**.

<h2 id="news">News</h2>

<ul>
  <li><strong>2026.09</strong> Started my master's journey at Soochow University</li>
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
  <li><strong>2026</strong> Outstanding Graduate, School of Mathematics and Computer Science, Shantou University</li>
  <li><strong>2025</strong> First-Class Comprehensive Scholarship, Shantou University (2024-2025)</li>
  <li><strong>2025</strong> Third-Class Comprehensive Scholarship, Shantou University (2023-2024)</li>
  <li><strong>2024</strong> Third-Class Comprehensive Scholarship, Shantou University (2022-2023)</li>
</ul>

<h2 id="competitions">Competitions</h2>

<ul>
  <li><strong>2026</strong> Second Prize, Lanqiao Cup National Software & IT Competition (National)</li>
  <li><strong>2026</strong> Silver Award, Baidu Star Programming Contest (Provincial)</li>
  <li><strong>2026</strong> Silver Award, Mati Cup Programming Contest (Provincial)</li>
  <li><strong>2025</strong> Second Prize, RAICOM Robot Developer Competition (National)</li>
  <li><strong>2025</strong> Third Prize, Chuanzhi Cup National IT Skills Competition (National)</li>
  <li><strong>2025</strong> Individual Third Prize, National Team Programming Ladder Competition (Finals)</li>
  <li><strong>2025</strong> Team Second Prize, National Team Programming Ladder Competition (Finals)</li>
  <li><strong>2025</strong> Merit Award, China Collegiate Programming Contest (Guangdong)</li>
  <li><strong>2024</strong> Third Prize, National Mathematical Modeling Contest (Guangdong)</li>
  <li><strong>2024</strong> Second Prize, National College Computer Skills Challenge (Provincial)</li>
  <li><strong>2024</strong> Second Prize, National College Students Mathematics Competition (Provincial)</li>
</ul>

<h2 id="experience">Experience</h2>

<div class="experience-container">
  <div class="experience-card">
    <img src="images/soochow.jpg" alt="Soochow University" class="experience-logo" />
    <div class="experience-info">
      <strong>Soochow University</strong><br />
      Sep 2026 - June 2029<br />
      M.S. in Computer Technology
    </div>
  </div>
  <div class="experience-card">
    <img src="images/shantou.png" alt="Shantou University" class="experience-logo" />
    <div class="experience-info">
      <strong>Shantou University</strong><br />
      Oct 2022 - Jul 2026<br />
      B.E. in Computer Science and Technology
    </div>
  </div>
</div>

<h2 id="contact">Contact Me</h2>

<p>Feel free to reach out to me via email:</p>

<p>
  <span class="contact-email">📧 1994953194@qq.com</span>
  <span class="contact-email">📧 linda1994953@gmail.com</span>
</p>

<!-- Lightbox Overlay -->
<div id="lightbox-overlay" onclick="closeLightbox()">
  <img id="lightbox-image" src="" alt="Enlarged view" />
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
