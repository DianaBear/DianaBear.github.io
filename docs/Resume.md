---
permalink: /resume
---
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume | Diana Barakat</title>
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
            <li><a href="CareerOverview.md">Career Overview</a></li>
            <li><a href="Resume.md">Resume</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <header class="hero">
        <h1>Resume</h1>
        <p>Here’s an overview of my academic achievements and experience.</p>
    </header>

    <!-- Footer -->
    <footer class="footer">
        <p>&copy; 2025 DianaBear</p>
    </footer>
</body>
</html>
