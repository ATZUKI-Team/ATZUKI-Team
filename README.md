<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Koro Obi's Portfolio</title>
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #121212;
            color: #ffffff;
        }
        header {
            background-color: #64ECED;
            color: #121212;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #1f1f1f;
            padding: 10px 0;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.5);
        }
        nav a {
            color: #64ECED;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #ffffff;
        }
        .container {
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .about-me, .portfolio, .contact {
            background-color: #1f1f1f;
            margin-bottom: 20px;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
        }
        h2 {
            color: #64ECED;
            border-bottom: 2px solid #64ECED;
            padding-bottom: 5px;
        }
        a {
            color: #64ECED;
            text-decoration: none;
            transition: color 0.3s ease;
        }
        a:hover {
            color: #ffffff;
        }
        footer {
            background-color: #64ECED;
            color: #121212;
            text-align: center;
            padding: 10px 0;
            box-shadow: 0 -2px 10px rgba(0, 0, 0, 0.5);
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>

<header>
    <h1>Koro Obi's Portfolio</h1>
</header>

<nav>
    <a href="#about">About Me</a>
    <a href="#portfolio">NFT Portfolio</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">
    <section id="about" class="about-me">
        <h2>About Me</h2>
        <p>Hi, I'm Koro Obi, a Graphic Designer and NFT creator. I am also known as a Pixie Script Validator. My passion lies in creating stunning visuals and unique NFT art pieces.</p>
    </section>

    <section id="portfolio" class="portfolio">
        <h2>NFT Portfolio</h2>
        <p>Check out my latest NFT creations on <a href="https://t.me/designinfos" target="_blank">ATZUKI</a>.</p>
    </section>

    <section id="contact" class="contact">
        <h2>Contact</h2>
        <p>If you would like to get in touch, feel free to contact me via my Telegram: <a href="https://t.me/designinfos" target="_blank">https://t.me/designinfos</a>.</p>
    </section>
</div>

<footer>
    <p>&copy; 2024 Koro Obi. All rights reserved.</p>
</footer>

</body>
</html>
