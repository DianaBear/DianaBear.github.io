---
permalink: /about
---
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me | Diana Barakat</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #F2F3F2;
            color: #333;
            text-align: center;
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

        .section {
            padding: 60px 20px;
            max-width: 900px;
            margin: auto;
        }

        /* Footer */
        .footer {
            background: #333;
            color: white;
            padding: 10px;
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
            <li><a href="careerOverview.md">Career Overview</a></li>
            <li><a href="resume.md">Resume</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <header class="hero">
        <h1>About Me</h1>
        <p>Learn more about my academic journey and career goals.</p>
    </header>

    <!-- About Me Section -->
    <section class="section">
        <h2>About Diana Barakat</h2>
        <p>I am a Computer Information Systems major with a Cybersecurity minor at Clemson University, and I plan to graduate in May 2026. I have a deep fascination with cutting-edge technologies, particularly in the areas of artificial intelligence, machine learning, and privacy compliance in software development. These interests reflect my passion for understanding how advanced algorithms and secure systems shape the modern digital landscape. By pursuing both technical and security-focused coursework, I am building a broad skill set to thrive in the ever-evolving world of technology.</p>

        <h2>My goals as a student</h2>
        <p>My goal is to become a Cybersecurity Analyst, where I can apply my skills to protect systems and safeguard data in an increasingly digital world. While I have a clear end goal, I am also taking the time to explore different areas of computer science to discover what excites me most. Whether it’s diving deeper into AI, studying cybersecurity threats, or experimenting with software development, I believe this exploration will help me grow both personally and professionally. I am driven by a desire to learn, adapt, and contribute meaningfully to the ever-evolving tech landscape.</p>

        <h2>Contact Me</h2>
        <p>Feel free to connect with me via the following:</p>
        <ul>
            <li>Email: <a href="mailto:dbaraka@clemson.edu">dbaraka@clemson.edu</a></li>
            <li>LinkedIn: <a href="https://www.linkedin.com/in/dianabear/">Diana Barakat</a></li>
            <li>GitHub: <a href="https://github.com/DianaBear">DianaBear</a></li>
        </ul>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <p>&copy; 2025 DianaBear</p>
    </footer>
</body>
</html>
