<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Safar Saydshoev's Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#resume">Resume</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    <section id="home">
        <h1>Welcome to Safar Saydshoev's Portfolio</h1>
        <p>Hi, I'm Safar. I am a passionate developer with experience in various technologies. Explore my portfolio to learn more about my work and skills.</p>
    </section>
    <section id="about">
        <h2>About Me</h2>
        <p>Detail description about your background, skills, and experiences.</p>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <!-- Add your projects here -->
    </section>
    <section id="resume">
        <h2>Resume</h2>
        <a href="resume.pdf" download>Download My Resume</a>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2025 Safar Saydshoev. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
