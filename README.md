<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AMICALE DES JEUNES ELEVES ET ETUDIANTS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            background: #f9f9f9;
            color: #22aaf8;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(135deg, #4670a8, #355485);
            color: white;
            padding: 2rem 0;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .logo {
            max-width: 150px;
            display: block;
            margin: 0 auto 10px;
            border-radius: 50%;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 30px;
            padding: 1rem 0;
            position: sticky;
            top: 0;
            background: #355485;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        nav a {
            text-decoration: none;
            color: white;
            font-weight: bold;
            transition: color 0.3s ease, transform 0.3s ease;
        }

        nav a:hover {
            color: #22aaf8;
            transform: scale(1.1);
        }

        .container {
            max-width: 1100px;
            margin: 20px auto;
            padding: 0 20px;
        }

        footer {
            text-align: center;
            padding: 1rem 0;
            background: #6376b4;
            color: white;
        }

        @media (max-width: 600px) {
            nav {
                flex-direction: column;
                text-align: center;
            }
        }
    </style>
</head>
<body>

    <header>
        <img src="421848661_680553287580540_2963820430763456727_n.jpg" alt="Logo de l'AJE" class="logo">
        <h1>Bienvenue sur le site officiel de l'AJE</h1>
    </header>

    <nav>
        <a href="accueil.html">Accueil</a>
        <a href="apropos.html">À Propos</a>
        <a href="contact.html">Contact</a>
        <a href="galerie.html">Galerie</a>
        <a href="chat.html">Chat des Commissions</a>
    </nav>

    <footer>
        &copy; 2025 AMICALE DES JEUNES ELEES ET ÉTUDIANT. 788674075.
    </footer>

</body>
</html>

