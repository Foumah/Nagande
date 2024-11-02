<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nagande Platform</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
        }
        header {
            background-color: #ff6600; /* orange */
            color: #ffffff;

            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #008000; /* vert */
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 15px;
            text-decoration: none;
        }
        .container {
            padding: 20px;
        }
        footer {
            background-color: #ff6600; /* orange */
            color: #ffffff;
            text-align: center;

            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .product-card {
            border: 1px solid #ccc;
            border-radius: 8px;
            margin: 10px;
            padding: 15px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            transition: transform 0.2s;
        }
        .product-card:hover {
            transform: scale(1.02);
        }
        .product-title {
            font-size: 18px;
            color: #008000; /* vert */
        }

        .subscription {
            background-color: #f0f0f0;
            border-radius: 8px;
            padding: 15px;
            margin: 20px 0;
        }
        .subscription-title {
            font-size: 20px;
            color: #ff6600; /* orange */
        }
        .search-bar {
            margin: 20px 0;
        }
        .search-bar input {
            width: 80%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .category {
            margin: 20px 0;

        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenue sur Nagande</h1>
        <p>La plateforme de vente et d'achat multi-service</p>
    </header>
    <nav>
        <a href="#vendeurs">Vendeurs</a>
        <a href="#acheteurs">Acheteurs</a>
        <a href="#abonnements">Abonnements</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <div class="search-bar">
            <input type="text" placeholder="Rechercher un produit...">
        </div>


        <h2 id="abonnements">Système d'Abonnement</h2>
        <div class="subscription">
            <h3 class="subscription-title">Niveau 1 : 3.000 FCFA/mois</h3>
            <p>- Accès à la plateforme</p>
            <p>- Mise en ligne de 10 images</p>
            <p>- Statistiques trimestrielles</p>
        </div>
        <div class="subscription">
            <h3 class="subscription-title">Niveau 2 : 10.000 FCFA/mois</h3>
            <p>- Accès à la plateforme</p>
            <p>- Mise en ligne de 40 images</p>
            <p>- Statistiques mensuelles</p>
        </div>
        <div class="subscription">
            <h3 class="subscription-title">Niveau 3 : 20.000 FCFA/mois</h3>
            <p>- Accès à la plateforme</p>

            <p>- Mise en ligne de 200 images, mise en avant</p>
            <p>- Statistiques semestrielles</p>
        </div>

        <h2 id="vendeurs">Espace Vendeurs</h2>
        <p>Tableau de bord pour gérer vos produits :</p>
        <div class="product-card">
            <h2 class="product-title">Nom du Produit</h2>
            <p>Description du produit...</p>
            <p>Prix : 10.000 FCFA</p>
            <p>Statut : En vente</p>
        </div>
        <!-- Répéter pour d'autres produits -->

        <h2 id="acheteurs">Espace Acheteurs</h2>
        <div class="category">

            <h3>Catégories de Produits :</h3>
            <ul>
                <li>Éducation</li>
                <li>Santé</li>
                <li>Beauté</li>
                <li>Habillement</li>
                <li>Électronique</li>
                <li>Restaurants</li>
                <li>Hôtels</li>
            </ul>
        </div>
        
        <h2>Fonctionnalités pour Acheteurs</h2>
        <p>Recherchez des produits par image et laissez des avis sur vos achats !</p>
        
        <h2 id="contact">Contact</h2>
        <p>Pour plus d'informations, contactez-nous à <a 

href="mailto:info@nagande.com">info@nagande.com</a></p>
    </div>
    <footer>
        <p>&copy; 2024 Nagande. Tous droits réservés.</p>
    </footer>
</body>
</html>
