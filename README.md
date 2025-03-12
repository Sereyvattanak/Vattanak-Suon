<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Modern Dark Portfolio</title>
    <style>
        body {
            background-color: #121212;
            color: #ffffff;
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #1e1e1e;
            padding: 20px;
            text-align: center;
            font-size: 28px;
            font-weight: bold;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #222;
            padding: 15px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
            font-size: 18px;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #00adb5;
        }
        .container {
            max-width: 900px;
            margin: 50px auto;
            padding: 20px;
        }
        section {
            margin-bottom: 50px;
        }
        h2 {
            border-bottom: 2px solid #00adb5;
            padding-bottom: 5px;
        }
        .button {
            background-color: #00adb5;
            color: white;
            padding: 12px 24px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            transition: background 0.3s;
        }
        .button:hover {
            background-color: #008c9e;
        }
        .social-icons {
            text-align: center;
            margin-top: 20px;
        }
        .social-icons a {
            color: white;
            font-size: 24px;
            margin: 0 10px;
            transition: color 0.3s;
        }
        .social-icons a:hover {
            color: #00adb5;
        }
    </style>
</head>
<body>
    <header>My Dark Portfolio</header>
    <nav>
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <p>Passionate learner and developer specializing in web development, machine learning, and mathematics.</p>
        </section>
        
        <section id="education">
            <h2>Education</h2>
            <ul>
                <li>Master's in Mathematics and Computing - IIT (ISM) Dhanbad</li>
                <li>Bachelor's in Advanced Mathematics - Royal University of Phnom Penh</li>
            </ul>
        </section>
        
        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li>Programming: C++, Python, JavaScript</li>
                <li>Web Development: HTML, CSS, React, Node.js</li>
                <li>Data Science: Machine Learning, Deep Learning, Statistics</li>
                <li>Mathematics: Functional Analysis, Linear Algebra, Probability Theory</li>
            </ul>
        </section>
        
        <section id="projects">
            <h2>Projects</h2>
            <ul>
                <li>Matrix Exponential for ODEs</li>
                <li>Numerical Integration in C++</li>
                <li>Galois Theory and Field Extensions</li>
                <li>Deep Learning Applications in Computer Vision</li>
            </ul>
        </section>
        
        <section id="contact">
            <h2>Contact</h2>
            <p>Email: example@domain.com</p>
            <p>LinkedIn: linkedin.com/in/example</p>
        </section>
        
        <div class="social-icons">
            <a href="#"><i class="fab fa-github"></i></a>
            <a href="#"><i class="fab fa-linkedin"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
        </div>
        
        <button class="button" onclick="alert('Thanks for visiting!')">Download Resume</button>
    </div>
</body>
</html>
