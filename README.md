<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>[Your Name] - [Your Profession]</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            transition: background-color 0.5s;
        }

        header {
            background-color: #333;
            color: white;
            padding: 1em;
            text-align: center;
        }

        section {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            transition: background-color 0.5s;
        }

        h1 {
            color: #333;
        }

        h2 {
            color: #333;
        }

        p {
            line-height: 1.6;
            color: #666;
        }

        a {
            color: #007BFF;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Light theme */
        .light-theme {
            background-color: #f5f5f5;
        }

        .light-theme section {
            background-color: white;
        }

        /* Dark theme */
        .dark-theme {
            background-color: #333;
            color: white;
        }

        .dark-theme section {
            background-color: #444;
            color: white;
        }
    </style>
</head>

<body class="light-theme">

    <header>
        <h1>[Your Name]</h1>
        <p>[Your Profession]</p>
        <button onclick="toggleTheme()">Toggle Theme</button>
    </header>

    <section>
        <h2>About Me</h2>
        <p>Hello! I'm [Your Name], a passionate [Your Profession]. I have a keen interest in [Your Interests or Hobbies],
            and I thrive on exploring new technologies to stay at the forefront of innovation.</p>
    </section>

    <!-- ... Rest of your content ... -->

    <script>
        function toggleTheme() {
            const body = document.body;
            body.classList.toggle('light-theme');
            body.classList.toggle('dark-theme');
        }
    </script>

</body>

</html>
