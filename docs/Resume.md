<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diana Barakat | Portfolio</title>

    <style>
        /* Global Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #F5F5F5;
            color: #333;
        }

        /* Navbar */
        .navbar {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 15px 30px;
            background: #5A5A5A; /* Dark Gray */
            color: white;
            font-size: 1.5rem;
            font-weight: bold;
        }

        /* Hero Section */
        .hero {
            background: #3A3A3A; /* Darker Gray */
            color: white;
            padding: 80px 20px;
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
            color: #5A5A5A;
            font-weight: bold;
            text-decoration: none;
            border-radius: 8px;
            margin-top: 20px;
            transition: 0.3s;
        }

        .cta:hover {
            background: #A807FF;
            color: #fff;
        }

        /* Resume Section */
        .resume {
            padding: 40px;
            background-color: #FFFFFF;
            text-align: center;
        }

        .resume a {
            color: #F66733;
            text-decoration: none;
            font-weight: bold;
        }

        .resume a:hover {
            text-decoration: underline;
        }

        .download-btn {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #F66733;
            color: white;
            font-weight: bold;
            text-decoration: none;
            border-radius: 5px;
        }

        .download-btn:hover {
            background-color: #D45027;
        }

        /* Projects Section */
        .projects {
            padding: 40px;
            background-color: #EDEDED;
            text-align: center;
        }

        .project-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            justify-content: center;
            margin-top: 20px;
        }

        .project-card {
            padding: 20px;
            background: #FFF;
            border-radius: 8px;
            border: 2px solid #5A5A5A;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
        }

        .project-card h3 {
            color: #F66733;
        }

        /* Footer */
        .footer {
            padding: 20px;
            background-color: #5A5A5A;
            text-align: center;
            color: white;
        }

        .footer-links {
            margin-top: 10px;
        }

        .footer-links a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            margin: 0 10px;
        }

        .footer-links a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <nav class="navbar">
        👩🏻‍💻 Welcome
    </nav>

    <!-- Hero Section -->
    <header class="hero">
        <h1>Welcome to My Portfolio 👩🏻‍💻</h1>
        <p>Computer Science Student | Clemson University | Cybersecurity Enthusiast</p>
        <a href="#projects" class="cta">View My Work</a>
    </header>

    <!-- Resume Section -->
    <section class="resume" id="resume">
        <h2>My Resume 👩🏻‍💻</h2>
        <p><strong>Diana Barakat</strong><br>
        Email: <a href="mailto:dbaraka@clemson.edu">dbaraka@clemson.edu</a> | Phone: <a href="mailto:dbaraka@clemson.edu">Email for details</a><br>
        LinkedIn: <a href="https://www.linkedin.com/in/dianabear/">Diana Barakat</a></p>

        <h3>Education</h3>
        <ul>
            <li><strong>Clemson University, Clemson, SC</strong> (August 2023 – Present)</li>
        </ul>

        <h3>Coursework & Projects</h3>
        <p><strong>Relevant Coursework:</strong> Web Site Design, C Programming, Microcomputer Applications...</p>

        <h3>Professional Experience</h3>
        <ul>
            <li><strong>Finance Specialist</strong> at A&H Auto Sales</li>
        </ul>

        <h3>Technical Skills</h3>
        <ul>
            <li>Proficient in C, C++, Python, Java, R</li>
        </ul>

        <h3>Languages</h3>
        <ul>
            <li>English, Arabic, Spanish</li>
        </ul>

        <a href="Diana_Barakat_Resume.pdf" class="download-btn" download>Download Resume</a>
    </section>

    <!-- Projects Section -->
    <section class="projects" id="projects">
        <h2>My Projects</h2>
        <div class="project-container">
            <div class="project-card">
                <h3>Checkers Game</h3>
                <p>A fun and interactive checkers game built using Python. The game allows two players to play checkers on the terminal.</p>
            </div>

            <div class="project-card">
                <h3>Data Science Project: Gender Analysis in Computer Science</h3>
                <p>This project uses IPEDS data to analyze the number of women and men in computer science both nationally and at Clemson University.</p>
            </div>

            <div class="project-card">
                <h3>US vs French Governments (R)</h3>
                <p>This R project compares the structure and functions of the US and French governments.</p>
            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="footer">
        <p>Last updated 2025 by DianaBear | Clemson University</p>
        <div class="footer-links">
            <a href="index.html">Home</a> |
            <a href="project.html">Projects</a> | 
            <a href="about.html">About</a> | 
            <a href="CareerOverview.html">Career</a>
        </div>
    </footer>

</body>
</html>
