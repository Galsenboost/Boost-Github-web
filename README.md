<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Galsen Boost - Portfolio</title>
    <style>
        /* Styles globaux */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
            scroll-behavior: smooth;
        }
        body {
            background: #121212;
            color: white;
            text-align: center;
        }
        header {
            background: #ff1493;
            padding: 15px;
            font-size: 24px;
            font-weight: bold;
            text-transform: uppercase;
        }
        .logo {
            width: 150px;
            height: auto;
            margin: 10px auto;
            display: block;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin: 20px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            font-size: 18px;
        }
        section {
            padding: 50px 20px;
        }
        .hero {
            font-size: 28px;
            font-weight: bold;
            margin-top: 20px;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .project {
            background: #222;
            padding: 20px;
            border-radius: 10px;
        }
        .contact {
            margin-top: 30px;
        }
        .contact a {
            color: #ff1493;
            text-decoration: none;
            font-weight: bold;
            display: block;
            margin: 5px 0;
        }
        footer {
            background: #ff1493;
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

    <header>
        <img src="logo.jpeg" alt="Galsen Boost Logo" class="logo">
        Galsen Boost
    </header>

    <nav>
        <a href="#accueil">Accueil</a>
        <a href="#apropos">À Propos</a>
        <a href="#projets">Projets</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="accueil">
        <h1 class="hero">Bienvenue sur mon portfolio</h1>
        <p>Découvrez mes projets et mon expertise en développement web.</p>
    </section>

    <section id="apropos">
        <h2>À Propos</h2>
        <p>Je suis un développeur passionné par le web et les technologies modernes.</p>
    </section>

    <section id="projets">
        <h2>Mes Projets</h2>
        <div class="projects">
            <div class="project">Projet 1</div>
            <div class="project">Projet 2</div>
            <div class="project">Projet 3</div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Téléphone : <a href="tel:+221781338532">+221 781338532</a></p>
        <p>Email : <a href="mailto:galsenboost@gmail.com">galsenboost@gmail.com</a></p>
        <p>WhatsApp : <a href="https://wa.me/221781338532" target="_blank">Chat sur WhatsApp</a></p>
        <p>Instagram : <a href="https://www.instagram.com/galsenboost?igsh=OXFob2tnbHpxNTZo&utm_source=qr" target="_blank">Suivez-nous sur Instagram</a></p>
    </section>

    <footer>
        © 2025 Galsen Boost - Tous droits réservés
    </footer>

    <script>
        // Animation simple au scroll
        document.addEventListener("scroll", function() {
            document.body.style.backgroundColor = window.scrollY > 200 ? "#1a1a1a" : "#121212";
        });
    </script>

</body>
</html>
