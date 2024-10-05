<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Deevl - Erneuerbare Energien</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #007BFF;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            margin: 10px 0;
        }
        nav a {
            margin: 0 15px;
            color: white;
            text-decoration: none;
        }
        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #007BFF;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
        }
        .card {
            border: 1px solid #ccc;
            padding: 10px;
            border-radius: 5px;
            text-align: center;
        }
    </style>
</head>
<body>

<header>
    <h1>Willkommen bei Deevl</h1>
    <nav>
        <a href="#home">Startseite</a>
        <a href="#services">Dienstleistungen</a>
        <a href="#about">Über uns</a>
        <a href="#contact">Kontakt</a>
    </nav>
</header>

<div class="container" id="home">
    <h2>Startseite</h2>
    <p>Hier bei Deevl setzen wir uns für erneuerbare Energien und nachhaltige Lösungen ein.</p>
</div>

<div class="container" id="services">
    <h2>Dienstleistungen</h2>
    <div class="grid">
        <div class="card">
            <h3>Beratung</h3>
            <p>Beratung zu erneuerbaren Energien.</p>
        </div>
        <div class="card">
            <h3>Installation</h3>
            <p>Installation von Solaranlagen.</p>
        </div>
        <div class="card">
            <h3>Energiemanagement</h3>
            <p>Effizientes Energiemanagement für Unternehmen.</p>
        </div>
        <div class="card">
            <h3>Wartung</h3>
            <p>Regelmäßige Wartung und Überprüfung.</p>
        </div>
    </div>
</div>

<div class="container" id="about">
    <h2>Über uns</h2>
    <p>Deevl ist Ihr Partner für eine nachhaltige Zukunft. Wir arbeiten daran, die Welt mit erneuerbaren Energien zu versorgen.</p>
</div>

<div class="container" id="contact">
    <h2>Kontakt</h2>
    <form>
        <label for="name">Name:</label><br>
        <input type="text" id="name" name="name"><br><br>
        <label for="email">E-Mail:</label><br>
        <input type="email" id="email" name="email"><br><br>
        <label for="message">Nachricht:</label><br>
        <textarea id="message" name="message" rows="4"></textarea><br><br>
        <input type="submit" value="Absenden">
    </form>
</div>

<footer>
    <p>&copy; 2024 Deevl. Alle Rechte vorbehalten.</p>
</footer>

</body>
</html>
