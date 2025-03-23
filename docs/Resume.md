<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
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

        /* Resume Section */
        .resume {
            padding: 40px;
            background-color: #e9e9e9;
        }

        .resume h2 {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 20px;
        }

        .resume p {
            font-size: 1.1rem;
            line-height: 1.6;
        }

        .resume ul {
            list-style: none;
            padding: 0;
        }

        .resume ul li {
            margin-bottom: 15px;
        }

        .download-btn {
            display: inline-block;
            padding: 12px 24px;
            background: #F66733;
            color: white;
            font-weight: bold;
            text-decoration: none;
            border-radius: 8px;
            margin-top: 20px;
            text-align: center;
        }

        .download-btn:hover {
            background: rgb(168, 7, 255); 
            color: #333;
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
    </style>
</head>
<body>
    <!-- Hero Section -->
    <header class="hero">
        <h1>My Resume</h1>
        <!-- <p>Computer Science Student | Clemson University | Intern @ Vertiv</p> -->
        <a href="#projects" class="cta">View My Work</a>
    </header>

    <!-- Resume Section -->
    <section class="resume" id="resume">
        <h2>My Resume</h2>
        <p><strong>Diana Barakat</strong><br>
        Email: <a href="mailto:dbaraka@clemson.edu">dbaraka@clemson.edu</a> | Phone: <a href="mailto:dbaraka@clemson.edu">Email for details</a><br>
        LinkedIn: <a href="https://www.linkedin.com/in/dianabear/">Diana Barakat</a></p>

        <h3>Education</h3>
        <ul>
            <li><strong>Clemson University, Clemson, SC</strong> (August 2023 – Present)<br>
            B.S. Computer Information Systems | Minor in Cybersecurity</li>
            <li><strong>Tri-County Technical College, Pendleton, SC</strong> (August 2021 – June 2022)<br>
            University Studies Certificate | December 13, 2022</li>
        </ul>

        <h3>Coursework & Projects</h3>
        <p><strong>Relevant Coursework:</strong> Web Site Design, Intro to Programming Logic, C Programming, Microcomputer Applications, Algorithms and Data Structures, Computer Science, Discrete Structures for Computing, Computer Ethics and Society, Problem Solving with Office Apps, Computer Science II, Software Development Foundations, and Computer Organization.</p>
        <p><strong>Projects Built in C++:</strong> Linked List Based Stacks and Queues, Infix to Postfix Conversion, Finding Groups Using Recursion, Searching and Sorting, Spell Checker Using a Hash Table, Finding the Closest Pair of Points.</p>
        <p><strong>Personal Projects:</strong> Weather Predictions using Machine Learning (Python)</p>

        <h3>Professional Experience</h3>
        <ul>
            <li><strong>Finance Specialist</strong> at A&H Auto Sales, Greenville, SC
                <ul>
                    <li>Maintained accurate financial records for accounts payable/receivable.</li>
                    <li>Assisted with budgeting and financial reporting tasks to support decision-making.</li>
                    <li>Implemented streamlined processes to improve efficiency in financial record-keeping.</li>
                </ul>
            </li>
            <li><strong>Financial Assistant</strong> at SB Trucking
                <ul>
                    <li>Supported preparation of 1099 tax submissions.</li>
                    <li>Built semi-automated accounting expense balancing tool.</li>
                </ul>
            </li>
        </ul>

        <h3>Technical Skills</h3>
        <ul>
            <li>Proficient in C, C++</li>
            <li>Intro Level Python, JavaScript</li>
            <li>Microsoft Office Specialist (MOS)</li>
            <li>Linux, Microsoft Access</li>
        </ul>

        <h3>Languages</h3>
        <ul>
            <li>English, Arabic, Spanish</li>
        </ul>

        <!-- Download Resume Button -->
        <a href="Diana_Barakat_Resume.pdf" class="download-btn" download>Download Resume</a>
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

    <footer class="footer">
        <p> Last updated 2025 by DianaBear | Clemson University</p>
        <div class="footer-links">
            <a href="index.html">Home</a> |
            <a href="about.html">About</a> | 
            <a href="CareerOverview.html">Career</a> | 
        </div>
    </footer>
    
</body>
</html>
