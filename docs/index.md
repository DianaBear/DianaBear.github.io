<!DOCTYPE html>
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
            background: rgb(168, 7, 255); 
            color: #333;
        }

        /* About Me Section */
        .about {
            padding: 40px;
            text-align: center;
        }

        /* Projects Section */
        .projects {
            padding: 40px;
            background-color: #f7f7f7;
        }

        .project-container {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }

        .project-card {
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        /* Contact Section */
        .contact {
            padding: 40px;
            background-color: #e9e9e9;
        }

        .contact-info ul {
            list-style: none;
            padding: 0;
        }

        .contact-info li {
            margin-bottom: 10px;
        }

        /* Footer */
        .footer {
            padding: 20px;
            background-color: #D6B3E1;
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
        <div class="logo">👩🏻‍💻 Diana Barakat</div>
        <ul class="nav-links">
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About Me</a></li>
            <li><a href="CareerOverview.html">Career Overview</a></li>
            <li><a href="Resume.html">Resume</a></li>
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
        <p>Hey there! I'm Diana, a Computer Information System major and Cyber Security minor at Clemson University. I enjoy exploring APIs, learning new programming languages, and all things tech!</p>
    </section>

    <!-- Projects Section -->
    <section class="projects" id="projects">
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
                <p>Analyzed weather patterns and predicted future conditions using machine learning algorithms.</p>
            </div>
            <div class="project-card">
                <h3>DianaBear Typing Game (C)</h3>
                <p>A fun typing game that tracks your typing speed (WPM) and helps practice notes or lyrics.</p>
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
        <div class="footer-links">
            <a href="index.html">Home</a> | 
            <a href="about.html">About</a> | 
            <a href="CareerOverview.html">Career</a> | 
            <a href="Resume.html">Resume</a> | 
            <a href="contact.html">Contact</a>
        </div>
    </footer>
</body>
</html> -->


<!DOCTYPE html>
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
            background: rgb(168, 7, 255); 
            color: #333;
        }

        /* About Me Section */
        .about {
            padding: 40px;
            text-align: center;
        }

        /* Projects Section */
        .projects {
            padding: 40px;
            background-color: #f7f7f7;
        }

        .project-container {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }

        .project-card {
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        /* Skills Section */
        .skills {
            padding: 40px;
            text-align: center;
            background-color: #e9e9e9;
        }

        /* Contact Section */
        .contact {
            padding: 40px;
            background-color: #e9e9e9;
        }

        .contact-info ul {
            list-style: none;
            padding: 0;
        }

        .contact-info li {
            margin-bottom: 10px;
        }

        /* Footer */
        .footer {
            padding: 20px;
            background-color: #D6B3E1;
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
        <div class="logo">👩🏻‍💻 Diana Barakat</div>
        <ul class="nav-links">
            <li><a href="index.html">Home</a></li>
            <li><a href="about.html">About Me</a></li>
            <li><a href="CareerOverview.html">Career Overview</a></li>
            <li><a href="Resume.html">Resume</a></li>
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
        <p>Hey there! I'm Diana, a Computer Information System major and Cyber Security minor at Clemson University. I am passionate about leveraging technology to solve real-world problems. I love exploring APIs, developing efficient code, and collaborating with other innovators in the tech community.</p>
        <p>My journey in Computer Science started with a curiosity for how technology impacts everyday life, and now I'm focused on advancing my skills in areas like backend development, microservices, and cybersecurity.</p>
    </section>

    <!-- Skills Section -->
    <section class="skills">
        <h2>Skills & Expertise</h2>
        <p>Here are some of the skills I’ve developed throughout my studies and projects:</p>
        <ul>
            <li>Programming Languages: Python, C, JavaScript, SQL</li>
            <li>Frameworks: Flask, Node.js, Express.js</li>
            <li>Web Development: HTML5, CSS3, JavaScript, React</li>
            <li>APIs: RESTful APIs, Postman</li>
            <li>Version Control: Git, GitHub</li>
            <li>Databases: MySQL, MongoDB</li>
            <li>Cybersecurity: Vulnerability Scanning, Encryption</li>
        </ul>
    </section>

    <!-- Projects Section -->
    <section class="projects" id="projects">
        <h2>My Projects</h2>
        <div class="project-container">
            <div class="project-card">
                <h3>TigerChow API</h3>
                <p>Developed an API to streamline campus food orders, using Postman for testing and microservices for the backend. It optimizes the user experience and enables easy integration with other systems.</p>
            </div>
            <div class="project-card">
                <h3>Image Stacking in C</h3>
                <p>Noise reduction in PPM images using dynamic memory allocation in C, improving image quality for further analysis. A hands-on project in memory management and image processing.</p>
            </div>
            <div class="project-card">
                <h3>Weather Predictor (Python)</h3>
                <p>Built a weather prediction system using Python’s machine learning libraries, analyzing past weather data and predicting future conditions for accurate forecasting.</p>
            </div>
            <div class="project-card">
                <h3>DianaBear Typing Game (C)</h3>
                <p>A fun typing game that tracks your typing speed (WPM) and helps practice notes or lyrics. Built in C with a timer and WPM calculation for a user-friendly experience.</p>
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
        <div class="footer-links">
            <a href="index.html">Home</a> | 
            <a href="about.html">About</a> | 
            <a href="CareerOverview.html">Career</a> | 
            <a href="Resume.html">Resume</a> | 
            <a href="contact.html">Contact</a>
        </div>
    </footer>
</body>
</html>
