<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Poornimaa Shri V K — QA Automation Engineer</title>
<link rel="preconnect" href="https://fonts.googleapis.com"/>
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin/>
<link href="https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500;600;700&family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet"/>
<style>
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --bg-base: #0d1117;
    --bg-card: #161b22;
    --bg-deep: #010409;
    --border: #21262d;
    --border-hover: #30363d;
    --text-primary: #f0f6fc;
    --text-secondary: #c9d1d9;
    --text-muted: #8b949e;
    --text-faint: #484f58;
    --cyan: #00d9ff;
    --cyan-dim: rgba(0,217,255,0.1);
    --cyan-border: rgba(0,217,255,0.25);
    --purple: #a78bfa;
    --purple-dim: rgba(167,139,250,0.1);
    --purple-border: rgba(167,139,250,0.25);
    --green: #23c55e;
    --green-dim: rgba(35,197,94,0.1);
    --amber: #fbbf24;
    --amber-dim: rgba(251,191,36,0.1);
    --orange: #ff6c37;
    --orange-dim: rgba(255,108,55,0.1);
    --red: #cc0000;
    --red-dim: rgba(204,0,0,0.1);
    --java: #f89820;
    --java-dim: rgba(248,152,32,0.1);
    --db: #4479a1;
    --db-dim: rgba(68,121,161,0.1);
    --sel: #43b02a;
    --sel-dim: rgba(67,176,42,0.1);
    --jenkins: #d24939;
    --jenkins-dim: rgba(210,73,57,0.1);
  }

  html { scroll-behavior: smooth; }

  body {
    background: var(--bg-deep);
    color: var(--text-secondary);
    font-family: 'Inter', -apple-system, sans-serif;
    font-size: 15px;
    line-height: 1.6;
    min-height: 100vh;
    padding: 40px 20px 80px;
  }

  .page {
    max-width: 820px;
    margin: 0 auto;
  }

  /* ── CARD ── */
  .readme {
    background: var(--bg-base);
    border: 1px solid var(--border);
    border-radius: 16px;
    overflow: hidden;
    box-shadow: 0 0 0 1px rgba(0,217,255,0.04), 0 32px 80px rgba(0,0,0,0.6);
  }

  /* ── HERO ── */
  .hero {
    background: radial-gradient(ellipse 80% 60% at 50% -10%, rgba(0,217,255,0.07) 0%, transparent 70%), #0d1117;
    padding: 56px 40px 48px;
    text-align: center;
    border-bottom: 1px solid var(--border);
    position: relative;
  }

  .hero-tag {
    display: inline-block;
    font-size: 10px;
    letter-spacing: 3.5px;
    text-transform: uppercase;
    color: var(--cyan);
    border: 1px solid var(--cyan-border);
    padding: 6px 20px;
    border-radius: 40px;
    margin-bottom: 24px;
    font-family: 'Fira Code', monospace;
    background: var(--cyan-dim);
  }

  .hero-name {
    font-size: 42px;
    font-weight: 800;
    color: var(--text-primary);
    letter-spacing: -1.5px;
    line-height: 1.05;
    margin-bottom: 12px;
  }

  .hero-name .accent { color: var(--cyan); }

  .hero-role {
    font-size: 13px;
    color: var(--text-muted);
    font-family: 'Fira Code', monospace;
    margin-bottom: 32px;
    letter-spacing: 1px;
  }

  .hero-role .cursor {
    color: var(--cyan);
    animation: blink 1.1s step-end infinite;
  }

  @keyframes blink { 50% { opacity: 0; } }

  .hero-pills {
    display: flex;
    gap: 10px;
    justify-content: center;
    flex-wrap: wrap;
  }

  .pill {
    font-size: 11px;
    font-weight: 600;
    padding: 6px 16px;
    border-radius: 40px;
    letter-spacing: 0.5px;
  }

  .pill-c { background: var(--cyan-dim); color: var(--cyan); border: 1px solid var(--cyan-border); }
  .pill-p { background: var(--purple-dim); color: var(--purple); border: 1px solid var(--purple-border); }
  .pill-g { background: var(--green-dim); color: var(--green); border: 1px solid rgba(35,197,94,0.25); }

  /* ── SECTION ── */
  .section {
    padding: 36px 40px;
    border-bottom: 1px solid var(--border);
  }
  .section:last-child { border-bottom: none; }

  .sec-label {
    font-size: 10px;
    letter-spacing: 3px;
    text-transform: uppercase;
    color: var(--cyan);
    font-family: 'Fira Code', monospace;
    margin-bottom: 24px;
    display: flex;
    align-items: center;
    gap: 12px;
  }

  .sec-label::after {
    content: '';
    flex: 1;
    height: 1px;
    background: linear-gradient(to right, var(--cyan-border), transparent);
  }

  /* ── ABOUT ── */
  .about-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 12px;
    margin-bottom: 20px;
  }

  .about-card {
    background: var(--bg-card);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 18px;
    display: flex;
    align-items: flex-start;
    gap: 14px;
    transition: border-color 0.2s;
  }

  .about-card:hover { border-color: var(--border-hover); }

  .about-icon {
    width: 36px; height: 36px;
    border-radius: 9px;
    display: flex; align-items: center; justify-content: center;
    font-size: 16px;
    flex-shrink: 0;
  }

  .ic-c { background: var(--cyan-dim); }
  .ic-p { background: var(--purple-dim); }
  .ic-g { background: var(--green-dim); }
  .ic-a { background: var(--amber-dim); }

  .about-title { font-size: 12px; font-weight: 700; color: var(--text-primary); margin-bottom: 4px; }
  .about-sub   { font-size: 12px; color: var(--text-muted); line-height: 1.55; }

  /* ── YAML BOX ── */
  .yaml-box {
    background: var(--bg-card);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 22px 28px;
    font-family: 'Fira Code', monospace;
    font-size: 12.5px;
    line-height: 2.1;
  }

  .y-key    { color: #79c0ff; }
  .y-colon  { color: var(--text-muted); }
  .y-str    { color: #a8d8a8; }
  .y-arr    { color: #a5d6ff; }
  .y-ok     { color: var(--green); }

  /* ── SKILLS ── */
  .skill-group { margin-bottom: 20px; }
  .skill-group:last-child { margin-bottom: 0; }

  .skill-group-title {
    font-size: 10px;
    font-weight: 700;
    color: var(--text-muted);
    text-transform: uppercase;
    letter-spacing: 2.5px;
    margin-bottom: 10px;
    font-family: 'Fira Code', monospace;
  }

  .badge-row { display: flex; flex-wrap: wrap; gap: 8px; }

  .badge {
    font-size: 11px;
    font-weight: 600;
    padding: 5px 13px;
    border-radius: 7px;
    letter-spacing: 0.4px;
    font-family: 'Fira Code', monospace;
    display: inline-flex;
    align-items: center;
    gap: 6px;
    border: 1px solid transparent;
  }

  .b-java   { background: var(--java-dim);    color: var(--java);    border-color: rgba(248,152,32,0.25); }
  .b-sel    { background: var(--sel-dim);     color: var(--sel);     border-color: rgba(67,176,42,0.25); }
  .b-api    { background: var(--orange-dim);  color: var(--orange);  border-color: rgba(255,108,55,0.25); }
  .b-rest   { background: rgba(0,150,136,0.1); color: #4db6ac;       border-color: rgba(0,150,136,0.25); }
  .b-perf   { background: var(--red-dim);     color: #ef5350;        border-color: rgba(204,0,0,0.25); }
  .b-ci     { background: var(--jenkins-dim); color: var(--jenkins); border-color: rgba(210,73,57,0.25); }
  .b-db     { background: var(--db-dim);      color: var(--db);      border-color: rgba(68,121,161,0.25); }
  .b-git    { background: rgba(240,246,252,0.05); color: #c9d1d9;    border-color: rgba(240,246,252,0.15); }
  .b-con    { background: var(--purple-dim);  color: var(--purple);  border-color: var(--purple-border); }
  .b-bdd    { background: rgba(35,217,118,0.1); color: #23d96c;      border-color: rgba(35,217,118,0.25); }

  /* ── PROJECTS ── */
  .proj-card {
    background: var(--bg-card);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 26px 28px;
    margin-bottom: 16px;
    position: relative;
    overflow: hidden;
    transition: border-color 0.2s, box-shadow 0.2s;
  }

  .proj-card:last-child { margin-bottom: 0; }
  .proj-card:hover { box-shadow: 0 4px 32px rgba(0,0,0,0.3); }

  .proj-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 2px;
  }

  .proj-card.c-cyan::before  { background: linear-gradient(to right, var(--cyan), transparent 65%); }
  .proj-card.c-purple::before { background: linear-gradient(to right, var(--purple), transparent 65%); }
  .proj-card.c-cyan:hover  { border-color: var(--cyan-border); }
  .proj-card.c-purple:hover { border-color: var(--purple-border); }

  .proj-header {
    display: flex;
    align-items: flex-start;
    justify-content: space-between;
    gap: 16px;
    margin-bottom: 14px;
  }

  .proj-title    { font-size: 16px; font-weight: 700; color: var(--text-primary); margin-bottom: 4px; }
  .proj-subtitle { font-size: 12px; color: var(--text-muted); font-style: italic; }

  .proj-tag {
    font-size: 10px;
    font-weight: 700;
    padding: 4px 12px;
    border-radius: 40px;
    white-space: nowrap;
    letter-spacing: 0.5px;
    flex-shrink: 0;
    font-family: 'Fira Code', monospace;
  }

  .tag-c  { background: var(--cyan-dim);   color: var(--cyan);   border: 1px solid var(--cyan-border); }
  .tag-p  { background: var(--purple-dim); color: var(--purple); border: 1px solid var(--purple-border); }

  .proj-points { list-style: none; margin: 0 0 18px; }

  .proj-points li {
    font-size: 13px;
    color: var(--text-muted);
    padding: 5px 0 5px 18px;
    position: relative;
    line-height: 1.6;
  }

  .proj-points li::before {
    content: '▸';
    position: absolute;
    left: 0;
    top: 6px;
    font-size: 10px;
  }

  .c-cyan  .proj-points li::before { color: var(--cyan); }
  .c-purple .proj-points li::before { color: var(--purple); }

  .proj-divider {
    height: 1px;
    background: var(--border);
    margin-bottom: 16px;
  }

  .tool-chips { display: flex; flex-wrap: wrap; gap: 7px; }

  .tool-chip {
    font-size: 10.5px;
    padding: 4px 10px;
    border-radius: 6px;
    background: #0d1117;
    color: var(--text-muted);
    border: 1px solid var(--border);
    font-family: 'Fira Code', monospace;
    letter-spacing: 0.3px;
  }

  /* ── CERT ── */
  .cert-card {
    background: var(--bg-card);
    border: 1px solid var(--border);
    border-radius: 14px;
    padding: 24px 28px;
    display: flex;
    align-items: center;
    gap: 22px;
    transition: border-color 0.2s;
  }

  .cert-card:hover { border-color: var(--cyan-border); }

  .cert-icon-wrap {
    width: 54px; height: 54px;
    border-radius: 14px;
    background: linear-gradient(135deg, var(--cyan-dim), var(--purple-dim));
    border: 1px solid var(--cyan-border);
    display: flex; align-items: center; justify-content: center;
    font-size: 24px;
    flex-shrink: 0;
  }

  .cert-name   { font-size: 15px; font-weight: 700; color: var(--text-primary); margin-bottom: 4px; }
  .cert-org    { font-size: 13px; color: var(--text-muted); }
  .cert-domain {
    font-size: 11px;
    color: var(--cyan);
    font-family: 'Fira Code', monospace;
    margin-top: 8px;
    display: flex; align-items: center; gap: 6px;
  }

  .cert-domain::before { content: '→'; }

  /* ── QUOTES ── */
  .quote-block {
    background: var(--bg-card);
    border-radius: 12px;
    padding: 22px 26px;
    margin-bottom: 14px;
    border: 1px solid var(--border);
    border-left: 3px solid var(--cyan);
    border-radius: 0 12px 12px 0;
  }

  .quote-block.purple { border-left-color: var(--purple); }
  .quote-block:last-child { margin-bottom: 0; }

  .quote-text   { font-size: 13.5px; color: var(--text-secondary); font-style: italic; line-height: 1.75; margin-bottom: 10px; }
  .quote-author { font-size: 11px; color: var(--cyan); font-family: 'Fira Code', monospace; font-weight: 600; }
  .quote-block.purple .quote-author { color: var(--purple); }

  /* ── CONNECT ── */
  .connect-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 12px;
  }

  .connect-btn {
    background: var(--bg-card);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 20px 16px;
    text-align: center;
    text-decoration: none;
    display: block;
    transition: border-color 0.2s, background 0.2s, transform 0.15s;
    cursor: pointer;
  }

  .connect-btn:hover {
    border-color: var(--cyan-border);
    background: rgba(0,217,255,0.04);
    transform: translateY(-2px);
  }

  .connect-icon  { font-size: 22px; margin-bottom: 10px; }
  .connect-label { font-size: 12px; font-weight: 700; color: var(--text-primary); margin-bottom: 4px; }
  .connect-sub   { font-size: 10.5px; color: var(--text-muted); font-family: 'Fira Code', monospace; word-break: break-all; }

  /* ── FOOTER ── */
  .footer {
    padding: 32px 40px 36px;
    text-align: center;
    border-top: 1px solid var(--border);
    background: var(--bg-card);
  }

  .footer-bar {
    width: 60px; height: 2px;
    background: linear-gradient(to right, transparent, var(--cyan), transparent);
    margin: 0 auto 16px;
    border-radius: 2px;
  }

  .footer-text {
    font-size: 11px;
    color: var(--text-faint);
    font-family: 'Fira Code', monospace;
    letter-spacing: 1px;
  }

  .footer-text span { color: var(--cyan); }

  /* ── RESPONSIVE ── */
  @media (max-width: 600px) {
    body { padding: 12px 8px 60px; }
    .hero { padding: 40px 20px 36px; }
    .section { padding: 28px 20px; }
    .hero-name { font-size: 30px; }
    .about-grid { grid-template-columns: 1fr; }
    .connect-grid { grid-template-columns: 1fr; }
    .proj-header { flex-direction: column; align-items: flex-start; gap: 8px; }
    .footer { padding: 24px 20px 28px; }
  }
</style>
</head>
<body>
<div class="page">
<div class="readme">

  <!-- ── HERO ── -->
  <div class="hero">
    <div class="hero-tag">✦ Portfolio · Open to Work ✦</div>
    <div class="hero-name">Poornimaa Shri <span class="accent">V K</span></div>
    <div class="hero-role">$ QA Automation Engineer<span class="cursor">_</span></div>
    <div class="hero-pills">
      <span class="pill pill-c">🔍 Test Automation</span>
      <span class="pill pill-p">⚡ API Testing</span>
      <span class="pill pill-g">🚀 CI/CD · Agile</span>
    </div>
  </div>

  <!-- ── ABOUT ── -->
  <div class="section">
    <div class="sec-label">01 · About Me</div>
    <div class="about-grid">
      <div class="about-card">
        <div class="about-icon ic-c">🎯</div>
        <div>
          <div class="about-title">Mission</div>
          <div class="about-sub">Building reliable automation frameworks that catch defects before they reach users</div>
        </div>
      </div>
      <div class="about-card">
        <div class="about-icon ic-p">📐</div>
        <div>
          <div class="about-title">Approach</div>
          <div class="about-sub">Shift-left testing mindset — quality baked in from day one, not bolted on at the end</div>
        </div>
      </div>
      <div class="about-card">
        <div class="about-icon ic-g">🌱</div>
        <div>
          <div class="about-title">Learning</div>
          <div class="about-sub">Deepening expertise in Selenium, REST Assured, BDD, and Jenkins CI/CD pipelines</div>
        </div>
      </div>
      <div class="about-card">
        <div class="about-icon ic-a">💼</div>
        <div>
          <div class="about-title">Status</div>
          <div class="about-sub">Actively seeking QA/SDET internships &amp; entry-level roles — let's connect!</div>
        </div>
      </div>
    </div>

    <div class="yaml-box">
      <span class="y-key">name</span>        <span class="y-colon">:</span> <span class="y-str">"Poornimaa Shri V K"</span><br>
      <span class="y-key">role</span>        <span class="y-colon">:</span> <span class="y-str">"QA Automation Engineer"</span><br>
      <span class="y-key">frameworks</span>  <span class="y-colon">:</span> <span class="y-arr">[ POM, Data-Driven, BDD ]</span><br>
      <span class="y-key">methodology</span> <span class="y-colon">:</span> <span class="y-arr">[ Agile, SDLC, STLC ]</span><br>
      <span class="y-key">status</span>      <span class="y-colon">:</span> <span class="y-ok">"Open to Work ✅"</span>
    </div>
  </div>

  <!-- ── SKILLS ── -->
  <div class="section">
    <div class="sec-label">02 · Technical Skills</div>

    <div class="skill-group">
      <div class="skill-group-title">// Languages</div>
      <div class="badge-row">
        <span class="badge b-java">☕ Java</span>
        <span class="badge b-git">© C</span>
      </div>
    </div>

    <div class="skill-group">
      <div class="skill-group-title">// Automation Testing</div>
      <div class="badge-row">
        <span class="badge b-sel">🤖 Selenium WebDriver</span>
        <span class="badge b-api">🧪 TestNG</span>
        <span class="badge b-bdd">🥒 Cucumber BDD</span>
      </div>
    </div>

    <div class="skill-group">
      <div class="skill-group-title">// API Testing</div>
      <div class="badge-row">
        <span class="badge b-rest">🔌 REST Assured</span>
        <span class="badge b-api">📮 Postman</span>
      </div>
    </div>

    <div class="skill-group">
      <div class="skill-group-title">// Performance &amp; CI/CD</div>
      <div class="badge-row">
        <span class="badge b-perf">⚡ Apache JMeter</span>
        <span class="badge b-ci">🔧 Jenkins</span>
      </div>
    </div>

    <div class="skill-group">
      <div class="skill-group-title">// Database &amp; Version Control</div>
      <div class="badge-row">
        <span class="badge b-db">🗄️ MySQL</span>
        <span class="badge b-git">🐙 Git</span>
        <span class="badge b-git">⚡ GitHub</span>
      </div>
    </div>

    <div class="skill-group">
      <div class="skill-group-title">// Testing Expertise</div>
      <div class="badge-row">
        <span class="badge b-con">Automation Testing</span>
        <span class="badge b-con">API Testing</span>
        <span class="badge b-con">Regression Testing</span>
        <span class="badge b-con">Functional Testing</span>
        <span class="badge b-con">Smoke Testing</span>
        <span class="badge b-con">SDLC · STLC</span>
        <span class="badge b-con">Agile Methodology</span>
      </div>
    </div>
  </div>

  <!-- ── PROJECTS ── -->
  <div class="section">
    <div class="sec-label">03 · Projects</div>

    <div class="proj-card c-cyan">
      <div class="proj-header">
        <div>
          <div class="proj-title">🛒 Zenvora Living</div>
          <div class="proj-subtitle">End-to-End E-Commerce Testing Project</div>
        </div>
        <span class="proj-tag tag-c">E-Commerce QA</span>
      </div>
      <ul class="proj-points">
        <li>Automated critical user journeys — browse → cart → checkout → order — using Selenium WebDriver + TestNG with Page Object Model architecture</li>
        <li>Validated REST APIs for product catalog, cart operations and order lifecycle using REST Assured and Postman collections</li>
        <li>Built regression &amp; smoke test suites for rapid post-deployment confidence validation</li>
        <li>Verified backend data integrity via MySQL queries after every critical transaction</li>
        <li>Benchmarked concurrent user performance under load using Apache JMeter</li>
        <li>Integrated full test execution into Jenkins CI/CD pipeline for automated build-trigger runs</li>
      </ul>
      <div class="proj-divider"></div>
      <div class="tool-chips">
        <span class="tool-chip">Java</span>
        <span class="tool-chip">Selenium WebDriver</span>
        <span class="tool-chip">TestNG</span>
        <span class="tool-chip">REST Assured</span>
        <span class="tool-chip">Postman</span>
        <span class="tool-chip">MySQL</span>
        <span class="tool-chip">Apache JMeter</span>
        <span class="tool-chip">Jenkins</span>
      </div>
    </div>

    <div class="proj-card c-purple">
      <div class="proj-header">
        <div>
          <div class="proj-title">🎪 Occasio</div>
          <div class="proj-subtitle">Multi-Role Event Management Testing Project</div>
        </div>
        <span class="proj-tag tag-p">BDD · Multi-Role</span>
      </div>
      <ul class="proj-points">
        <li>Implemented Behavior-Driven Development (BDD) using Cucumber with Gherkin feature files — readable by both business and technical stakeholders</li>
        <li>Validated Role-Based Access Control (RBAC) workflows across Admin, Organizer, and Attendee personas end-to-end</li>
        <li>Executed API contract testing using Postman with automated environment switching across staging and production</li>
        <li>Confirmed backend data consistency via MySQL queries post every critical booking and event operation</li>
        <li>Integrated automated test suite into Jenkins pipeline for continuous delivery validation</li>
      </ul>
      <div class="proj-divider"></div>
      <div class="tool-chips">
        <span class="tool-chip">Java</span>
        <span class="tool-chip">Selenium WebDriver</span>
        <span class="tool-chip">TestNG</span>
        <span class="tool-chip">Cucumber BDD</span>
        <span class="tool-chip">Postman</span>
        <span class="tool-chip">MySQL</span>
        <span class="tool-chip">Apache JMeter</span>
        <span class="tool-chip">Jenkins</span>
      </div>
    </div>
  </div>

  <!-- ── CERTIFICATION ── -->
  <div class="section">
    <div class="sec-label">04 · Certification</div>
    <div class="cert-card">
      <div class="cert-icon-wrap">🏅</div>
      <div>
        <div class="cert-name">Software Testing</div>
        <div class="cert-org">Pumo Technovation</div>
        <div class="cert-domain">Manual &amp; Automation Testing · Quality Assurance</div>
      </div>
    </div>
  </div>

  <!-- ── PHILOSOPHY ── -->
  <div class="section">
    <div class="sec-label">05 · QA Philosophy</div>
    <div class="quote-block">
      <div class="quote-text">"Quality is never an accident; it is always the result of intelligent effort."</div>
      <div class="quote-author">— John Ruskin</div>
    </div>
    <div class="quote-block purple">
      <div class="quote-text">"Testing leads to failure, and failure leads to understanding."</div>
      <div class="quote-author">— Burt Rutan</div>
    </div>
  </div>

  <!-- ── CONNECT ── -->
  <div class="section">
    <div class="sec-label">06 · Connect With Me</div>
    <div class="connect-grid">
      <a href="https://www.linkedin.com/in/poornimaa-shri-vk" target="_blank" class="connect-btn">
        <div class="connect-icon">💼</div>
        <div class="connect-label">LinkedIn</div>
        <div class="connect-sub">poornimaa-shri-vk</div>
      </a>
      <a href="mailto:poornimaashrivk@gmail.com" class="connect-btn">
        <div class="connect-icon">📧</div>
        <div class="connect-label">Email</div>
        <div class="connect-sub">poornimaashrivk@gmail.com</div>
      </a>
      <a href="https://github.com/poornimaa-shri-vk" target="_blank" class="connect-btn">
        <div class="connect-icon">🐙</div>
        <div class="connect-label">GitHub</div>
        <div class="connect-sub">@poornimaa-shri-vk</div>
      </a>
    </div>
  </div>

  <!-- ── FOOTER ── -->
  <div class="footer">
    <div class="footer-bar"></div>
    <div class="footer-text">✦ <span>Poornimaa Shri V K</span> · Building Quality, One Test at a Time ✦</div>
  </div>

</div>
</div>
</body>
</html>
