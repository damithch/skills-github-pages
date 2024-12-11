---
title: "Welcome to My GitHub Pages"
date: 2024-12-11
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to My GitHub Pages</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: url('https://www.wallpapers13.com/wp-content/uploads/2019/12/technology-circuit-board-programming-code-abstract-wallpaper-2560x1600.jpg') no-repeat center center fixed;
            background-size: cover;
            color: white;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        header {
            text-align: center;
            padding: 100px 20px;
            background: rgba(0, 0, 0, 0.6); /* Dark semi-transparent background */
            margin-bottom: 40px;
            border-radius: 10px;
        }
        header h1 {
            font-size: 3.5em;
            font-weight: bold;
            text-transform: uppercase;
            color: #f5a623;
        }
        header p {
            font-size: 1.2em;
            color: #ddd;
            margin-top: 10px;
            animation: fadeIn 2s ease-in-out;
        }
        section {
            padding: 50px 20px;
        }
        section h2 {
            font-size: 2.5em;
            color: #f5a623;
            text-align: center;
            margin-bottom: 30px;
            animation: fadeIn 2s ease-in-out;
        }
        ul {
            list-style: none;
            padding-left: 0;
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
        }
        li {
            margin: 15px 0;
            font-size: 1.2em;
            width: 300px;
            height: 200px;
            position: relative;
            border-radius: 10px;
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        li a {
            text-decoration: none;
            color: #f5a623;
            font-size: 1.2em;
            display: block;
            height: 100%;
            width: 100%;
            text-align: center;
            line-height: 200px;
            background-color: rgba(0, 0, 0, 0.6);
            transition: background-color 0.3s ease, transform 0.3s ease;
            border-radius: 10px;
        }
        li a:hover {
            background-color: #f5a623;
            color: #000;
            transform: scale(1.05);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
        }
        li a span {
            font-size: 1.5em;
            font-weight: bold;
        }
        .contact {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 40px;
        }
        .contact a {
            font-size: 1.2em;
            color: #f5a623;
            text-decoration: none;
            padding: 10px;
            border: 2px solid #f5a623;
            border-radius: 5px;
            transition: 0.3s;
        }
        .contact a:hover {
            background-color: #f5a623;
            color: #000;
        }
        footer {
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.6);
            color: #ddd;
            margin-top: 50px;
        }

        @keyframes fadeIn {
            0% { opacity: 0; }
            100% { opacity: 1; }
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My GitHub Pages!</h1>
        <p>Hello and welcome to my homepage! I'm **Damith Chandrathilake**, an aspiring software engineer with a focus on **Machine Learning** and **Backend Development**. This page will showcase my projects, ideas, and the work I'm currently doing.</p>
    </header>

    <section>
        <h2>About Me</h2>
        <p>I’m currently studying **Software Engineering** at SLIIT. I am passionate about programming, AI, and solving complex problems.</p>

        <ul>
            <li><a href="#"><span>Python</span></a></li>
            <li><a href="#"><span>Java</span></a></li>
            <li><a href="#"><span>MERN Stack</span></a></li>
            <li><a href="#"><span>Machine Learning</span></a></li>
        </ul>
    </section>

    <section>
        <h2>Projects</h2>
        <ul>
            <li><a href="https://github.com/damithc/ml-model"><span>Project 1: Machine Learning Model</span></a></li>
            <li><a href="https://github.com/damithc/java-backend"><span>Project 2: Java Backend App</span></a></li>
            <li><a href="https://github.com/damithc/mern-app"><span>Project 3: Web App using MERN Stack</span></a></li>
        </ul>
    </section>

    <section>
        <h2>Contact Me</h2>
        <div class="contact">
            <a href="https://www.linkedin.com/in/damithchandrathilake/">LinkedIn</a>
            <a href="mailto:damchandrathilake@gmail.com">Email</a>
        </div>
    </section>

    <footer>
        <p>Thank you for visiting my homepage!</p>
    </footer>

</body>
</html>
