  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resume</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .section {
            padding: 2em 0;
        }
        .section:nth-of-type(even) {
            background-color: #e4e4e4;
        }
        h2 {
            text-align: center;
            margin-bottom: 1em;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        li {
            background: #fff;
            margin: .5em 0;
            padding: 1em;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1em 0;
            margin-top: 2em;
        }
        .project-button {
            display: block;
            width: 200px;
            margin: 1em auto;
            padding: 1em;
            text-align: center;
            background-color: #333;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }
        .project-button img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>John Doe</h1>
        <p>Web Developer | Software Engineer</p>
    </header>
    <div class="container">
        <section class="section" id="profile">
            <h2>Profile</h2>
            <p>Experienced web developer with a strong background in JavaScript, HTML, CSS, and various frameworks. Passionate about building efficient and scalable web applications.</p>
        </section>
        <section class="section" id="experience">
            <h2>Experience</h2>
            <ul>
                <li>Job Title 1 - Company Name<br>Duration<br>Description of responsibilities and achievements.</li>
                <li>Job Title 2 - Company Name<br>Duration<br>Description of responsibilities and achievements.</li>
            </ul>
        </section>
        <section class="section" id="education">
            <h2>Education</h2>
            <ul>
                <li>Degree - University<br>Year of Graduation<br>Description (optional).</li>
            </ul>
        </section>
        <section class="section" id="projects">
            <h2>Projects</h2>
            <a href="https://github.com/manikandan9159/check.git" class="project-button">
                <img src="https://bpincontrol.in/wp-content/uploads/2023/08/Heart-Disease.jpg " alt="Project 1 Image">
                <p>View Project 1</p>
            </a>
            <a href="https://example.com/project2" class="project-button">
                <img src="path/to/project2-image.jpg" alt="Project 2 Image">
                <p>View Project 2</p>
            </a>
            <a href="https://example.com/project3" class="project-button">
                <img src="path/to/project3-image.jpg" alt="Project 3 Image">
                <p>View Project 3</p>
            </a>
             <a href="https://example.com/project3" class="project-button">
                <img src="path/to/project3-image.jpg" alt="Project 4 Image">
                <p>View Project 4</p>
            </a>
        </section>
        <section class="section" id="skills">
            <h2>Skills</h2>
            <ul>
                <li>JavaScript</li>
                <li>HTML & CSS</li>
                <li>React</li>
                <li>Node.js</li>
            </ul>
        </section>
        <section class="section" id="contact">
            <h2>Contact Information</h2>
            <p>Email: <a href="mailto:john.doe@example.com">john.doe@example.com</a></p>
            <p>Phone: (123) 456-7890</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 John Doe. All rights reserved.</p>
    </footer>
</body>
</html>
