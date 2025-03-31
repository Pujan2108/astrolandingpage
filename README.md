// src/pages/index.astro
---
import "../styles.css";
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Astro Landing Page</title>
</head>
<body>
    <header>
        <h1>Welcome to My Astro Landing Page</h1>
        <p>Built with Astro for performance and speed.</p>
    </header>
    <section>
        <h2>Features</h2>
        <ul>
            <li>Fast and lightweight</li>
            <li>SEO-friendly</li>
            <li>Easy to deploy</li>
        </ul>
    </section>
    <footer>
        <p>Contact: your@email.com</p>
    </footer>
</body>
</html>

/* src/styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    background-color: #f4f4f4;
}
header {
    background-color: #333;
    color: white;
    padding: 20px;
}
section {
    margin: 20px;
    padding: 20px;
}
footer {
    background-color: #222;
    color: white;
    padding: 10px;
    position: absolute;
    width: 100%;
    bottom: 0;
}
