<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Lissa Josephine | Digital Marketing Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <!-- NAVBAR -->
  <header>
    <nav class="navbar">
      <h2 class="logo">LJ</h2>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#case-studies">Case Studies</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- HOME -->
  <section id="home" class="hero">
    <h1>Hi, I’m <span>Lissa Josephine</span></h1>
    <h3>Digital Marketing & Growth Executive</h3>
    <p>
      Driving admissions growth through performance marketing, CRM automation,
      creatives, and direct lead conversion.
    </p>

    <div class="stats">
      <div><strong>8+</strong><br/>Months Experience</div>
      <div><strong>6</strong><br/>Vendors Managed</div>
      <div><strong>30%</strong><br/>PGDM Weekend</div>
      <div><strong>43%</strong><br/>Executive Diploma</div>
    </div>

    <a href="#case-studies" class="btn">View My Work</a>
  </section>

  <!-- ABOUT -->
  <section id="about">
    <h2>About Me</h2>
    <p>
      I am a results-driven Digital Marketing professional currently working at
      <strong>LIBA Admissions</strong>. I manage multi-vendor campaigns, build
      landing pages using HTML & CSS, automate WhatsApp journeys, and personally
      convert leads into enrolled students.
    </p>
    <p>
      I enjoy working at the intersection of performance marketing, CRM systems,
      automation, and creative communication.
    </p>
  </section>

  <!-- EXPERIENCE -->
  <section id="experience">
    <h2>Experience</h2>

    <div class="card">
      <h3>Digital Marketing Executive – LIBA Admissions</h3>
      <ul>
        <li>Managed 6 vendors (SRV Media, InsideIIM, Digital Crest, Pagalguy, KollegeApply, Career Launcher)</li>
        <li>Built 4 landing pages using HTML + CSS in LeadSquared CRM</li>
        <li>Onboarded AiSensy for WhatsApp automation</li>
        <li>Handled marketing budget & invoice processing</li>
        <li>Achieved 30% & 43% conversion through direct calling</li>
      </ul>
    </div>

    <div class="card">
      <h3>Talent Acquisition Intern – Equitas Small Finance Bank</h3>
      <ul>
        <li>Designed recruitment posters & creatives</li>
        <li>Handled calling & candidate engagement</li>
        <li>Applied digital marketing principles to hiring campaigns</li>
      </ul>
    </div>
  </section>

  <!-- CASE STUDIES -->
  <section id="case-studies">
    <h2>Case Studies</h2>

    <div class="grid">
      <div class="case-card">
        <h4>PGDM Weekend – Conversion Recovery</h4>
        <p>Last-minute calling + WhatsApp follow-ups</p>
        <span>Result: 30% Conversion</span>
      </div>

      <div class="case-card">
        <h4>Executive Diploma Campaign</h4>
        <p>Content + calling-based engagement</p>
        <span>Result: 43% Conversion</span>
      </div>

      <div class="case-card">
        <h4>Landing Pages – LeadSquared</h4>
        <p>HTML + CSS landing pages</p>
        <span>Lead Optimization</span>
      </div>

      <div class="case-card">
        <h4>WhatsApp Automation – AiSensy</h4>
        <p>Automated lead nurturing flows</p>
        <span>Improved response rate</span>
      </div>
    </div>
  </section>

  <!-- SKILLS -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <span>Performance Marketing</span>
      <span>LeadSquared CRM</span>
      <span>AiSensy</span>
      <span>HTML</span>
      <span>CSS</span>
      <span>Poster & Video Creation</span>
      <span>Email & WhatsApp Marketing</span>
      <span>Social Media Management</span>
      <span>Budget & Invoice Handling</span>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <h2>Contact</h2>
    <p>Email: <strong>yourmail@gmail.com</strong></p>
    <p>LinkedIn: <strong>linkedin.com/in/yourprofile</strong></p>
    <p>WhatsApp: <strong>+91 XXXXX XXXXX</strong></p>
  </section>

  <footer>
    <p>© 2026 Lissa Josephine | Digital Marketing Portfolio</p>
  </footer>

</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Segoe UI", sans-serif;
}

body {
  background: #f9f9f9;
  color: #222;
  line-height: 1.6;
}

/* NAVBAR */
header {
  background: #111;
  padding: 15px 40px;
  position: sticky;
  top: 0;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  color: #fff;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
}

.nav-links a {
  color: #fff;
  text-decoration: none;
}

/* HERO */
.hero {
  padding: 80px 40px;
  background: linear-gradient(to right, #111, #333);
  color: #fff;
  text-align: center;
}

.hero span {
  color: #00ffcc;
}

.stats {
  display: flex;
  justify-content: center;
  gap: 30px;
  margin: 30px 0;
}

.btn {
  background: #00ffcc;
  padding: 12px 25px;
  text-decoration: none;
  color: #000;
  border-radius: 5px;
  font-weight: bold;
}

/* SECTIONS */
section {
  padding: 60px 40px;
}

h2 {
  margin-bottom: 20px;
}

/* CARDS */
.card {
  background: #fff;
  padding: 25px;
  margin-bottom: 20px;
  border-radius: 8px;
}

/* CASE STUDIES */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

.case-card {
  background: #fff;
  padding: 20px;
  border-radius: 8px;
}

/* SKILLS */
.skills {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.skills span {
  background: #e0e0e0;
  padding: 8px 15px;
  border-radius: 20px;
}

/* FOOTER */
footer {
  background: #111;
  color: #fff;
  text-align: center;
  padding: 20px;
}

