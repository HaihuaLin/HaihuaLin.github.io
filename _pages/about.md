---
permalink: /
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Playfair+Display:wght@700&display=swap');

  :root {
    --primary-color: #2c3e50;
    --accent-color: #e74c3c;
    --text-color: #333;
    --text-light: #666;
    --bg-light: #f8f9fa;
    --border-color: #eee;
  }

  * {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  }

  .main-heading {
    font-family: 'Playfair Display', serif;
    text-align: center;
    color: var(--primary-color);
    font-size: 2.2em;
    margin-bottom: 10px;
  }

  h2 {
    color: var(--primary-color);
    font-weight: 600;
    font-size: 1.5em;
    border-bottom: 2px solid var(--accent-color);
    padding-bottom: 8px;
    margin-top: 35px;
  }

  p, li {
    color: var(--text-color);
    line-height: 1.8;
    font-size: 15px;
  }

  a {
    color: var(--accent-color) !important;
    text-decoration: none !important;
    transition: all 0.3s ease;
  }

  a:hover {
    color: #c0392b !important;
    text-decoration: underline !important;
  }

  .experience-card {
    display: flex;
    align-items: center;
    background: white;
    border-radius: 12px;
    padding: 20px;
    margin-bottom: 15px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.08);
    transition: transform 0.3s, box-shadow 0.3s;
    border: 1px solid var(--border-color);
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
    font-size: 14px;
  }

  .experience-info strong {
    font-size: 1.05em;
    color: var(--primary-color);
  }

  .experience-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 15px;
  }

  ul {
    padding-left: 0;
    list-style: none;
  }

  ul li {
    padding: 10px 0;
    border-bottom: 1px dashed var(--border-color);
    font-size: 14px;
  }

  ul li:last-child {
    border-bottom: none;
  }

  ul li strong {
    display: inline-block;
    background: var(--accent-color);
    color: white;
    padding: 2px 10px;
    border-radius: 4px;
    font-size: 12px;
    margin-right: 10px;
    font-weight: 500;
  }

  .contact-email {
    display: inline-block;
    background: var(--bg-light);
    padding: 8px 16px;
    border-radius: 6px;
    margin: 5px;
    font-weight: 500;
  }
</style>

<h1 id="introduction" class="main-heading">Hi there <img src="images/Hi.gif" width="40px" /> Welcome to my Homepage!</h1>

## About Me

I am a **first-year master's student** at Soochow University, majoring in Computer Technology. My research interests focus on **Natural Language Processing**.

<h2 id="news">News</h2>

<ul>
  <li><strong>2026.09</strong> - Started my master's journey at Soochow University</li>
</ul>

<h2 id="publications">Selected Publications</h2>

<p style="color: var(--text-light); font-style: italic;">Coming soon...</p>

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
