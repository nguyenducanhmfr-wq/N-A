<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nguyễn Đức Anh Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Inter',sans-serif}
body{background:#eef3f9;color:#1e293b}
.container{width:1100px;margin:auto}

/* NAV */
nav{display:flex;justify-content:space-between;align-items:center;padding:18px 0}
nav h1{font-size:14px;letter-spacing:2px;color:#0f172a}
nav ul{display:flex;gap:30px;list-style:none}
nav a{text-decoration:none;color:#334155;font-size:14px}
nav a:hover{color:#2563eb}

/* HERO */
.hero{display:flex;justify-content:space-between;align-items:center;margin-top:40px}
.hero-text{width:65%}
.hero-text h2{font-size:40px;margin-bottom:15px}
.hero-text h2 span{color:#2563eb}
.hero-text p{color:#475569;margin-bottom:15px;line-height:1.6}
.tags{display:flex;flex-wrap:wrap;gap:10px;margin:15px 0}
.tag{background:#e0ecff;color:#1d4ed8;padding:6px 12px;border-radius:20px;font-size:12px}
.btn{display:inline-block;background:#2563eb;color:#fff;padding:10px 18px;border-radius:6px;text-decoration:none;font-size:14px;margin-top:10px}
.hero-img{width:30%;background:#fff;padding:15px;border-radius:12px;box-shadow:0 5px 20px rgba(0,0,0,0.08)}
.hero-img img{width:100%;border-radius:10px}
.hero-img p{font-size:12px;color:#64748b;margin-top:8px;text-align:center}

section{margin-top:70px}
section h3{color:#2563eb;margin-bottom:10px}
section p.section-desc{color:#64748b;font-size:14px;margin-bottom:20px}

.card{background:#fff;padding:20px;border-radius:12px;box-shadow:0 5px 20px rgba(0,0,0,0.06);margin-bottom:20px}

.grid-2{display:grid;grid-template-columns:1fr 1fr;gap:20px}
.grid-3{display:grid;grid-template-columns:1fr 1fr 1fr;gap:20px}

.card h4{margin-bottom:8px;font-size:16px}
.card ul{padding-left:18px;font-size:14px;color:#475569}
.card li{margin-bottom:6px}
.small-tags{display:flex;gap:8px;flex-wrap:wrap;margin-top:8px}
.small-tag{background:#e0ecff;color:#1d4ed8;font-size:11px;padding:4px 8px;border-radius:12px}

footer{margin:80px 0 40px;color:#64748b;font-size:13px;text-align:center}

@media(max-width:1100px){.container{width:90%}.hero{flex-direction:column;gap:30px}.hero-text,.hero-img{width:100%}.grid-2,.grid-3{grid-template-columns:1fr}}
</style>
</head>
<body>
<div class="container">

<nav>
<h1>NGUYEN DUC ANH</h1>
<ul>
<li><a href="#">About</a></li>
<li><a href="#">Highlights</a></li>
<li><a href="#">Experience</a></li>
<li><a href="#">Activities</a></li>
<li><a href="#">Skills</a></li>
<li><a href="#">Contact</a></li>
</ul>
</nav>

<div class="hero">
<div class="hero-text">
<h2>Hi, I’m <span>Nguyễn Đức Anh.</span></h2>
<p>An aspiring Marketing staff with an economic and advertising background. I'm a third-year student at Foreign Trade University majoring in International Business.</p>
<p>Business: I enjoy understanding business problems, working with data, and turning insights into clear, practical actions for people and organizations.</p>

<div class="tags">
<span class="tag">Marketing</span>
<span class="tag">International Business</span>
<span class="tag">Market Analysis</span>
<span class="tag">Business Communication</span>
<span class="tag">Online advertising</span>
</div>

<a class="btn">Contact me</a>
<p style="margin-top:10px;color:#475569">Currently seeking an environment to apply analytical skills and proactive energy to help a business scale internationally.</p>
</div>

<div class="hero-img">
<img src="https://via.placeholder.com/300x300" alt="profile">
<p>Nguyễn Đức Anh · Hanoi, Vietnam</p>
</div>
</div>

<section>
<h3>About</h3>
<p class="section-desc">A quick look at who I am, what I’ve built, and the direction I’m heading.</p>

<div class="grid-2">
<div class="card">
<h4>Profile</h4>
<p style="font-size:14px;color:#475569">Hello! I am Nguyễn Đức Anh, a third-year International Business student at Foreign Trade University (FTU). I am increasingly interested in financial markets, securities analysis and asset management.</p>
</div>

<div class="card">
<h4>Education</h4>
<p style="font-size:14px;color:#475569"><b>Foreign Trade University (FTU)</b><br>International Business – Third-year student<br>Hanoi, Vietnam</p>
<br>
<h4>What I’m looking for</h4>
<ul>
<li>A growth environment with strong mentoring and high standards.</li>
<li>Marketing / market intelligence / business analytic roles.</li>
<li>Opportunities to support international scaling strategies.</li>
</ul>
</div>
</div>
</section>

<section>
<h3>Highlights</h3>
<p class="section-desc">Achievements that reflect discipline, competitiveness, and execution.</p>
<div class="card">
<ul>
<li><b>Top 40 – Stockwise 2025 Competition</b></li>
<li>Third prize winner of BUSINESS FAIR & BUSINESS FRONTLINE CONTEST 2025.</li>
</ul>
</div>
</section>

<section>
<h3>Experience</h3>
<p class="section-desc">Hands-on experience in finance, research, reporting, and client support.</p>
<div class="card">
<h4>Intern, Securities Trading Department – Mirae Asset Securities</h4>
<div class="small-tags">
<span class="small-tag">Market Analysis</span>
<span class="small-tag">Client Management</span>
<span class="small-tag">Research</span>
<span class="small-tag">Reporting</span>
</div>
<br>
<ul>
<li>Monitored daily stock movements and synthesized financial news.</li>
<li>Assisted in research and investment evaluation reports.</li>
<li>Supported client onboarding and account management.</li>
<li>Conducted fundamental research on listed companies.</li>
</ul>
</div>
</section>

<!-- Activities section intentionally removed as requested -->

<section>
<h3>Skills & Tools</h3>
<div class="grid-3">
<div class="card">
<h4>Business skills</h4>
<ul>
<li>Strategic problem-solving</li>
<li>Stakeholder collaboration</li>
<li>Professional business communication</li>
<li>Market/consumer understanding</li>
</ul>
</div>

<div class="card">
<h4>Technical tools</h4>
<ul>
<li>Microsoft Word</li>
<li>Microsoft Excel</li>
<li>Microsoft PowerPoint</li>
<li>Adobe Photoshop</li>
<li>Adobe Illustrator</li>
<li>Canva Premium</li>
</ul>
</div>

<div class="card">
<h4>Languages</h4>
<ul>
<li>Vietnamese – Native</li>
<li>English – Fluent</li>
<li>Chinese – Basic</li>
</ul>
</div>
</div>
</section>

<section>
<h3>Contact</h3>
<div class="card">
<p>Email: nguyenducanh10a4@email.com</p>
<p>Phone: 0522348618</p>
<p>Location: Hanoi, Vietnam</p>
</div>
</section>

<footer>
© 2026 Nguyễn Đức Anh. All Rights Reserved.
</footer>

</div>
</body>
</html>

</html>

