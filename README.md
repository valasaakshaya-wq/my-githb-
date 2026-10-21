<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>VALASA AKSHAYA | Portfolio</title>
<meta name="description" content="Portfolio of Valasa Akshaya, a B.Tech CSE AI and ML student.">
<style>
:root {
  --bg: #101010;
  --panel: #191919;
  --text: #f3f0f5;
  --muted: #aaa6b2;
  --blue: #8ebcff;
  --line: #303036;
}
* { box-sizing: border-box; }
html { scroll-behavior: smooth; scroll-padding-top: 85px; }
body {
  margin: 0;
  color: var(--text);
  background:
    radial-gradient(ellipse at 15% 15%, #172337 0, transparent 35%),
    radial-gradient(ellipse at 85% 40%, #1b1c2b 0, transparent 30%),
    var(--bg);
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.7;
}
a { color: inherit; }
nav {
  position: sticky;
  top: 12px;
  z-index: 10;
  width: fit-content;
  max-width: 95%;
  margin: 12px auto;
  padding: 9px 15px;
  display: flex;
  gap: 18px;
  justify-content: center;
  flex-wrap: wrap;
  background: #222222eF;
  border: 1px solid #393940;
  border-radius: 40px;
  backdrop-filter: blur(12px);
}
nav a {
  font-size: 12px;
  color: #ddd;
  text-decoration: none;
}
nav a:hover { color: var(--blue); }
section {
  width: min(1000px, 90%);
  margin: auto;
  padding: 85px 0;
}
.hero {
  min-height: 80vh;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
}
.eyebrow {
  color: var(--blue);
  letter-spacing: 4px;
  font-size: 10px;
  text-transform: uppercase;
}
h1 {
  font-family: Georgia, serif;
  font-weight: normal;
  font-size: clamp(42px, 8vw, 86px);
  line-height: 1.1;
  letter-spacing: -3px;
  margin: 18px 0;
}
h1 span, h2 span {
  font-family: Georgia, serif;
  font-style: italic;
  color: var(--blue);
}
.intro { color: var(--muted); max-width: 580px; }
.actions { display: flex; gap: 12px; flex-wrap: wrap; margin-top: 22px; }
.btn {
  display: inline-block;
  padding: 10px 19px;
  border-radius: 28px;
  background: #f3f0f5;
  color: #171717;
  text-decoration: none;
  font-size: 13px;
}
.btn.secondary { background: transparent; color: white; border: 1px solid #555; }
h2 {
  font-family: Georgia, serif;
  font-size: clamp(32px, 5vw, 48px);
  line-height: 1.2;
  font-weight: normal;
  margin: 8px 0 20px;
}
.sub { color: var(--muted); font-size: 14px; }
.grid {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 18px;
  margin-top: 30px;
}
.card {
  background: linear-gradient(145deg, #20232b, #171719);
  border: 1px solid var(--line);
  border-radius: 17px;
  padding: 24px;
  transition: transform .2s, border-color .2s;
}
.card:hover { transform: translateY(-4px); border-color: #637fa6; }
.card h3 { margin-top: 0; }
.card p { color: var(--muted); font-size: 14px; }
.pill {
  display: inline-block;
  padding: 5px 11px;
  margin: 4px;
  border: 1px solid #363640;
  border-radius: 30px;
  color: #d8d5df;
  font-size: 12px;
}
.skills { margin-top: 20px; }
.timeline { border-left: 1px solid #53515e; padding-left: 22px; }
.timeline .card { margin-bottom: 15px; }
.stats {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 12px;
  margin-top: 25px;
}
.stat { padding: 18px; border-top: 1px solid #444; }
.stat strong { display: block; font: 32px Georgia, serif; }
.stat small { color: var(--muted); font-size: 10px; }
.contact { text-align: center; }
footer {
  border-top: 1px solid var(--line);
  text-align: center;
  padding: 25px;
  color: var(--muted);
  font-size: 12px;
}
@media(max-width:600px) {
  nav { gap: 12px; }
  .grid { grid-template-columns: 1fr; }
  section { padding: 55px 0; }
  .stats { grid-template-columns: 1fr; }
  h1 { letter-spacing: -1.5px; }
}
</style>
</head>
<body>

<nav>
  <a href="#home">Home</a>
  <a href="#work">Work</a>
  <a href="#certificates">Certificates</a>
  <a href="#about">About</a>
  <a href="#contact">Say Hi ↗</a>
</nav>

<section class="hero" id="home">
  <div class="eyebrow">Portfolio · 2026</div>
  <h1>VALASA<br><span>AKSHAYA</span></h1>
  <p class="intro">
    B.Tech 3rd Year · Computer Science & Engineering (AI & ML)<br>
    A curious learner exploring artificial intelligence,
    machine learning and web development.
  </p>
  <div class="actions">
    <a class="btn" href="#work">See my work ↘</a>
    <a class="btn secondary" href="#contact">Reach out ↗</a>
  </div>
  <p class="eyebrow" style="margin-top:55px">Scroll to explore ↓</p>
</section>

<section id="work">
  <div class="eyebrow">Selected work</div>
  <h2>Featured <span>projects</span></h2>
  <p class="sub">Projects and ideas from my learning journey.</p>
  <div class="grid">
    <article class="card">
      <div class="eyebrow">AI / ML</div>
      <h3>Fake News Detector</h3>
      <p>An AI/ML project focused on classifying news and exploring how technology can help identify misleading information.</p>
      <span class="pill">Artificial Intelligence</span>
      <span class="pill">Machine Learning</span>
    </article>
    <article class="card">
      <div class="eyebrow">Python</div>
      <h3>Hangman Game</h3>
      <p>A word-guessing game created to practise Python programming, conditions, loops and user input.</p>
      <span class="pill">Python</span>
      <span class="pill">Game Logic</span>
    </article>
    <article class="card">
      <div class="eyebrow">Cybersecurity</div>
      <h3>SentinelID</h3>
      <p>A zero-trust identity and threat intelligence platform concept exploring risk-based authentication.</p>
      <span class="pill">Cybersecurity</span>
      <span class="pill">AI</span>
    </article>
    <article class="card">
      <div class="eyebrow">Personal project</div>
      <h3>My Portfolio</h3>
      <p>A personal website built with HTML and CSS and published online using GitHub Pages.</p>
      <span class="pill">HTML</span>
      <span class="pill">CSS</span>
      <span class="pill">GitHub</span>
    </article>
  </div>
</section>

<section id="certificates">
  <div class="eyebrow">Learning journey</div>
  <h2>My <span>certifications</span></h2>
  <p class="sub">Add your verified course certificates below.</p>
  <div class="timeline">
    <article class="card">
      <h3>IBM SkillsBuild</h3>
      <p>AI and professional skills learning.</p>
    </article>
    <article class="card">
      <h3>IBM / Watson Studio</h3>
      <p>AI and AutoAI learning activities.</p>
    </article>
    <article class="card">
      <h3>Data Analyst — Novitech</h3>
      <p>Data analytics learning and training.</p>
    </article>
  </div>
  <p class="sub">Only list courses you completed, and add certificate links when available.</p>
</section>

<section id="about">
  <div class="eyebrow">A little about me</div>
  <h2>Learning today.<br><span>Building tomorrow.</span></h2>
  <p class="sub">
    I am a third-year B.Tech student in Computer Science
    and Engineering (AI & ML) at Sri Chaitanya Institute
    of Technology and Research, Khammam, Telangana.
    I enjoy learning new technologies and turning ideas
    into practical projects.
  </p>
  <h3>What I am learning</h3>
  <div class="skills">
    <span class="pill">Python</span>
    <span class="pill">Artificial Intelligence</span>
    <span class="pill">Machine Learning</span>
    <span class="pill">HTML & CSS</span>
    <span class="pill">GitHub</span>
    <span class="pill">Data Analytics</span>
  </div>
  <h3 style="margin-top:35px">Education</h3>
  <div class="card">
    <h3>B.Tech — CSE (AI & ML)</h3>
    <p>Sri Chaitanya Institute of Technology and Research</p>
    <p>Khammam, Telangana · Third year</p>
  </div>
  <div class="stats">
    <div class="stat"><strong>AI & ML</strong><small>MY SPECIALISATION</small></div>
    <div class="stat"><strong>03</strong><small>B.TECH YEAR</small></div>
    <div class="stat"><strong>∞</strong><small>THINGS TO LEARN</small></div>
  </div>
</section>

<section id="contact" class="contact">
  <div class="eyebrow">Let's connect</div>
  <h2>Have an idea?<br><span>Say hello.</span></h2>
  <p class="sub">I am interested in learning, collaboration and project opportunities.</p>
  <div class="actions" style="justify-content:center">
    <a class="btn" href="https://github.com/">GitHub ↗</a>
    <a class="btn secondary" href="https://www.linkedin.com/">LinkedIn ↗</a>
  </div>
  <p class="sub">Replace these links with your own profile URLs.</p>
</section>

<footer>© 2026 VALASA AKSHAYA · Built with HTML & CSS</footer>
</body>
</html>
