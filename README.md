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
            text-align: center;
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
        <a href="about.html">About</a>
        <a href="education.html">Education</a>
        <a href="skills.html">Skills</a>
        <a href="projects.html">Projects</a>
        <a href="contact.html">Contact</a>
    </nav>
    <div class="container">
        <h2>Welcome to My Portfolio</h2>
        <p>Click a section above to learn more about me!</p>
        <button class="button" onclick="window.location.href='about.html'">Learn More About Me</button>
    </div>
</body>
</html>
