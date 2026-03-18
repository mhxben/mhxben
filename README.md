
<style>
  @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700&family=DM+Sans:wght@400;500;600&display=swap');

  .gh-root {
    background: #0d1117;
    color: #e6edf3;
    font-family: 'DM Sans', sans-serif;
    padding: 2rem 2.5rem;
    border-radius: 12px;
    border: 1px solid #21262d;
    max-width: 780px;
    margin: 0 auto;
  }

  .mono { font-family: 'JetBrains Mono', monospace; }

  .header-line {
    font-family: 'JetBrains Mono', monospace;
    color: #58a6ff;
    font-size: 12px;
    margin-bottom: 0.25rem;
    opacity: 0.7;
  }

  .name {
    font-size: 28px;
    font-weight: 600;
    color: #e6edf3;
    margin: 0 0 4px;
    letter-spacing: -0.5px;
  }

  .title-tag {
    font-family: 'JetBrains Mono', monospace;
    font-size: 13px;
    color: #7ee787;
    background: rgba(126,231,135,0.1);
    border: 1px solid rgba(126,231,135,0.25);
    border-radius: 6px;
    padding: 3px 10px;
    display: inline-block;
    margin-bottom: 1rem;
  }

  .bio {
    font-size: 14px;
    color: #8b949e;
    line-height: 1.6;
    margin-bottom: 1.5rem;
    border-left: 2px solid #21262d;
    padding-left: 12px;
  }

  .section-label {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    color: #58a6ff;
    text-transform: uppercase;
    letter-spacing: 2px;
    margin: 1.5rem 0 0.75rem;
    display: flex;
    align-items: center;
    gap: 8px;
  }
  .section-label::after {
    content: '';
    flex: 1;
    height: 1px;
    background: #21262d;
  }

  .skills-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-bottom: 1rem;
  }

  .skill-pill {
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    background: #161b22;
    border: 1px solid #30363d;
    border-radius: 6px;
    padding: 5px 12px;
    color: #c9d1d9;
    display: flex;
    align-items: center;
    gap: 6px;
  }
  .skill-pill .dot {
    width: 6px; height: 6px;
    border-radius: 50%;
  }

  .projects-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 10px;
  }

  .project-card {
    background: #161b22;
    border: 1px solid #30363d;
    border-radius: 8px;
    padding: 14px;
    position: relative;
    overflow: hidden;
  }
  .project-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
  }
  .project-card.kt::before { background: #7f52ff; }
  .project-card.kmp::before { background: #58a6ff; }

  .project-name {
    font-family: 'JetBrains Mono', monospace;
    font-size: 13px;
    font-weight: 700;
    color: #58a6ff;
    margin-bottom: 4px;
  }
  .project-desc {
    font-size: 12px;
    color: #8b949e;
    line-height: 1.5;
    margin-bottom: 10px;
  }
  .project-meta {
    display: flex;
    gap: 12px;
    font-size: 11px;
    font-family: 'JetBrains Mono', monospace;
    color: #6e7681;
    align-items: center;
  }
  .lang-dot {
    width: 10px; height: 10px;
    border-radius: 50%;
    display: inline-block;
  }

  .stats-row {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    margin-top: 0.75rem;
  }
  .stat-box {
    background: #161b22;
    border: 1px solid #30363d;
    border-radius: 8px;
    padding: 12px;
    text-align: center;
  }
  .stat-num {
    font-family: 'JetBrains Mono', monospace;
    font-size: 20px;
    font-weight: 700;
    color: #e6edf3;
  }
  .stat-label {
    font-size: 11px;
    color: #6e7681;
    margin-top: 2px;
  }

  .contact-row {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
    margin-top: 0.75rem;
  }
  .contact-btn {
    font-family: 'JetBrains Mono', monospace;
    font-size: 12px;
    padding: 7px 16px;
    border-radius: 6px;
    border: 1px solid #30363d;
    background: #161b22;
    color: #c9d1d9;
    cursor: pointer;
    display: flex;
    align-items: center;
    gap: 6px;
    text-decoration: none;
  }

  .footer-mono {
    font-family: 'JetBrains Mono', monospace;
    font-size: 11px;
    color: #3d444d;
    margin-top: 1.5rem;
    text-align: center;
  }
</style>

<div class="gh-root">

  <div class="header-line">// profile.md — last updated March 2026</div>
  <div class="name">Mohamed Ali Benouarzeg</div>
  <div class="title-tag">Android Dev · KMP · Kotlin · Jetpack Compose</div>
  <div class="bio">
    Building fast, clean, and intuitive mobile apps. I care about architecture, UI feel, and writing Kotlin that reads well. Currently exploring Kotlin Multiplatform to write once, run everywhere.
  </div>

  <div class="section-label">skills</div>
  <div class="skills-grid">
    <div class="skill-pill"><span class="dot" style="background:#7f52ff"></span>Kotlin</div>
    <div class="skill-pill"><span class="dot" style="background:#3ddc84"></span>Android</div>
    <div class="skill-pill"><span class="dot" style="background:#58a6ff"></span>Jetpack Compose</div>
    <div class="skill-pill"><span class="dot" style="background:#7f52ff"></span>KMP / CMP</div>
    <div class="skill-pill"><span class="dot" style="background:#f0883e"></span>Ktor</div>
    <div class="skill-pill"><span class="dot" style="background:#6db33f"></span>Spring Boot</div>
    <div class="skill-pill"><span class="dot" style="background:#f05032"></span>Git</div>
    <div class="skill-pill"><span class="dot" style="background:#8b949e"></span>MVVM · Clean Arch</div>
    <div class="skill-pill"><span class="dot" style="background:#58a6ff"></span>Retrofit · StateFlow</div>
    <div class="skill-pill"><span class="dot" style="background:#f24e1e"></span>Figma</div>
  </div>

  <div class="section-label">featured projects</div>
  <div class="projects-grid">
    <div class="project-card kt">
      <div class="project-name">ComposeKit</div>
      <div class="project-desc">A reusable UI component library built with Jetpack Compose, following Material 3.</div>
      <div class="project-meta">
        <span><span class="lang-dot" style="background:#7f52ff"></span> Kotlin</span>
        <span>⭐ 84</span>
        <span>🍴 12</span>
      </div>
    </div>
    <div class="project-card kmp">
      <div class="project-name">NoteFlow-KMP</div>
      <div class="project-desc">Cross-platform notes app using Kotlin Multiplatform and Compose Multiplatform.</div>
      <div class="project-meta">
        <span><span class="lang-dot" style="background:#58a6ff"></span> KMP</span>
        <span>⭐ 61</span>
        <span>🍴 9</span>
      </div>
    </div>
    <div class="project-card kt">
      <div class="project-name">KtorAPI-Starter</div>
      <div class="project-desc">Production-ready Ktor backend template with auth, routing, and PostgreSQL.</div>
      <div class="project-meta">
        <span><span class="lang-dot" style="background:#f0883e"></span> Ktor</span>
        <span>⭐ 43</span>
        <span>🍴 7</span>
      </div>
    </div>
    <div class="project-card kmp">
      <div class="project-name">WeatherNow</div>
      <div class="project-desc">Android weather app showcasing MVVM, Retrofit, and StateFlow in a clean arch setup.</div>
      <div class="project-meta">
        <span><span class="lang-dot" style="background:#3ddc84"></span> Android</span>
        <span>⭐ 29</span>
        <span>🍴 5</span>
      </div>
    </div>
  </div>

  <div class="section-label">github stats</div>
  <div class="stats-row">
    <div class="stat-box">
      <div class="stat-num" style="color:#7f52ff">90%</div>
      <div class="stat-label">Kotlin usage</div>
    </div>
    <div class="stat-box">
      <div class="stat-num" style="color:#7ee787">↑ streak</div>
      <div class="stat-label">daily commits</div>
    </div>
    <div class="stat-box">
      <div class="stat-num" style="color:#58a6ff">4+</div>
      <div class="stat-label">public repos</div>
    </div>
  </div>

  <div class="section-label">contact</div>
  <div class="contact-row">
    <a class="contact-btn" href="mailto:mohamedbenouarzeg1@gmail.com">✉ Email</a>
    <a class="contact-btn" href="https://www.linkedin.com/in/mohamed-ali-benouarzeg-3b55582b2/">in LinkedIn</a>
    <a class="contact-btn" href="https://instagram.com/mhx.kt">📷 Instagram</a>
  </div>

  <div class="footer-mono">/* open to collaborations & freelance work */</div>
</div>
