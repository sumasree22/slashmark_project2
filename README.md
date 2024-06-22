# slashmark_project2
Task 2 : Basic Portfolio Website

You must try making your own portfolio website for yourself. Showcase your projects, your social media handles, your experience on the website. You can refer to some templates available for free on Google for that.


#HTML code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h1>Hello, I'm [Your Name]</h1>
        <p>Welcome to my portfolio website. I'm a [Your Profession] with experience in [Your Skills].</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>Description of project 1.</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>Description of project 2.</p>
        </div>
        <!-- Add more projects as needed -->
    </section>

    <section id="experience">
        <h2>Experience</h2>
        <div class="job">
            <h3>Job Title at Company</h3>
            <p>Description of your role and responsibilities.</p>
        </div>
        <!-- Add more job experiences as needed -->
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>You can find me on:</p>
        <ul>
            <li><a href="https://linkedin.com/in/yourprofile" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a></li>
            <li><a href="https://github.com/yourusername" target="_blank"><i class="fab fa-github"></i> GitHub</a></li>
            <!-- Add more social media links as needed -->
        </ul>
    </section>

    <footer>
        <p>&copy; 2024 [Your Name]. All rights reserved.</p>
    </footer>
</body>
</html>
#css code
<style>
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 1rem;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 2rem;
    max-width: 800px;
    margin: 0 auto;
}

#about {
    background: #f4f4f4;
    text-align: center;
}

.project, .job {
    margin-bottom: 1.5rem;
}

#contact ul {
    list-style: none;
    padding: 0;
    text-align: center;
}

#contact ul li {
    display: inline;
    margin: 0 1rem;
}

#contact ul li a {
    text-decoration: none;
    color: #333;
    font-size: 1.2rem;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
</style>
