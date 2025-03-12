<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Educational Website</title>
    <style>
        body {
            background-color: #f9f9f9;
            color: #333;
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 24px;
        }
        nav {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 50px;
            max-width: 900px;
            margin: auto;
            background: white;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        section {
            margin-bottom: 40px;
        }
        h2 {
            border-bottom: 2px solid #4CAF50;
            padding-bottom: 5px;
        }
        .button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
            margin-top: 20px;
        }
        .button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>Educational Website</header>
    <nav>
        <a href="#home">Home</a>
        <a href="#courses">Courses</a>
        <a href="#teachers">Teachers</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="home">
            <h2>Welcome to Our Educational Platform</h2>
            <p>We provide high-quality courses in mathematics, programming, and science.</p>
        </section>
        <section id="courses">
            <h2>Our Courses</h2>
            <ul>
                <li>Mathematics for Machine Learning</li>
                <li>Introduction to Programming in Python</li>
                <li>Data Science and AI Fundamentals</li>
            </ul>
        </section>
        <section id="teachers">
            <h2>Meet Our Teachers</h2>
            <p>Our instructors are experts in their fields, with years of experience in academia and industry.</p>
        </section>
        <section id="contact">
            <h2>Contact Us</h2>
            <p>Email: edu@example.com</p>
            <p>Phone: +123456789</p>
        </section>
        <button class="button" onclick="alert('Thank you for visiting our website!')">Click Me</button>
    </div>
</body>
</html>
