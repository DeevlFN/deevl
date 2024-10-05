<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mein Shop</title>
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
            padding: 10px 0;
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
        .product {
            border: 1px solid #ccc;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background: #007BFF;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Willkommen in meinem Shop!</h1>
    <nav>
        <a href="#home">Startseite</a>
        <a href="#shop">Shop</a>
        <a href="#info">Informationen</a>
    </nav>
</header>

<div class="container" id="home">
    <h2>Startseite</h2>
    <p>Hier findest du die besten Produkte zu tollen Preisen!</p>
</div>

<div class="container" id="shop">
    <h2>Shop</h2>
    <div class="product">
        <h3>Produkt 1</h3>
        <p>Beschreibung von Produkt 1.</p>
        <p>Preis: 19,99 €</p>
    </div>
    <div class="product">
        <h3>Produkt 2</h3>
        <p>Beschreibung von Produkt 2.</p>
        <p>Preis: 29,99 €</p>
    </div>
    <div class="product">
        <h3>Produkt 3</h3>
        <p>Beschreibung von Produkt 3.</p>
        <p>Preis: 39,99 €</p>
    </div>
</div>

<div class="container" id="info">
    <h2>Informationen</h2>
    <p>Hier kannst du Informationen über unseren Shop und unsere Produkte finden.</p>
    <p>Wir bieten eine Vielzahl von Produkten zu wettbewerbsfähigen Preisen.</p>
</div>

<footer>
    <p>&copy; 2024 Mein Shop. Alle Rechte vorbehalten.</p>
</footer>

</body>
</html>
