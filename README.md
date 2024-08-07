<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #fff;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        nav {
            margin: 20px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
        }
        section {
            padding: 20px;
        }
        .profile, .projects, .blog {
            max-width: 800px;
            margin: 0 auto;
        }
        .project, .post {
            background-color: #fff;
            margin-bottom: 20px;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 -2px 4px rgba(0, 0, 0, 0.1);
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Personal Webpage</h1>
        <nav>
            <a href="#profile">About Me</a>
            <a href="#projects">Projects</a>
            <a href="#blog">Blog</a>
        </nav>
    </header>

    <section id="profile" class="profile">
        <h2>About Me</h2>
        <p>This is where your personal introduction goes. You can talk about your background, interests, and anything else you'd like to share.</p>
    </section>

    <section id="projects" class="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project Title</h3>
            <p>Description of the project. You can showcase your work here with images, links, and detailed descriptions.</p>
        </div>
        <!-- Add more projects as needed -->
    </section>

    <section id="blog" class="blog">
        <h2>Blog</h2>
        <div class="post">
            <h3>Blog Post Title</h3>
            <p>Summary of the blog post. Users can click to read more.</p>
            <a href="#">Read More</a>
        </div>
        <!-- Add more blog posts as needed -->
    </section>

    <footer>
        <p>&copy; 2024 Your Name. All rights reserved.</p>
    </footer>
</body>
</html>
