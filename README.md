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
            scroll-behavior: smooth;
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
            position: sticky;
            top: 0;
            z-index: 1000;
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
            text-align: center;
        }
        section {
            padding: 50px 0;
            margin-bottom: 50px;
            border-bottom: 2px solid #333;
        }
        .button {
            background-color: #00adb5;
            color: white;
            padding: 12px 24px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            transition: background 0.3s;
            margin-top: 20px;
        }
        .button:hover {
            background-color: #008c9e;
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
            <p>I am a passionate developer and researcher in mathematics, computing, and deep learning.</p>
        </section>
        <section id="education">
            <h2>Education</h2>
            <p>Master's in Mathematics and Computing - IIT (ISM) Dhanbad</p>
            <p>Bachelor's in Advanced Mathematics - Royal University of Phnom Penh</p>
        </section>
        <section id="skills">
            <h2>Skills</h2>
            <p>Programming: C++, Python, JavaScript</p>
            <p>Machine Learning, Deep Learning, Web Development</p>
        </section>
        <section id="projects">
            <h2>Projects</h2>
            <ul>
                <li>Matrix Exponential for ODEs</li>
                <li>Numerical Integration in C++</li>
                <li>Deep Learning Applications in Computer Vision</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Email: example@domain.com</p>
            <p>LinkedIn: linkedin.com/in/example</p>
        </section>
        <button class="button" onclick="alert('Thank you for visiting!')">Click Me</button>
    </div>
</body>
</html>
