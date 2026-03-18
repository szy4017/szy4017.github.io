---
layout: default
title: 施振宇 | Home
---

<style>
  .hero {
    text-align: center;
    padding: 3rem 0;
  }
  .hero .avatar-container {
    margin-bottom: 1.5rem;
  }
  .hero .avatar {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid #00d4aa;
    box-shadow: 0 4px 15px rgba(0, 212, 170, 0.3);
  }
  .hero .site-title {
    font-size: 2.5rem;
    margin-bottom: 0.5rem;
    color: #fff;
  }
  .hero .site-subtitle {
    font-size: 1.1rem;
    color: #94a3b8;
    margin-bottom: 1.5rem;
  }
  .about-section {
    background: rgba(255,255,255,0.05);
    border-radius: 12px;
    padding: 2rem;
    margin: 2rem 0;
  }
  .skills-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 0.5rem;
    justify-content: center;
  }
  .skill-tag {
    padding: 0.4rem 1rem;
    background: rgba(0, 212, 170, 0.15);
    border: 1px solid rgba(0, 212, 170, 0.3);
    border-radius: 20px;
    color: #00d4aa;
    font-size: 0.9rem;
  }
  .social-links {
    display: flex;
    justify-content: center;
    gap: 1rem;
    margin-top: 1rem;
  }
  .social-links a {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    padding: 0.5rem 1rem;
    background: rgba(255,255,255,0.1);
    border-radius: 8px;
    color: #fff;
    text-decoration: none;
    font-size: 0.9rem;
    transition: background 0.3s;
  }
  .social-links a:hover {
    background: rgba(255,255,255,0.2);
  }
  .social-links .icon {
    width: 20px;
    height: 20px;
  }
</style>

<div class="hero">
  <div class="avatar-container">
    <img src="assets/avatar.png" alt="施振宇" class="avatar" width="150" height="150">
  </div>
  <h1 class="site-title">施振宇</h1>
  <p class="site-subtitle">Developer | Creator | Problem Solver</p>
  <div class="social-links">
    <a href="https://github.com/szy4017" target="_blank" rel="noopener">
      <svg class="icon" viewBox="0 0 24 24">
        <path fill="currentColor" d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
      </svg>
      GitHub
    </a>
  </div>
</div>

<div class="about-section">
  <h2>About Me</h2>
  <div class="about-content">
    <p>你好，我是施振宇 👋</p>
    <p>这里是我的个人空间，我会在这里分享我的项目和思考。</p>
    <p>更多内容正在筹备中，敬请期待...</p>
  </div>
</div>

<div class="skills-section">
  <h2>Tech Stack</h2>
  <div class="skills-grid">
    <span class="skill-tag">JavaScript</span>
    <span class="skill-tag">Python</span>
    <span class="skill-tag">TypeScript</span>
    <span class="skill-tag">Node.js</span>
    <span class="skill-tag">React</span>
    <span class="skill-tag">Vue</span>
  </div>
</div>
