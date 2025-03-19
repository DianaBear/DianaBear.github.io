---
permalink: /index
---
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
            background: #F66733; /* Clemson Orange */
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
            background: linear-gradient(135deg, #F66733, #522D80);
            color: white;
            padding: 80px 20px;
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
            background: #FFC107; /* Gold highlight effect */
            color: #333;
        }

        /* Sections */
        .about, .projects, .contact {
            padding: 60px 20px;
            max-width: 800px;
            margin: auto;
        }

        /* Projects */
        .project-container {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .project-card {
            background: #FFF;
            padding: 20px;
            border: 3px solid #F66733;
            border-radius: 10px;
            box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.1);
            width: 40%;
            min-width: 250px;
        }

        .project-card:hover {
            transform: scale(1.05);
            transition: 0.3s;
        }

        /* Contact */
        .contact-btn {
            display: inline-block;
            padding: 12px 24px;
            background: #522D80;
            color: white;
            font-weight: bold;
            text-decoration: none;
            border-radius: 8px;
        }

        .contact-btn:hover {
            background: #F66733;
        }

        /* Footer */
        .footer {
            background: #333;
            color: white;
            padding: 10px;
        }

        /* Contact Info */
        .contact-info {
            text-align: left;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar">
        <div class="logo">👩🏻‍💻 Diana Barakat</div>
        <ul class="nav-links">
            <li><a href="index.md">Home</a></li>
            <li><a href="about.md">About Me</a></li>
            <li><a href="CareerOverview.md">Career Overview</a></li>
            <li><a href="Resume.md">Resume</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <header class="hero">
        <h1>Welcome to My World!</h1>
        <p>Computer Science Student | Clemson University | Intern @ Vertiv</p>
        <a href="#projects" class="cta">View My Work</a>
    </header>

    <!-- About Me Section -->
    <section class="about">
        <h2>About Me</h2>
        <p>Hey there! I'm Diana, a passionate computer science student at Clemson University. I love exploring APIs, microservices, and all things tech. Let’s build something amazing!</p>
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
                <p>Analyzed weather patterns and predicted future conditions using machine learning algorithms. Built using the Pandas library in Python.</p>
            </div>
            <div class="project-card">
                <h3>DianaBear Typing Game (C)</h3>
                <p>A fun typing game that tracks your typing speed (WPM) and helps practice notes or lyrics. Built in C with a timer and WPM calculation.</p>
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
        <p>&copy; 2025 DianaBear | Clemson University</p>
    </footer>
</body>
</html>
