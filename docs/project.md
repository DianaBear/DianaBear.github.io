<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Projects</title>
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

        /* Styling for images (code snippets) */
        img {
            max-width: 100%;
            height: auto;
            border: 1px solid #ccc;
            border-radius: 8px;
            margin: 20px 0;
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <header class="hero">
        <h1>My Projects</h1>
        <p>Explore some of the projects I've worked on during my studies.</p>
    </header>

    <!-- Projects Section -->
    <section class="projects" id="projects">
        <h2>Checkers Game Project</h2>
        <p>This project is a checkers game built using [language/framework]. Below is a screenshot of the code:</p>
        <img src="images/checkers_code.png" alt="Checkers Project Code Snippet">

        <h2>Data Science Project (Python)</h2>
        <p>This project uses IPEDS data to analyze the number of men and women in computer science nationally and at Clemson University. Below is a screenshot of the code:</p>
        <img src="CodeSnippets/womenCPSC code snippet.png" alt="Data Science Project Code Snippet">

        <h2>US vs. France Government Comparison (R)</h2>
        <p>This project compares the US and French governments using R. Below is a screenshot of the code:</p>
        <img src="CodeSnippets/R code snippet.png" alt="US vs France Code Snippet">

        <!-- Add more project sections as needed -->

    </section>

<footer class="footer">
        <p> Last updated 2025 by DianaBear | Clemson University</p>
        <div class="footer-links">
            <a href="index.html">Home</a> |
            <a href="about.html">About</a> |  
            <a href="CareerOverview.html">Career</a> | 
            <a href="Resume.html">Resume</a> |
        </div>
    </footer>




</body>
</html>
