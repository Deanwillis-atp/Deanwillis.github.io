# Deanwillis.github.io
<style>
    .portfolio-container {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        line-height: 1.6;
        color: #333;
        max-width: 8.5in;
        margin: 0 auto;
        padding: 0.75in;
        background: white;
    }
    
    .portfolio-header {
        text-align: center;
        border-bottom: 3px solid #667eea;
        padding-bottom: 20px;
        margin-bottom: 30px;
    }
    
    .portfolio-header h1 {
        font-size: 2.2em;
        color: #667eea;
        margin-bottom: 5px;
    }
    
    .portfolio-header .subtitle {
        font-size: 1.1em;
        color: #666;
        margin-bottom: 15px;
    }
    
    .contact-info {
        font-size: 0.95em;
        color: #555;
    }
    
    .contact-info a {
        color: #667eea;
        text-decoration: none;
    }
    
    .portfolio-section {
        margin-bottom: 35px;
    }
    
    .portfolio-section h2 {
        color: #667eea;
        font-size: 1.5em;
        border-bottom: 2px solid #e0e0e0;
        padding-bottom: 8px;
        margin-bottom: 15px;
    }
    
    .about-text {
        text-align: justify;
        margin-bottom: 20px;
    }
    
    .project {
        margin-bottom: 30px;
        padding: 20px;
        background: #f8f9fa;
        border-radius: 8px;
        border-left: 4px solid #667eea;
    }
    
    .project h3 {
        color: #667eea;
        font-size: 1.3em;
        margin-bottom: 10px;
    }
    
    .project-description {
        margin-bottom: 12px;
        text-align: justify;
    }
    
    .highlight-box {
        background: #fff3cd;
        border-left: 4px solid #ffc107;
        padding: 10px 15px;
        margin: 10px 0;
        font-size: 0.95em;
    }
    
    .tech-stack {
        margin: 12px 0;
    }
    
    .tech-stack strong {
        color: #555;
        font-size: 0.9em;
    }
    
    .tech-stack span {
        display: inline-block;
        background: white;
        padding: 4px 10px;
        margin: 3px 5px 3px 0;
        border-radius: 3px;
        font-size: 0.85em;
        border: 1px solid #ddd;
    }
    
    .github-link {
        color: #667eea;
        text-decoration: none;
        font-size: 0.9em;
        font-weight: 500;
    }
    
    .github-link:before {
        content: "→ ";
    }
    
    .portfolio-footer {
        margin-top: 40px;
        padding-top: 20px;
        border-top: 2px solid #e0e0e0;
        text-align: center;
        font-size: 0.9em;
        color: #666;
    }
</style>

