<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SolidWorks Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background-color: #222;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        .project {
            display: flex;
            flex-wrap: wrap;
            margin-bottom: 2rem;
            background: white;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            overflow: hidden;
        }

        .project img {
            width: 100%;
            max-width: 400px;
        }

        .project-content {
            padding: 1rem;
            flex: 1;
        }

        .project-content h2 {
            margin: 0 0 1rem;
            font-size: 1.5rem;
            color: #0078d7;
        }

        .project-content p {
            margin: 0 0 1rem;
        }

        .project-content a {
            display: inline-block;
            padding: 0.5rem 1rem;
            background-color: #0078d7;
            color: white;
            text-decoration: none;
            border-radius: 4px;
        }

        .project-content a:hover {
            background-color: #005bb5;
        }

        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #222;
            color: white;
            margin-top: 2rem;
        }
    </style>
</head>

<body>
    <header>
        <h1>SolidWorks Portfolio</h1>
        <p>Showcasing my 3D CAD designs and engineering projects.</p>
    </header>

    <div class="container">
        <!-- Project 1 -->
        <div class="project">
            <img src="project1-image.jpg" alt="Project 1">
            <div class="project-content">
                <h2>3-Legged Microphone Stand</h2>
                <p>A bespoke microphone stand engineered for stability and aesthetic appeal. Designed with precision using SolidWorks.</p>
                <a href="https://github.com/yourusername/project1" target="_blank">View on GitHub</a>
            </div>
        </div>

        <!-- Project 2 -->
        <div class="project">
            <img src="project2-image.jpg" alt="Project 2">
            <div class="project-content">
                <h2>Custom Gearbox Assembly</h2>
                <p>An optimized gearbox assembly showcasing advanced SolidWorks techniques for mechanical design.</p>
                <a href="https://github.com/yourusername/project2" target="_blank">View on GitHub</a>
            </div>
        </div>

        <!-- Add more projects as needed -->
    </div>

    <footer>
        <p>&copy; 2025 Your Name. All Rights Reserved.</p>
    </footer>
</body>

</html>

