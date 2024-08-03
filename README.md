<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
            line-height: 1.6;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 15px;
            background: #444;
            border-radius: 5px;
            margin: 0 5px;
        }
        nav a:hover {
            background: #555;
        }
        .profile, .skills, .projects, .contact {
            padding: 20px;
            margin: 20px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        h2 {
            color: #333;
        }
        .skills ul, .projects ul {
            list-style-type: none;
            padding: 0;
        }
        .skills ul li, .projects ul li {
            background: #f4f4f4;
            margin: 5px 0;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .contact form {
            display: flex;
            flex-direction: column;
        }
        .contact form label {
            margin: 5px 0;
        }
        .contact form input, .contact form textarea {
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .contact form button {
            background: #333;
            color: #fff;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
        }
        .contact form button:hover {
            background: #555;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Student Portfolio</h1>
            <nav>
                <a href="#profile">Profile</a>
                <a href="#skills">Skills</a>
                <a href="#projects">Projects</a>
                <a href="#contact">Contact</a>
            </nav>
        </div>
    </header>

    <div class="container">
        <section id="profile" class="profile">
            <h2>Profile</h2>
            <p><strong>Name:</strong> GEMBALI LOKESH</p>
            <p><strong>Branch:</strong> Computer Science And Engineering</p>
            <p><strong>About Me:</strong> I am a passionate student with a strong interest in software development and programming. I enjoy learning new technologies and applying them to solve real-world problems.</p>
        </section>

        <section id="skills" class="skills">
            <h2>Skills</h2>
            <ul>
                <li>C & C++ & Java</li>
                <li>HTML & CSS</li>
                <li>JavaScript</li>
                <li>React</li>
                <li>Node.js</li>
                <li>Python</li>
            </ul>
        </section>

        <section id="projects" class="projects">
            <h2>Projects</h2>
            <ul>
                <li>
                    <strong>Project One</strong>: The programming coding with C,C++,Java,Python.
                </li>
                <li>
                    <strong>Project Two</strong>: A task management application built with React and Node.js.
                </li>
                <li>
                    <strong>Project Three</strong>: An e-commerce site developed with Django and PostgreSQL.
                </li>
                <li>
                    <strong>Project Four</strong>: A personal portfolio website using HTML, CSS, and JavaScript.
                </li>
            </ul>
        </section>

        <section id="contact" class="contact">
            <h2>Contact</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>
  
                <button type="submit">Send Message</button>
            </form>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 LOKI</p>
    </footer>
</body>
</html>