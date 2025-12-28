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
            color: #e0e0e0;
            background: #000000;
            min-height: 100vh;
        }

        .container {
            max-width: 1400px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            background: #1a1a1a;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(255, 255, 255, 0.1);
            margin-bottom: 30px;
            text-align: center;
            border: 1px solid #333;
        }

        h1 {
            font-size: 2.5em;
            color: #00d4ff;
            margin-bottom: 10px;
        }

        .subtitle {
            font-size: 1.2em;
            color: #b0b0b0;
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
            color: #00d4ff;
            text-decoration: none;
            padding: 8px 16px;
            border: 2px solid #00d4ff;
            border-radius: 25px;
            transition: all 0.3s;
        }

        .contact-links a:hover {
            background: #00d4ff;
            color: #000;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 212, 255, 0.4);
        }

        .about-section {
            background: #1a1a1a;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(255, 255, 255, 0.1);
            margin-bottom: 30px;
            border: 1px solid #333;
        }

        .about-section h2 {
            color: #00d4ff;
            margin-bottom: 15px;
            font-size: 2em;
        }

        .about-section p {
            font-size: 1.1em;
            color: #c0c0c0;
        }

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
            gap: 30px;
            margin-bottom: 30px;
        }

        .project-card {
            background: #1a1a1a;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(255, 255, 255, 0.1);
            transition: transform 0.3s, box-shadow 0.3s;
            border: 1px solid #333;
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 40px rgba(0, 212, 255, 0.3);
            border-color: #00d4ff;
        }

        .project-card h3 {
            color: #00d4ff;
            margin-bottom: 15px;
            font-size: 1.5em;
        }

        .project-card p {
            color: #c0c0c0;
            margin-bottom: 15px;
        }

        .key-achievement {
            background: #0a2a3a;
            padding: 15px;
            border-left: 4px solid #00d4ff;
            margin: 15px 0;
            border-radius: 5px;
        }

        .key-achievement strong {
            color: #00d4ff;
        }

        .technologies {
            margin-top: 20px;
        }

        .technologies h4 {
            color: #00d4ff;
            margin-bottom: 10px;
        }

        .tech-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }

        .tech-tag {
            background: #00d4ff;
            color: #000;
            padding: 5px 12px;
            border-radius: 15px;
            font-size: 0.9em;
            font-weight: 600;
        }

        .github-link {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            background: #00d4ff;
            color: #000;
            text-decoration: none;
            border-radius: 25px;
            transition: all 0.3s;
            font-weight: 600;
        }

        .github-link:hover {
            background: #00a8cc;
            transform: translateX(5px);
            box-shadow: 0 5px 15px rgba(0, 212, 255, 0.4);
        }

        footer {
            background: #1a1a1a;
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(255, 255, 255, 0.1);
            text-align: center;
            color: #b0b0b0;
            border: 1px solid #333;
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
                
            </div>
        </header>

        <section class="about-section">
            <h2>About Me</h2>
            <p>Finance graduate (B.S.) with a minor in Applied Computing, currently pursuing an M.S. in Computer Science at the University of South Carolina. I have experience in full-stack web applications, Python, and computational mathematics. I developed strong problem solving skills and applied clean, efficient code while working on projects. Going forward, my academic focus is on machine learning and database systems, as I am passionate about building intelligent systems while exploring how mathematics and software engineering work.</p>
        </section>

        <div class="projects-grid">
            <div class="project-card">
                <h3>Semi-Prime Factorization Algorithm</h3>
                <p>Original mathematical research project that discovers and implements a pattern-based algorithm for factoring a specific class of semi-prime numbers. Semi-primes with gap=4 are products of two prime numbers that differ by exactly 4 (e.g., 3×7=21, 7×11=77, 13×17=221). I developed an algorithm that efficiently calculates the prime factors of numbers using number theory analysis and computational experimentation, bypassing traditional factorization approaches through pattern recognition for this specific class of numbers.</p>
                
                <div class="key-achievement">
                    <strong>Key Achievement:</strong> Demonstrated the efficiency of computation using patterns in factorization. My program almost instantaneously factors semi-primes exceeding 1 quadrillion (e.g., 1,224,999,929,999,997 → 34,999,997 × 35,000,001).
                </div>

                <p>The sequence generator produces candidates for semi-prime factorization and validates output across very large number ranges. This work demonstrates my ability to conduct graduate-level research using computational mathematics while showcasing my capacity to identify and manipulate mathematical patterns, work with algorithms, use creative problem-solving, and work independently.</p>

                <div class="technologies">
                    <h4>Technologies:</h4>
                    <div class="tech-tags">
                        <span class="tech-tag">Python</span>
                        <span class="tech-tag">Number Theory</span>
                        <span class="tech-tag">Algorithm Design</span>
                        <span class="tech-tag">Mathematical Research</span>
                    </div>
                </div>

                <a href="https://github.com/Deanwillis-atp/semiprime_factorizer" target="_blank" class="github-link">View on GitHub →</a>
            </div>

            <div class="project-card">
                <h3>Amazon Review Sentiment Analyzer</h3>
                <p>I developed a program that uses sentiment analysis to identify whether Amazon reviews are positive or negative. My program uses the Amazon Review Polarity Dataset (3.6 million reviews spanning 18 years), as well as machine learning and natural language processing. My model uses a Support Vector Machine (SVM) to separate two classes of data with a straight line (linear kernel) and TF-IDF vectorization to extract text. The system predicts sentiment polarity from the text with accuracy as was demonstrated on test data. My project applies NLP techniques to classify text for real-world application.</p>

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
                    <strong>Features:</strong> Multi-bot coordination (Billy and Kathy), 12+ branching decision points, retro terminal web interface, timed async messaging for suspense, fake social media integration (FaceLibrary), and cross-bot communication through JSON file triggers.
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

       
    </div>
</body>
</html>
