---
permalink: /resume
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diana Barakat | Resume</title>
    <style>
        /* Global Styles */
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

        /* Sections */
        .resume-section {
            padding: 60px 20px;
            max-width: 800px;
            margin: auto;
        }

        h2 {
            color: #F66733;
            font-size: 2rem;
        }

        /* Resume Content */
        .resume-content {
            background: white;
            padding: 30px;
            border: 2px solid #F66733;
            border-radius: 10px;
            box-shadow: 3px 3px 10px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }

        .resume-content p {
            font-size: 1.1rem;
            line-height: 1.6;
            color: #333;
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
        <div class="logo">🐅 DianaBear</div>
        <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <header class="hero">
        <h1>My Resume</h1>
        <p>Explore my journey, skills, and achievements as a Clemson Tiger and aspiring Cybersecurity Analyst.</p>
    </header>

    <!-- Resume Content -->
    <section class="resume-section">
        <div class="resume-content">
            <h2>Updated Resume</h2>
            <p>You can view my latest resume here: <a href="https://docs.google.com/document/d/1A6QZWEtbWgpBSnQmdusWNSqi-bqpmVr77o6TFo4Xgx8/edit?usp=sharing" target="_blank">My Resume</a></p>
        </div>

        <div class="resume-content">
            <h2>LinkedIn Profile</h2>
            <p>Connect with me professionally through my LinkedIn profile: <a href="https://www.linkedin.com/in/dianabear/" target="_blank">LinkedIn - Diana Barakat</a></p>
        </div>

        <div class="resume-content">
            <h2>Note:</h2>
            <p>I regularly update my resume and LinkedIn profile at the end of each semester to reflect my latest coursework, projects, and achievements.</p>
        </div>
    </section>

    <!-- Relevant Links -->
    <section class="resume-section">
        <h2>Relevant Links</h2>
        <ul class="nav-links">
            <li><a href="index.md">Home</a></li>
            <li><a href="about.md">About Me</a></li>
            <li><a href="CareerOverview.md">Career Overview</a></li>
        </ul>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <p>&copy; 2025 DianaBear | Clemson Proud 🐅</p>
    </footer>
</body>
</html>
