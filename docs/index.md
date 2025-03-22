
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diana Barakat | Clemson Computer Science</title>
    <style>
        /* Global Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #F2F3F2;
            color: #333;
        }

        /* Navbar */
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 30px;
            background: #D6B3E1; /* Lilac Purple */
            border-bottom: 5px solid #F66733; /* Orange Strip */
            color: white;
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 20px;
            padding: 0;
        }

        .nav-links li {
            display: inline;
        }

        .nav-links li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 10px;
        }

        .nav-links li a:hover {
            text-decoration: underline;
        }

        /* Hero Section */
        .hero {
            background: #D6B3E1; /* Lilac Purple */
            color: white;
            padding: 80px 20px;
            border-bottom: 5px solid #F66733; /* Orange Strip */
            text-align: center;
        }

        .hero h1 {
            font-size: 3rem;
        }

        .hero p {
            font-size: 1.3rem;
        }

        .cta {
            display: inline-block;
            padding: 12px 24px;
            background: white;
            color: #F66733;
            font-weight: bold;
            text-decoration: none;
            border-radius: 8px;
            margin-top: 20px;
            transition: 0.3s;
        }

        .cta:hover {
            background:rgb(168, 7, 255); /* Gold highlight effect */
            color: #333;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar">
        <div class="logo">👩🏻‍💻 Diana Barakat</div>
        <ul class="nav-links">
            <li><a href="/">Home</a></li>
            <li><a href="/about/">About Me</a></li>
            <li><a href="/CareerOverview/">Career Overview</a></li>
            <li><a href="/Resume/">Resume</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <header class="hero">
        <h1>Welcome to My World!</h1>
        <p>Computer Science Student | Clemson University | Intern @ Vertiv</p>
        <a href="#projects" class="cta">View My Work</a>
    </header>
</body>
</html>


    <!-- About Me Section -->
    <section class="about">
        <h2>About Me</h2>
        <p>Hey there! I'm Diana, a computer science student at Clemson University. I enjoy exploring APIs, learning new programming languages, and all things tech!</p>
    </section>

    <!-- Projects Section -->
    <section class="projects">
        <h2>My Projects</h2>
        <div class="project-container">
            <div class="project-card">
                <h3>TigerChow API</h3>
                <p>Developing an API to streamline campus food orders using Postman & microservices.</p>
            </div>
            <div class="project-card">
                <h3>Image Stacking in C</h3>
                <p>Noise reduction in PPM images using dynamic memory allocation in C.</p>
            </div>
            <div class="project-card">
                <h3>Weather Predictor (Python)</h3>
                <p>Analyzed weather patterns and predicted future conditions using machine learning algorithms. Built using the Pandas library in Python.[Personal Project]</p>
            </div>
            <div class="project-card">
                <h3>DianaBear Typing Game (C)</h3>
                <p>A fun typing game that tracks your typing speed (WPM) and helps practice notes or lyrics. Built in C with a timer and WPM calculation.[Personal Project]</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact">
        <h2>Contact Me</h2>
        <div class="contact-info">
            <p>Feel free to connect with me via the following:</p>
            <ul>
                <li>Email: <a href="mailto:dbaraka@clemson.edu">dbaraka@clemson.edu</a></li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/dianabear/">Diana Barakat</a></li>
                <li>GitHub: <a href="https://github.com/DianaBear">DianaBear</a></li>
            </ul>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <p> Last updated 2025 by DianaBear | Clemson University</p>
    </footer>
</body>
</html>

