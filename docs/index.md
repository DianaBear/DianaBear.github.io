---
permalink: /
---
# **Diana Barakat**

## About Me
I am a Computer Information Systems major with a Cybersecurity minor at Clemson University, and I plan to graduate
in May 2026. I have a deep fascination with cutting-edge technologies, particularly in the areas of artificial
intelligence, machine learning, and privacy compliance in software development. These interests reflect my passion
for understanding how advanced algorithms and secure systems shape the modern digital landscape. By pursuing both
technical and security-focused coursework, I am building a broad skill set to thrive in the ever-evolving world of
technology.

## Menu
Relevant Links:

- [About Me](about.md)
- [Public Resume and LinkedIn](Resume.md)
- [Career Overview](CareerOverview.md)

## How to contact me 
- Clemson Email: dbaraka@clemson.edu
- Vertiv Email: -----
- LinkedIn: [Diana Barakat](https://www.linkedin.com/in/dianabear/)
- GitHub Username: DianaBear

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diana Barakat | Clemson Computer Scientist</title>
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
    </style>
    <script>
        document.addEventListener("DOMContentLoaded", function() {
            document.querySelectorAll('.nav-links li a').forEach(link => {
                link.addEventListener('mouseover', () => {
                    link.style.textDecoration = 'underline';
                });

                link.addEventListener('mouseout', () => {
                    link.style.textDecoration = 'none';
                });
            });
        });
    </script>
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
        <h1>Welcome to My World!</h1>
        <p>Computer Science Enthusiast | Clemson Tiger | Tech Explorer</p>
        <a href="#projects" class="cta">View My Work</a>
    </header>

    <!-- About Me -->
    <section id="about" class="about">
        <h2>About Me</h2>
        <p>Hey there! I'm Diana, a passionate computer science student at Clemson University. I love exploring APIs, microservices, and all things tech. Let’s build something amazing!</p>
    </section>

    <!-- Projects -->
    <section id="projects" class="projects">
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
        </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="contact">
        <h2>Contact Me</h2>
        <p>Let's connect! Reach out via email or find me on GitHub.</p>
        <a href="mailto:diana@example.com" class="contact-btn">Email Me</a>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <p>&copy; 2025 DianaBear | Clemson Proud 🐅</p>
    </footer>
</body>
</html>
