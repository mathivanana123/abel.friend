<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Godson A - Portfolio</title>
    <base href="/">
    <link rel="stylesheet" href="styles.css">
    <link rel="icon" type="image/x-icon" href="favicon.ico">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            background-color: #e9efff;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #941919, #c0392b);
            color: #fff;
            text-align: center;
            padding: 3rem 0;
            position: relative;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        .profile-picture {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            position: absolute;
            top: 20px;
            left: 20px;
            border: 3px solid white;
        }

        nav {
            background-color: #222;
            text-align: center;
            padding: 10px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav ul {
            list-style: none;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            transition: 0.3s;
        }

        nav ul li a:hover {
            color: #f39c12;
        }

        .section-content {
            background: white;
            padding: 2rem;
            margin: 1rem;
            border-radius: 15px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s;
        }

        .section-content:hover {
            transform: scale(1.02);
        }

        .download-button {
            display: inline-block;
            background: #333;
            color: white;
            padding: 10px 20px;
            border-radius: 25px;
            text-decoration: none;
            transition: 0.3s;
        }

        .download-button:hover {
            background: #555;
        }

        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #222;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <img src="../src/assets/images/photo.jpg" class="profile-picture" alt="Profile Picture">
        <h1>Godson A</h1>
        <p>Web Developer | AI Enthusiast</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#resume">Resume</a></li>
        </ul>
    </nav>

    <section id="about" class="section-content">
        <h2>About Me</h2>
        <p>I am a passionate web developer specializing in modern frameworks and technologies, including JavaScript, React, and AI-driven solutions.</p>
    </section>

    <section id="education" class="section-content">
        <h2>Education</h2>
        <p>Sri Devi Arts & Science College (University of Madras) - BCA</p>
    </section>

    <section id="skills" class="section-content">
        <h2>Skills</h2>
        <ul>
            <li>Python</li>
            <li>Java</li>
            <li>Web Design</li>
            <li>Spring Boot</li>
            <li>AI Development</li>
            <li>C++</li>
            <li>Excel & Word</li>
        </ul>
    </section>

    <section id="projects" class="section-content">
        <h2>Projects</h2>
        <ul>
            <li><a href="#">IBM CSS</a></li>
            <li><a href="#">LinkedIn Clone</a></li>
            <li><a href="#">IBM Chatbot</a></li>
            <li><a href="#">College Portal</a></li>
        </ul>
    </section>

    <section id="resume" class="section-content">
        <h2>Resume</h2>
        <a href="https://your-resume-link.com" target="_blank" class="download-button">Download CV</a>
    </section>

    <footer>
        <p>&copy; 2025 Godson A</p>
    </footer>

    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });



        
    </script>
</body>
</html>



