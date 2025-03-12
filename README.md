<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Educational Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background-color: #ffffff;
            padding: 20px;
            text-align: center;
            font-size: 24px;
            font-weight: bold;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #ffffff;
            padding: 10px;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        nav a {
            color: #333;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #007BFF;
        }
        .container {
            max-width: 900px;
            margin: 50px auto;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
        }
        .profile {
            display: flex;
            align-items: center;
            gap: 20px;
        }
        .profile img {
            border-radius: 50%;
            width: 100px;
            height: 100px;
        }
        section {
            padding: 20px 0;
            border-bottom: 2px solid #ddd;
        }
    </style>
</head>
<body>
    <header>Educational Profile</header>
    <nav>
        <a href="#home">Home</a>
        <a href="#publications">Publications</a>
        <a href="#talks">Talks</a>
        <a href="#teaching">Teaching</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="home" class="profile">
            <img src="profile.jpg" alt="Profile Picture">
            <div>
                <h2>Your Name</h2>
                <p>Senior Lecturer | Researcher in Applied Mathematics</p>
                <p>Institution Name</p>
            </div>
        </section>
        <section id="publications">
            <h2>Publications</h2>
            <p>List your research papers and articles here.</p>
        </section>
        <section id="talks">
            <h2>Talks</h2>
            <p>Details about invited talks and presentations.</p>
        </section>
        <section id="teaching">
            <h2>Teaching</h2>
            <p>Courses taught and academic contributions.</p>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Email: example@domain.com</p>
            <p>LinkedIn | ResearchGate | Github</p>
        </section>
    </div>
</body>
</html>