<div class="portfolio-container">
    <header class="portfolio-header">
        <h1>Dean Willis</h1>
        <div class="subtitle">Finance Graduate (B.S.) | Minor in Applied Computing<br>
        Interest in Machine Learning & Database Systems</div>
        <div class="contact-info">
            <a href="mailto:deanwillis@outlook.com">deanwillis@outlook.com</a> | 
            <a href="https://github.com/Deanwillis-atp">github.com/Deanwillis-atp</a> | 
            <a href="https://deanwillis.com">deanwillis.com</a>
        </div>
    </header>

    <section class="portfolio-section about">
        <h2>About</h2>
        <p class="about-text">
            Finance graduate (B.S.) with a minor in Applied Computing, currently pursuing an M.S. in Computer Science at the University of South Carolina. My academic focus centers on machine learning applications and database systems, with hands-on experience in Python development, full-stack web applications, and computational mathematics. I am passionate about building intelligent systems and exploring the intersection of mathematics, data science, and software engineering. Through my projects, I have developed strong problem-solving skills and a commitment to writing clean, efficient code.
        </p>
    </section>

    <section class="portfolio-section projects">
        <h2>Featured Projects</h2>
        
        <div class="project">
            <h3>Semi-Prime Factorization Algorithm (Gap=4)</h3>
            <p class="project-description">
                Original mathematical research project that discovers and implements a pattern-based algorithm for factoring a specific class of semi-prime numbers. Semi-primes with gap=4 are products of two prime numbers that differ by exactly 4 (e.g., 3×7=21, 7×11=77, 13×17=221). Through computational experimentation and number theory analysis, I developed an algorithm that can efficiently calculate the prime factors of these numbers without traditional brute-force factorization methods.
            </p>
            <div class="highlight-box">
                <strong>Key Achievement:</strong> Successfully factors semi-primes exceeding 2 trillion (e.g., 2,208,062,262,021 → 1,485,953 × 1,485,957) with near-instant computation, demonstrating the efficiency of pattern-based approaches over traditional factorization methods that would require hours or days for numbers of this magnitude.
            </div>
            <p class="project-description">
                The project includes a sequence generator that produces valid semi-prime candidates and validates factorization accuracy across large number ranges. This work demonstrates independent research ability, creative problem-solving in computational mathematics, algorithmic thinking, and the capacity to identify and exploit mathematical patterns—skills essential for graduate-level research.
            </p>
            <div class="tech-stack">
                <strong>Technologies:</strong>
                <span>Python</span>
                <span>Number Theory</span>
                <span>Algorithm Design</span>
                <span>Mathematical Pattern Recognition</span>
                <span>Computational Mathematics</span>
            </div>
            <a href="https://github.com/Deanwillis-atp/semiprime-repo" class="github-link">View on GitHub (coming soon)</a>
        </div>
        
        <div class="project">
            <h3>Amazon Review Sentiment Analyzer</h3>
            <p class="project-description">
                Sentiment analysis model that classifies Amazon product reviews as positive or negative using natural language processing and machine learning. Built using the Amazon Review Polarity Dataset (3.6 million reviews spanning 18 years), the model implements TF-IDF vectorization for text feature extraction and a Support Vector Machine (SVM) classifier with a linear kernel for binary classification.
            </p>
            <p class="project-description">
                The system processes review text to predict sentiment polarity, achieving strong accuracy on test data. The project demonstrates practical application of NLP techniques, text preprocessing, feature engineering, and supervised learning for real-world text classification tasks. Initial experimentation also explored NLTK's VADER sentiment analyzer for comparative analysis.
            </p>
            <div class="tech-stack">
                <strong>Technologies:</strong>
                <span>Python</span>
                <span>Scikit-learn</span>
                <span>Pandas</span>
                <span>NLTK</span>
                <span>TF-IDF</span>
                <span>SVM</span>
                <span>Natural Language Processing</span>
            </div>
            <a href="https://github.com/Deanwillis-atp/sentiment_analyzer" class="github-link">View on GitHub</a>
        </div>
        
        <div class="project">
            <h3>Text-Based RPG Adventure Game</h3>
            <p class="project-description">
                Interactive text-based role-playing game featuring story-driven gameplay, dynamic inventory management, combat mechanics, and branching narrative paths based on player decisions. Demonstrates strong object-oriented programming principles including inheritance, encapsulation, and polymorphism. The game architecture includes a robust state management system, character progression mechanics, and save/load functionality, showcasing end-to-end software development skills.
            </p>
            <div class="tech-stack">
                <strong>Technologies:</strong>
                <span>Python/Java</span>
                <span>Object-Oriented Programming</span>
                <span>Game Logic Design</span>
                <span>State Management</span>
            </div>
            <a href="https://github.com/Deanwillis-atp/rpg-project" class="github-link">View on GitHub</a>
        </div>
        
        <div class="project">
            <h3>Full-Stack CRUD Application</h3>
            <p class="project-description">
                Complete CRUD (Create, Read, Update, Delete) application with user authentication, database integration, and RESTful API architecture. Features include secure user management, data validation, responsive frontend design, and efficient database queries. The application demonstrates full-stack development capabilities from database schema design and backend API development to frontend user interface implementation, incorporating industry best practices for security and scalability.
            </p>
            <div class="tech-stack">
                <strong>Technologies:</strong>
                <span>React/Node.js</span>
                <span>PostgreSQL/MongoDB</span>
                <span>REST API</span>
                <span>JWT Authentication</span>
                <span>Express.js</span>
            </div>
            <a href="https://github.com/Deanwillis-atp/crud-project" class="github-link">View on GitHub</a>
        </div>
        
        <div class="project">
            <h3>Classic Word Games Collection</h3>
            <p class="project-description">
                Collection of classic word games including Hangman, implementing clean function-based architecture with modular design principles. Features include input validation, error handling, game state persistence, and an intuitive user interface. The project demonstrates fundamental programming concepts, string manipulation techniques, and user experience design considerations, with emphasis on code readability and maintainability.
            </p>
            <div class="tech-stack">
                <strong>Technologies:</strong>
                <span>Python</span>
                <span>Functional Programming</span>
                <span>Input Validation</span>
                <span>Logic Design</span>
            </div>
            <a href="https://github.com/Deanwillis-atp/games-project" class="github-link">View on GitHub</a>
        </div>
    </section>

    <footer class="portfolio-footer">
        <p>Portfolio prepared for University of South Carolina M.S. in Computer Science Program</p>
        <p>All projects available at <a href="https://github.com/Deanwillis-atp">github.com/Deanwillis-atp</a></p>
    </footer>
</div>
