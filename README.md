<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Awesome Website</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
        }

        header {
            background: linear-gradient(135deg, #6366f1 0%, #8b5cf6 100%);
            color: white;
            text-align: center;
            padding: 5rem 2rem;
            animation: fadeIn 1s ease-in;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
        }

        header p {
            font-size: 1.3rem;
            opacity: 0.95;
        }

        nav {
            background: #1f2937;
            padding: 1rem;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 1.5rem;
            font-weight: 600;
            transition: all 0.3s;
            padding: 0.5rem 1rem;
            border-radius: 5px;
        }

        nav a:hover {
            background: #6366f1;
            transform: translateY(-2px);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 4rem 2rem;
        }

        section {
            margin-bottom: 4rem;
        }

        section h2 {
            color: #6366f1;
            margin-bottom: 2rem;
            font-size: 2.5rem;
            text-align: center;
        }

        .about-content {
            background: linear-gradient(135deg, #667eea22 0%, #764ba222 100%);
            padding: 3rem;
            border-radius: 15px;
            text-align: center;
            font-size: 1.2rem;
        }

        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .project-card {
            background: white;
            padding: 2rem;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: all 0.3s;
        }

        .project-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 25px rgba(99,102,241,0.3);
        }

        .project-card h3 {
            color: #8b5cf6;
            margin-bottom: 1rem;
            font-size: 1.5rem;
        }

        .project-card p {
            color: #666;
            margin-bottom: 1rem;
        }

        .btn {
            display: inline-block;
            background: linear-gradient(135deg, #6366f1 0%, #8b5cf6 100%);
            color: white;
            padding: 0.8rem 2rem;
            text-decoration: none;
            border-radius: 50px;
            margin-top: 1rem;
            transition: all 0.3s;
            font-weight: 600;
        }

        .btn:hover {
            transform: scale(1.05);
            box-shadow: 0 5px 15px rgba(99,102,241,0.4);
        }

        .contact-box {
            background: linear-gradient(135deg, #6366f1 0%, #8b5cf6 100%);
            color: white;
            padding: 3rem;
            border-radius: 15px;
            text-align: center;
        }

        .contact-box p {
            font-size: 1.2rem;
            margin-bottom: 1.5rem;
        }

        .contact-box .btn {
            background: white;
            color: #6366f1;
        }

        .contact-box .btn:hover {
            background: #f3f4f6;
        }

        footer {
            background: #1f2937;
            color: white;
            text-align: center;
            padding: 2rem;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }
            
            nav a {
                display: block;
                margin: 0.5rem 0;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>🚀 Welcome to My Website</h1>
        <p>Building amazing things on the web</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <section id="about">
            <h2>About Me</h2>
            <div class="about-content">
                <p>👋 Hi! I'm passionate about creating beautiful and functional websites. This is my personal space on the web where I share my work and ideas. Feel free to explore and get in touch!</p>
            </div>
        </section>

        <section id="projects">
            <h2>My Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <h3>🎨 Project One</h3>
                    <p>An amazing web application that solves real problems. Built with modern technologies and best practices.</p>
                    <a href="#" class="btn">View Project</a>
                </div>
                <div class="project-card">
                    <h3>💻 Project Two</h3>
                    <p>A creative solution that makes life easier. Featuring responsive design and smooth user experience.</p>
                    <a href="#" class="btn">View Project</a>
                </div>
                <div class="project-card">
                    <h3>🌟 Project Three</h3>
                    <p>An innovative tool that pushes boundaries. Designed with performance and accessibility in mind.</p>
                    <a href="#" class="btn">View Project</a>
                </div>
            </div>
        </section>

        <section id="contact">
            <h2>Get in Touch</h2>
            <div class="contact-box">
                <p>💌 Have a project in mind or just want to chat? I'd love to hear from you!</p>
                <a href="mailto:your.email@example.com" class="btn">Send Me an Email</a>
            </div>
        </section>
    </div>

    <footer>
        <p>© 2024 My Website | Made with ❤️ and HTML</p>
    </footer>
</body>
</html>
