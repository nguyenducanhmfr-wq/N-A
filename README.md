<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio | Finance Student</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Poppins', sans-serif; }
        body { background: #0f172a; color: #f1f5f9; line-height: 1.6; }
        a { color: #38bdf8; text-decoration: none; }
        header { background: linear-gradient(135deg,#1e293b,#0f172a); padding: 100px 20px; text-align: center; }
        header h1 { font-size: 48px; font-weight: 700; }
        header p { font-size: 20px; color: #94a3b8; margin-top: 15px; }
        nav { margin-top: 25px; }
        nav a { margin: 0 15px; font-weight: 500; }
        section { padding: 70px 20px; max-width: 1000px; margin: auto; }
        h2 { font-size: 32px; margin-bottom: 30px; border-bottom: 2px solid #334155; padding-bottom: 10px; }
        .card { background: #1e293b; padding: 25px; border-radius: 16px; margin-bottom: 20px; transition: 0.3s; }
        .card:hover { transform: translateY(-5px); box-shadow: 0 10px 25px rgba(0,0,0,0.3); }
        .card h3 { font-size: 22px; margin-bottom: 10px; }
        .card span { font-size: 14px; color: #94a3b8; }
        .skills-list { display: flex; flex-wrap: wrap; gap: 10px; }
        .skill { background: #334155; padding: 8px 14px; border-radius: 20px; font-size: 14px; }
        .projects { display: grid; grid-template-columns: repeat(auto-fit,minmax(250px,1fr)); gap: 20px; }
        footer { text-align: center; padding: 40px 20px; background: #1e293b; margin-top: 50px; font-size: 14px; color: #94a3b8; }
        @media(max-width:768px){ header h1{font-size:36px;} h2{font-size:26px;} }
    </style>
</head>
<body>

<header>
    <h1>Your Name</h1>
    <p>Finance Student | Investment Enthusiast | Future Analyst</p>
    <nav>
        <a href="#about">About</a>
        <a href="#highlights">Highlights</a>
        <a href="#experience">Experience</a>
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="about">
    <h2>About Me</h2>
    <div class="card">
        <p>I am a finance student with a strong interest in equity research, financial analysis, and investment strategy. I am passionate about understanding market movements and building data-driven investment insights.</p>
    </div>
</section>

<section id="highlights">
    <h2>Highlights</h2>
    <div class="card">
        <h3>Top 40 cuộc thi Stockwise 2025</h3>
        <span>National Investment Competition</span>
    </div>
</section>

<section id="experience">
    <h2>Experience</h2>
    <div class="card">
        <h3>Mirae Asset Securities</h3>
        <span>Investment Intern | 2025</span>
        <p>
            • Supported equity research and market analysis.<br>
            • Assisted in preparing investment reports and valuation models.<br>
            • Conducted financial statement analysis using Excel.
        </p>
    </div>
</section>

<section id="projects">
    <h2>Projects</h2>
    <div class="projects">
        <div class="card">
            <h3>Equity Valuation Project</h3>
            <p>Built a DCF valuation model and conducted sensitivity analysis for a listed company.</p>
        </div>
        <div class="card">
            <h3>Market Research Report</h3>
            <p>Analyzed industry trends and macroeconomic indicators impacting the stock market.</p>
        </div>
        <div class="card">
            <h3>Portfolio Simulation</h3>
            <p>Constructed and tracked a simulated investment portfolio using risk-return metrics.</p>
        </div>
    </div>
</section>

<section id="skills">
    <h2>Skills</h2>
    <div class="skills-list">
        <div class="skill">Financial Analysis</div>
        <div class="skill">Equity Research</div>
        <div class="skill">DCF Valuation</div>
        <div class="skill">Excel</div>
        <div class="skill">PowerPoint</div>
        <div class="skill">Data Analysis</div>
        <div class="skill">Market Research</div>
    </div>
</section>

<section id="contact">
    <h2>Contact</h2>
    <div class="card">
        <p>Email: your.email@example.com</p>
        <p>LinkedIn: linkedin.com/in/yourprofile</p>
        <p>Phone: +84 xxx xxx xxx</p>
    </div>
</section>

<footer>
    © 2026 Your Name. All Rights Reserved.
</footer>

</body>
</html>
