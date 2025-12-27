
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dean Willis - Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background: rgba(255, 255, 255, 0.95);
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            margin-bottom: 30px;
            text-align: center;
        }

        h1 {
            font-size: 2.5em;
            color: #667eea;
            margin-bottom: 10px;
        }

        .subtitle {
            font-size: 1.2em;
            color: #666;
            margin-bottom: 15px;
        }

        .contact-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .contact-links a {
            color: #667eea;
            text-decoration: none;
            padding: 8px 16px;
            border: 2px solid #667eea;
            border-radius: 25px;
            transition: all 0.3s;
        }

        .contact-links a:hover {
            background: #667eea;
            color: white;
            transform: translateY(-2px);
        }

        .about-section {
            background: rgba(255, 255, 255, 0.95);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            margin-bottom: 30px;
        }

        .about-section h2 {
            color: #667eea;
            margin-bottom: 15px;
            font-size: 2em;
        }

        .about-section p {
            font-size: 1.1em;
            color: #555;
        }

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }

        .project-card {
            background: rgba(255, 255, 255, 0.95);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.3);
        }

        .project-card h3 {
            color: #667eea;
            margin-bottom: 15px;
            font-size: 1.5em;
        }

        .project-card p {
            color: #555;
            margin-bottom: 15px;
        }

        .key-achievement {
            background: #f0f4ff;
            padding: 15px;
            border-left: 4px solid #667eea;
            margin: 15px 0;
            border-radius: 5px;
        }

        .key-achievement strong {
            color: #667eea;
        }

        .technologies {
            margin-top: 20px;
        }

        .technologies h4 {
            color: #667eea;
            margin-bottom: 10px;
        }

        .tech-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }

        .tech-tag {
            background: #667eea;
            color: white;
            padding: 5px 12px;
            border-radius: 15px;
            font-size: 0.9em;
        }

        .github-link {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            background: #667eea;
            color: white;
            text-decoration: none;
            border-radius: 25px;
            transition: all 0.3s;
        }

        .github-link:hover {
            background: #764ba2;
            transform: translateX(5px);
        }

        footer {
            background: rgba(255, 255, 255, 0.95);
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            text-align: center;
            color: #666;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2em;
            }

            .projects-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>Dean Willis</h1>
            <p class="subtitle">Finance Graduate (B.S.) | Minor in Applied Computing</p>
            <p class="subtitle">M.S. Computer Science Student | Machine Learning & Database Systems</p>
            <div class="contact-links">
                <a href="mailto:deanwillis@outlook.com">Email</a>
                <a href="https://github.com/Deanwillis-atp" target="_blank">GitHub</a>
                <a href="https://deanwillis.com" target="_blank">Website</a>
            </div>
        </header>

        <section class="about-section">
            <h2>About Me</h2>
            <p>Finance graduate (B.S.) with a minor in Applied Computing, currently pursuing an M.S. in Computer Science at the University of South Carolina. I have experience in full-stack web applications, Python, and computational mathematics. I developed strong problem solving skills and applied clean, efficient code while working on projects. Going forward, my academic focus is on machine learning and database systems, as I am passionate about building intelligent systems while exploring how mathematics and software engineering work.</p>
        </section>

        <div class="projects-grid">
            <div class="project-card">
                <h3>Semi-Prime Factorization Algorithm</h3>
                <p>Original mathematical research project that discovers and implements a pattern-based algorithm for factoring a specific class of semi-prime numbers. Semi-primes with gap=4 are products of two prime numbers that differ by exactly 4 (e.g., 3×7=21, 7×11=77, 13×17=221).</p>
                
                <div class="key-achievement">
                    <strong>Key Achievement:</strong> My program almost instantaneously factors semi-primes exceeding 1 quadrillion (e.g., 1,224,999,929,999,997 → 34,999,997 × 35,000,001).
                </div>

                <p>The sequence generator produces candidates for semi-prime factorization and validates output across very large number ranges. This work demonstrates graduate-level research in computational mathematics, showcasing my ability to identify mathematical patterns, work with algorithms, and apply creative problem-solving independently.</p>

                <div class="technologies">
                    <h4>Technologies:</h4>
                    <div class="tech-tags">
                        <span class="tech-tag">Python</span>
                        <span class="tech-tag">Number Theory</span>
                        <span class="tech-tag">Algorithm Design</span>
                        <span class="tech-tag">Mathematical Research</span>
                    </div>
                </div>
            </div>

            <div class="project-card">
                <h3>Amazon Review Sentiment Analyzer</h3>
                <p>A program that uses sentiment analysis to identify whether Amazon reviews are positive or negative. Using the Amazon Review Polarity Dataset (3.6 million reviews spanning 18 years), this project applies machine learning and natural language processing techniques.</p>

                <p>The model uses a Support Vector Machine (SVM) with linear kernel to separate data classes and TF-IDF vectorization for text extraction. The system predicts sentiment polarity with high accuracy on test data, applying NLP techniques to classify text for real-world applications.</p>

                <div class="technologies">
                    <h4>Technologies:</h4>
                    <div class="tech-tags">
                        <span class="tech-tag">Python</span>
                        <span class="tech-tag">Scikit-learn</span>
                        <span class="tech-tag">SVM</span>
                        <span class="tech-tag">TF-IDF</span>
                        <span class="tech-tag">Pandas</span>
                        <span class="tech-tag">NLTK</span>
                        <span class="tech-tag">NLP</span>
                    </div>
                </div>

                <a href="https://github.com/Deanwillis-atp/sentiment_analyzer" target="_blank" class="github-link">View on GitHub →</a>
            </div>

            <div class="project-card">
                <h3>Interactive Horror Narrative Game</h3>
                <p>Multi-bot interactive horror experience delivered through Discord, combining narrative game design with full-stack development. Players sign up through a retro terminal-style web interface for a 'weather assistant' named Billy, who gradually reveals sinister intentions through timed, branching conversation trees.</p>

                <p>A second bot, Kathy, intervenes to warn players, creating a complex narrative with 12+ decision points and multiple endings. The project demonstrates advanced bot coordination, asynchronous message timing for dramatic effect, persistent state management across user sessions, and integration of web (Flask) and chat (Discord API) platforms.</p>

                <div class="key-achievement">
                    <strong>Features:</strong> Multi-bot coordination, 12+ branching decision points, retro terminal web interface, timed async messaging for suspense, and fake social media integration (FaceLibrary).
                </div>

                <div class="technologies">
                    <h4>Technologies:</h4>
                    <div class="tech-tags">
                        <span class="tech-tag">Python</span>
                        <span class="tech-tag">Discord.py</span>
                        <span class="tech-tag">Flask</span>
                        <span class="tech-tag">HTML/CSS</span>
                        <span class="tech-tag">JSON</span>
                        <span class="tech-tag">Async Programming</span>
                        <span class="tech-tag">Game Design</span>
                    </div>
                </div>

                <a href="https://github.com/Deanwillis-atp/Billy_V2" target="_blank" class="github-link">View on GitHub →</a>
            </div>
        </div>

        <footer>
            <p>&copy; 2025 Dean Willis. All rights reserved.</p>
        </footer>
    </div>
</body>
</html>
