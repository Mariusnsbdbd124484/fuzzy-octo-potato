# fuzzy-octo-potato
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LGM Bijouterie</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fdf5e6;
        }
        header {
            background-color: #8b4513;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #deb887;
            padding: 10px;
        }
        nav a {
            color: #ffffff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .main {
            padding: 20px;
            text-align: center;
        }
        .btn {
            background-color: #ff4500;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        .btn:hover {
            background-color: #dc143c;
        }
        footer {
            background-color: #8b4513;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .product {
            border: 1px solid #ccc;
            padding: 10px;
            margin: 10px auto;
            max-width: 300px;
            border-radius: 8px;
            background-color: #ffffff;
        }
        .highlight {
            color: #ff4500;
            font-weight: bold;
        }
        .new-badge {
            display: inline-block;
            background-color: #ffa500;
            color: white;
            padding: 5px 10px;
            border-radius: 12px;
            font-size: 12px;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>LGM Bijouterie</h1>
    <p>Bracelets intemporels pour femme et homme</p>
</header>

<nav>
    <a href="#accueil">Accueil</a>
    <a href="#a-propos">À propos</a>
    <a href="#compte">Créer un compte</a>
    <a href="#paiement">Paiement</a>
</nav>

<div id="accueil" class="main">
    <div class="product">
        <span class="new-badge">Nouveauté</span>
        <h2>Bracelet Intemporel</h2>
        <p>Taille disponible : 15 cm, 17 cm, 19 cm</p>
        <p class="highlight">Prix : 15€</p>
        <button class="btn">Acheter maintenant</button>
    </div>
</div>

<div id="a-propos" class="main">
    <h2>À propos</h2>
    <p>Je m'appelle <strong>Marius</strong>, et je fabrique ces bracelets pour leur grand esthétisme et confort. J'ai choisi des matériaux de grande qualité pour vous offrir le meilleur.</p>
    <p>Pour toute question, contactez-moi : <a href="mailto:mariuslagrue78@gmail.com">mariuslagrue78@gmail.com</a></p>
</div>

<div id="compte" class="main">
    <h2>Créer un compte</h2>
    <form>
        <label for="prenom">Prénom :</label><br>
        <input type="text" id="prenom" name="prenom" required><br><br>

        <label for="nom">Nom :</label><br>
        <input type="text" id="nom" name="nom" required><br><br>

        <label for="date-naissance">Date de naissance :</label><br>
        <input type="date" id="date-naissance" name="date-naissance" required><br><br>

        <label for="adresse">Adresse :</label><br>
        <input type="text" id="adresse" name="adresse" required><br><br>

        <label for="email">Adresse mail :</label><br>
        <input type="email" id="email" name="email" required><br><br>

        <button class="btn" type="submit">Créer mon compte</button>
    </form>
</div>

<div id="paiement" class="main">
    <h2>Paiement</h2>
    <p>Veuillez choisir un mode de paiement :</p>
    <form>
        <label><input type="radio" name="paiement" value="carte" required> Carte bancaire</label><br>
        <label><input type="radio" name="paiement" value="paypal" required> PayPal</label><br>
        <label><input type="radio" name="paiement" value="virement" required> Virement bancaire</label><br><br>

        <p>L'argent sera envoyé à : <strong>mariuslagrue78@gmail.com</strong></p>
        <button class="btn" type="submit">Payer</button>
    </form>
</div>

<footer>
    <p>&copy; 2024 LGM Bijouterie. Tous droits réservés.</p>
</footer>

</body>
</html>
