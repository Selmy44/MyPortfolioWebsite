# MyPortfolioWebsite
This is My Portfolio Website 
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
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
            text-align: center;
            padding: 1rem;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 0.5rem;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
        }

        .container {
            max-width: 960px;
            margin: 2rem auto;
            padding: 2rem;
            background-color: #fff;
            border-radius: 5px;
        }

        .project {
            margin-bottom: 1rem;
        }
    </style>
</head>

<body>
    <header>
        <h1>My Portfolio</h1>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="home">
            <h2>Home</h2>
            <p>Welcome to my portfolio website. I am passionate about web development and creating awesome
                user experiences.</p>
        </section>

        <section id="about">
            <h2>About Me</h2>
            <p>I am a web developer with expertise in HTML, CSS, JavaScript, and other web technologies. I love
                to create responsive and interactive websites.</p>
        </section>

        <section id="projects">
            <h2>Projects</h2>
            <div class="project">
                <h3>Project 1</h3>
                <p>Description of Project 1.</p>
            </div>
            <div class="project">
                <h3>Project 2</h3>
                <p>Description of Project 2.</p>
            </div>
        </section>

        <section id="contact">
            <h2>Contact Me</h2>
            <p>Email: example@example.com</p>
        </section>
    </div>

    <script>
        // You can add interactivity using JavaScript here
    </script>
</body>

</html>
