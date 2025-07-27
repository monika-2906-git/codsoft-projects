# codsoft-projects
It includes a portfolio using HTML,CSS,JAVASCRIPT
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="codsoft.css">
</head>

<body>
    <nav class="navbar">
        <div class="logo"> online portfolio</div>
        <ul>
            <li> <a href="#about"> About me</a></li>
            <li> <a href="#skills"> skills</a></li>
            <li> <a href="#projects"> Projects</a></li>
            <li> <a href="#resume"> Resume</a></li>
            <li> <a href="#contact"> contact</a></li>
        </ul>
    </nav>
    <section class="hero">
        <div class="hero-text">
            <h1>MONIKA KUMARI</h1>
            <p> hi, i am a web developer. i build clean functional website using html, css,javascript</p>
            <a href="#about" class="btn">Read More</a>
        </div>
        <div class="hero-img">
            <img src="https://cdn.pixabay.com/photo/2015/07/17/22/43/student-849825_1280.jpg" alt="Portfolio image">
        </div>
    </section>

    <section class="about" id="about">
        <div class="about-img">
            <img src="https://cdn.pixabay.com/photo/2015/07/17/22/43/student-849825_1280.jpg" alt="Portfolio image">
        </div>
        <div class="about-text">
            <h2> About me</h2>
            <p> I am a passionate web developer eager to build imactful web applications and portfolios</p>
            <a href="monika-resume.pdf" download class="btn">Download Resume</a>

        </div>
    </section>
    <section class="skills" id="skills">

        <h2> Skills</h2>
        <ul class="skills-list">
            <li> HTML</li>
            <li> CSS</li>
            <li> JAVA SCRIPT</li>
            <li> GIT AND GITHUB</li>
            <li> responsive web design</li>
        </ul>
    </section>
    <section class="projects" id="projects">
        <h2> Projects</h2>
        <div class="project-card">
            <h3> portfolio website</h3>
            <p> perosnal portfolio showcasing my skills</p>
        </div>
        <div class="project-card">
            <h3> landing page</h3>
            <p> responsive landing page project using html ,css</p>
        </div>
    </section>

    <section class="contact" id="contact">
        <h2> Contact</h2>
        <p> Email:monikasisodiya128@gmail.com</p>
        <p> Phone:9969694522</p>
    </section>
    <footer>
        <p>&copy; 2025 Monika kumari. All rights reserved</p>
    </footer>
</body>

</html>
