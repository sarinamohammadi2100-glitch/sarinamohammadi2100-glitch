<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            text-align: center;
            padding: 4rem 2rem;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }

        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        nav {
            background: #333;
            padding: 1rem;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1.5rem;
            font-weight: 500;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #667eea;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 3rem 2rem;
        }

        section {
            margin-bottom: 3rem;
        }

        section h2 {
            color: #667eea;
            margin-bottom: 1rem;
            font-size: 2rem;
        }

        .card {
            background: #f4f4f4;
            padding: 2rem;
            border-radius: 8px;
            margin-bottom: 1.5rem;
        }

        .card h3 {
            color: #764ba2;
            margin-bottom: 0.5rem;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 2rem;
        }

        .btn {
            display: inline-block;
            background: #667eea;
            color: white;
            padding: 0.8rem 2rem;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 1rem;
            transition: background 0.3s;
        }

        .btn:hover {
            background: #764ba2;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
        <p>A simple, beautiful website built with HTML & CSS</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <div class="card">
                <p>Hello! I'm a web developer passionate about creating beautiful and functional websites. This is a simple template you can customize to showcase your own content.</p>
            </div>
        </section>

        <section id="projects">
            <h2>My Projects</h2>
            <div class="card">
                <h3>Project One</h3>
                <p>Description of your first project goes here. You can add links, images, or any other content you'd like.</p>
            </div>
            <div class="card">
                <h3>Project Two</h3>
                <p>Description of your second project. Feel free to customize these cards with your actual projects!</p>
            </div>
            <div class="card">
                <h3>Project Three</h3>
                <p>Another project description. You can add as many of these as you need.</p>
            </div>
        </section>

        <section id="contact">
            <h2>Get in Touch</h2>
            <div class="card">
                <p>Feel free to reach out to me through email or social media!</p>
                <a href="mailto:your.email@example.com" class="btn">Contact Me</a>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 My Simple Website. Built with HTML & CSS.</p>
    </footer>
</body>
</html>
