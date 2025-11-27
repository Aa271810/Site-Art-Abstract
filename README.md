<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Univers Artistique</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin:0; padding:0;
            background:#ffffff;
            color:#333;
        }

        header {
            text-align:center;
            padding:50px 20px;
            background:#f7f7f7;
        }

        header h1 {
            margin:0;
            font-size:2.6em;
            letter-spacing:1px;
        }

        nav {
            margin-top:20px;
        }

        nav a {
            margin:0 15px;
            text-decoration:none;
            color:#444;
            font-weight:bold;
        }

        section {
            max-width:1100px;
            margin:50px auto;
            padding:0 20px;
        }

        h2 {
            text-align:center;
            margin-bottom:30px;
            font-size:2em;
        }

        .gallery {
            display:flex;
            flex-wrap:wrap;
            justify-content:center;
            gap:30px;
        }

        .item {
            width:300px;
            text-align:center;
        }

        .item img {
            width:100%;
            border-radius:8px;
            box-shadow:0 4px 12px rgba(0,0,0,0.1);
        }

        .titre {
            margin-top:10px;
            font-size:0.95em;
            color:#666;
        }

        footer {
            text-align:center;
            padding:20px;
            background:#f7f7f7;
            margin-top:40px;
        }
    </style>
</head>

<body>

<header>
    <h1>Mon Univers Artistique</h1>
    <nav>
        <a href="#portfolio">Portfolio</a>
        <a href="#explorations">Explorations</a>
        <a href="#apropos">À propos</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<!-- PORTFOLIO PRINCIPAL -->
<section id="portfolio">
    <h2>Portfolio</h2>

    <div class="gallery">

        <div class="item">
            <img src="img/img1.jpg" alt="Résonance Lumineuse – 2024">
            <p class="titre">Résonance Lumineuse – 2024</p>
        </div>

        <div class="item">
            <img src="img/img2.jpg" alt="Fragments de Matière – 2024">
            <p class="titre">Fragments de Matière – 2024</p>
        </div>

        <div class="item">
            <img src="img/img3.jpg" alt="Relief Vibratoire – 2024">
            <p class="titre">Relief Vibratoire – 2024</p>
        </div>

        <div class="item">
            <img src="img/img4.jpg" alt="Flux Organique – 2024">
            <p class="titre">Flux Organique – 2024</p>
        </div>

        <div class="item">
            <img src="img/img5.jpg" alt="Éclosion Chromatique – 2024">
            <p class="titre">Éclosion Chromatique – 2024</p>
        </div>

        <div class="item">
            <img src="img/img6.jpg" alt="Structure Sensible – 2024">
            <p class="titre">Structure Sensible – 2024</p>
        </div>

        <div class="item">
            <img src="img/img7.jpg" alt="Lumière Dorée – 2024">
            <p class="titre">Lumière Dorée – 2024</p>
        </div>

        <div class="item">
            <img src="img/img8.jpg" alt="Impulsion Intérieure – 2024">
            <p class="titre">Impulsion Intérieure – 2024</p>
        </div>

        <div class="item">
            <img src="img/img9.jpg" alt="Souffle Doux – 2024">
            <p class="titre">Souffle Doux – 2024</p>
        </div>

        <div class="item">
            <img src="img/img10.jpg" alt="Expansion – 2024">
            <p class="titre">Expansion – 2024</p>
        </div>

    </div>
</section>

<!-- GALERIE SECONDAIRE -->
<section id="explorations">
    <h2>Explorations & Détails</h2>

    <div class="gallery">
        <div class="item">
            <img src="img/img11.jpg" alt="Détail Doré">
            <p class="titre">Détail Doré</p>
        </div>

        <div class="item">
            <img src="img/img12.jpg" alt="Texture Profonde">
            <p class="titre">Texture Profonde</p>
        </div>

        <div class="item">
            <img src="img/img13.jpg" alt="Éclat Métallique">
            <p class="titre">Éclat Métallique</p>
        </div>

        <div class="item">
            <img src="img/img14.jpg" alt="Mouvement Matière">
            <p class="titre">Mouvement Matière</p>
        </div>

        <div class="item">
            <img src="img/img15.jpg" alt="Énergie Fine">
            <p class="titre">Énergie Fine</p>
        </div>
    </div>
</section>

<!-- A PROPOS -->
<section id="apropos">
    <h2>À propos</h2>
    <p>
        Mon travail explore l’art abstrait à travers la lumière, la texture et l’énergie.  
        Chaque œuvre est un fragment de sensations, une vibration matérialisée.  
        Bienvenue dans un univers organique, intuitif et profondément sensoriel.
    </p>
</section>

<!-- CONTACT -->
<section id="contact">
    <h2>Contact</h2>
    <p>Email : monemail@example.com</p>
    <p>Instagram : <a href="https://instagram.com/tonpseudo" target="_blank">@tonpseudo</a></p>
</section>

<footer>
    <p>&copy; 2025 Mon Univers Artistique</p>
</footer>

</body>
</html>

