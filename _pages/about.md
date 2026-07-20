---
permalink: /
# title: "Haihua Lin - Personal Homepage"
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
    font-family: 'Arial Rounded MT Bold', 'Verdana', sans-serif;
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
  .publication-card.featured {
    border-color: #f5bba7;
    box-shadow: 0 4px 8px rgba(242, 166, 120, 0.2);
    z-index: 10;
  }
  .publication-card.featured:hover {
    box-shadow: 0 8px 16px rgba(242, 166, 120, 0.4);
  }
  .paper-links a {
    color: #ca6f6f !important;
    text-decoration: none;
  }
  .paper-links a:hover {
    color: #c71585 !important;
    text-decoration: underline;
  }
  .author-links a {
    color: #494E52 !important;
    text-decoration: none;
  }
  .author-links a:hover {
    color: #000000 !important;
    text-decoration: underline;
  }
  /* Abstract section styles */
  .abstract-container {
    background-color: #f5f5f5;
    border-radius: 8px;
    padding: 12px;
    margin-top: 8px;
    display: none;
    position: relative;
    z-index: 1;
  }
  .abstract-content {
    font-size: 13px;
    line-height: 1.5;
  }
  .abstract-toggle {
    cursor: pointer;
    font-weight: normal;
    display: inline-block;
    font-size: 13px;
  }
  .abstract-toggle:hover {
    text-decoration: underline;
  }
  /* Bibtex section styles */
  .bibtex-container {
    background-color: #f5f5f5;
    border-radius: 8px;
    padding: 12px;
    margin-top: 8px;
    display: none;
    position: relative;
    z-index: 1;
  }
  .bibtex-content pre {
    font-size: 13px;
    line-height: 1.5;
    font-family: 'Arial Rounded MT Bold', 'Verdana', sans-serif;
    white-space: pre-wrap;
    word-wrap: break-word;
    margin: 0;
    padding: 0;
    overflow-wrap: break-word;
  }
  /* Image wrapper for lightbox */
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
  /* Lightbox overlay */
  #lightbox-overlay {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(250, 250, 250, 0.88);
    backdrop-filter: blur(4px);
    display: none;
    justify-content: center;
    align-items: center;
    z-index: 10000;
  }
  #lightbox-image {
    max-width: 90%;
    max-height: 90%;
    border: 2px solid #e0e0e0;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.12);
    border-radius: 8px;
  }
  body {
    background-color: #FFFFFF;
    font-family: 'Arial Rounded MT Bold', 'Verdana', sans-serif;
    font-size: 15px;
  }
  .main-heading {
    font-family: 'Permanent Marker', cursive;
    text-align: center;
    color: #ca6f6f;
  }
  div.markdown-body a, a {
    text-decoration: none !important;
    color: #ca6f6f;
    transition: all 0.3s ease;
  }
  div.markdown-body a:hover, a:hover {
    color: #c71585;
    text-decoration: underline;
  }
</style>

<h1 id="introduction" class="main-heading">Hi there <img src="images/Hi.gif" width="40px" /> Welcome to my Homepage!</h1>

## About Me

I am a **first-year master's student** at Soochow University, majoring in Computer Technology. My research interests focus on **Natural Language Processing**.

<h2 id="news">News</h2>

<p style="color: #666; font-style: italic;">Stay tuned for upcoming news and updates.</p>

<h2 id="publications">Selected Publications</h2>

<p style="color: #666; font-style: italic;">Research in progress. Publications will be updated soon.</p>

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
  <li><strong>2026</strong> - Outstanding Graduate of School of Mathematics and Computer Science, Shantou University (2025-2026)</li>
  <li><strong>2025</strong> - First-Class Comprehensive Scholarship, Shantou University (2024-2025)</li>
  <li><strong>2025</strong> - Third-Class Comprehensive Scholarship, Shantou University (2023-2024)</li>
  <li><strong>2024</strong> - Third-Class Comprehensive Scholarship, Shantou University (2022-2023)</li>
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

<div class="experience-container">
  <div class="experience-card">
    <img src="images/soochow.jpg" alt="Soochow University logo" class="experience-logo" />
    <div class="experience-info">
      <strong>Soochow University</strong><br />
      Sep 2026 - June 2029<br />
      M.S. in Computer Technology
    </div>
  </div>
  <div class="experience-card">
    <img src="images/shantou.png" alt="Shantou University logo" class="experience-logo" />
    <div class="experience-info">
      <strong>Shantou University</strong><br />
      Oct 2022 - Jul 2026<br />
      B.E. in Computer Science and Technology
    </div>
  </div>
</div>

<h2 id="contact">Contact Me</h2>

My preferred emails: <span style="color: #c71585;">1994953194@qq.com</span> / <span style="color: #c71585;">linda1994953@gmail.com</span>

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
