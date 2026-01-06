<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Muhammad Jahanzeb Memon - DevOps Engineer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: #fff;
            overflow-x: hidden;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            text-align: center;
            padding: 60px 20px;
            background: rgba(0, 0, 0, 0.2);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            margin-bottom: 40px;
            animation: fadeIn 1s ease-in;
        }

        h1 {
            font-size: 3em;
            margin-bottom: 10px;
            background: linear-gradient(45deg, #FFD700, #FFA500);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            animation: glow 2s ease-in-out infinite alternate;
        }

        @keyframes glow {
            from { filter: drop-shadow(0 0 5px #FFD700); }
            to { filter: drop-shadow(0 0 20px #FFA500); }
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        .subtitle {
            font-size: 1.5em;
            color: #FFD700;
            margin-top: 10px;
        }

        .section {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(10px);
            border-radius: 15px;
            padding: 30px;
            margin-bottom: 30px;
            border: 1px solid rgba(255, 255, 255, 0.2);
            animation: slideIn 0.8s ease-out;
        }

        @keyframes slideIn {
            from { opacity: 0; transform: translateX(-30px); }
            to { opacity: 1; transform: translateX(0); }
        }

        h2 {
            font-size: 2em;
            margin-bottom: 20px;
            border-bottom: 3px solid #FFD700;
            padding-bottom: 10px;
        }

        .about-list {
            list-style: none;
            padding-left: 0;
        }

        .about-list li {
            padding: 10px 0;
            font-size: 1.1em;
            display: flex;
            align-items: center;
        }

        .about-list li:before {
            content: "▹";
            color: #FFD700;
            font-size: 1.5em;
            margin-right: 15px;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
            margin-top: 20px;
        }

        .skill-card {
            background: rgba(255, 255, 255, 0.15);
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .skill-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 30px rgba(255, 215, 0, 0.3);
            background: rgba(255, 255, 255, 0.2);
        }

        .skill-icon {
            font-size: 2.5em;
            margin-bottom: 10px;
        }

        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .stat-card {
            background: linear-gradient(135deg, rgba(255, 255, 255, 0.15), rgba(255, 255, 255, 0.05));
            padding: 30px;
            border-radius: 15px;
            text-align: center;
            border: 1px solid rgba(255, 255, 255, 0.2);
        }

        .stat-number {
            font-size: 3em;
            font-weight: bold;
            color: #FFD700;
            margin-bottom: 10px;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }

        .social-btn {
            background: linear-gradient(45deg, #FFD700, #FFA500);
            color: #333;
            padding: 15px 30px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            transition: all 0.3s ease;
            box-shadow: 0 5px 15px rgba(255, 215, 0, 0.3);
        }

        .social-btn:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(255, 215, 0, 0.5);
        }

        .workflow-diagram {
            background: rgba(0, 0, 0, 0.3);
            padding: 30px;
            border-radius: 15px;
            margin-top: 20px;
            text-align: center;
        }

        .workflow-steps {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 20px;
        }

        .workflow-step {
            flex: 1;
            min-width: 150px;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 10px;
            border: 2px dashed #FFD700;
        }

        .workflow-step h3 {
            color: #FFD700;
            margin-bottom: 10px;
        }

        footer {
            text-align: center;
            padding: 30px;
            background: rgba(0, 0, 0, 0.2);
            border-radius: 15px;
            margin-top: 40px;
        }

        @media (max-width: 768px) {
            h1 { font-size: 2em; }
            .subtitle { font-size: 1.2em; }
            .skills-grid { grid-template-columns: repeat(auto-fit, minmax(120px, 1fr)); }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>👋 Muhammad Jahanzeb Memon</h1>
            <p class="subtitle">🚀 DevOps Engineer | Cloud Architect | Infrastructure Specialist</p>
        </header>

        <div class="section">
            <h2>💡 About Me</h2>
            <ul class="about-list">
                <li>🌍 Passionate about Open Source Contributions</li>
                <li>🧑‍💻 Expertise in Web, Mobile, and Cloud Engineering</li>
                <li>☁️ Specialized in Cloud-Based and Scalable Architectures</li>
                <li>💡 Enjoy Over-Engineering and Optimizing Tech Stacks</li>
                <li>🔧 Currently enhancing skills in Kubernetes and containerization</li>
                <li>💬 Let's talk about Software Development, Cloud Engineering, or anything tech!</li>
            </ul>
        </div>

        <div class="section">
            <h2>🛠️ My DevOps Toolkit</h2>
            <div class="skills-grid">
                <div class="skill-card">
                    <div class="skill-icon">☁️</div>
                    <strong>AWS</strong>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">🐳</div>
                    <strong>Docker</strong>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">⎈</div>
                    <strong>Kubernetes</strong>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">🐍</div>
                    <strong>Python</strong>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">📜</div>
                    <strong>JavaScript</strong>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">⚛️</div>
                    <strong>React</strong>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">🔧</div>
                    <strong>Terraform</strong>
                </div>
                <div class="skill-card">
                    <div class="skill-icon">📊</div>
                    <strong>Jenkins</strong>
                </div>
            </div>
        </div>

        <div class="section">
            <h2>⚡ DevOps Workflow</h2>
            <div class="workflow-diagram">
                <div class="workflow-steps">
                    <div class="workflow-step">
                        <h3>1. Plan</h3>
                        <p>Requirements & Architecture Design</p>
                    </div>
                    <div class="workflow-step">
                        <h3>2. Build</h3>
                        <p>Development & Testing</p>
                    </div>
                    <div class="workflow-step">
                        <h3>3. Deploy</h3>
                        <p>CI/CD Pipeline</p>
                    </div>
                    <div class="workflow-step">
                        <h3>4. Monitor</h3>
                        <p>Performance & Security</p>
                    </div>
                </div>
            </div>
        </div>

        <div class="section">
            <h2>📊 GitHub Statistics</h2>
            <div class="stats-container">
                <div class="stat-card">
                    <div class="stat-number">500+</div>
                    <p>Commits This Year</p>
                </div>
                <div class="stat-card">
                    <div class="stat-number">50+</div>
                    <p>Projects Completed</p>
                </div>
                <div class="stat-card">
                    <div class="stat-number">10+</div>
                    <p>Technologies Mastered</p>
                </div>
            </div>
        </div>

        <div class="section">
            <h2>🤝 Let's Connect</h2>
            <div class="social-links">
                <a href="https://www.linkedin.com/in/jhanzaib-memon-9905a21a7" target="_blank" class="social-btn">
                    💼 LinkedIn
                </a>
                <a href="https://github.com/MuhammadJahanzeb" target="_blank" class="social-btn">
                    💻 GitHub
                </a>
                <a href="mailto:your-email@example.com" class="social-btn">
                    📧 Email
                </a>
            </div>
        </div>

        <footer>
            <p>⚡ Powered by DevOps Principles</p>
            <p style="margin-top: 10px; font-size: 0.9em; opacity: 0.8;">Last Updated: January 2026</p>
        </footer>
    </div>
</body>
</html>
