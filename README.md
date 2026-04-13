<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Marlo Shop</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      color: #111;
    }

    header {
      background: black;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 22px;
      font-weight: bold;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 15px;
      background: #222;
      padding: 10px;
      flex-wrap: wrap;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-size: 14px;
    }

    .hero {
      text-align: center;
      padding: 50px 20px;
      background: white;
    }

    .hero h1 {
      margin-bottom: 10px;
    }

    .info {
      text-align: center;
      padding: 15px;
      background: #fff;
      margin-top: 10px;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 15px;
      padding: 20px;
    }

    .product {
      background: white;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      transition: 0.3s;
    }

    .product:hover {
      transform: translateY(-5px);
    }

    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 10px 15px;
      background: #25D366;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #111;
      color: white;
      margin-top: 20px;
    }
  </style>
</head>

<body>

<header>
  Marlo Shop
</header>

<nav>
  <a href="#">Accueil</a>
  <a href="#products">Produits</a>
  <a href="#contact">Contact</a>
</nav>

<section class="hero">
  <h1>Bienvenue dans notre boutique</h1>
  <p>Parfum • Sacs • Chaussures • Vêtements • Cuisine</p>
</section>

<section class="info">
  <h2>Pourquoi nous choisir ?</h2>
  <p>✔ Livraison rapide</p>
  <p>✔ Produits de qualité</p>
  <p>✔ Commande directe via WhatsApp</p>
</section>

<section id="products" class="products">

  <div class="product">
    <h3>Parfum Luxe</h3>
    <p>15 000 FCFA</p>
    <a class="btn" href="https://wa.me/22956967812?text=Bonjour%20je%20veux%20acheter%20Parfum%20Luxe" target="_blank">
      Commander
    </a>
  </div>

  <div class="product">
    <h3>Sac Fashion</h3>
    <p>12 000 FCFA</p>
    <a class="btn" href="https://wa.me/22956967812?text=Bonjour%20je%20veux%20acheter%20Sac%20Fashion" target="_blank">
      Commander
    </a>
  </div>

  <div class="product">
    <h3>Chaussures</h3>
    <p>20 000 FCFA</p>
    <a class="btn" href="https://wa.me/22956967812?text=Bonjour%20je%20veux%20acheter%20Chaussures" target="_blank">
      Commander
    </a>
  </div>

  <div class="product">
    <h3>Ustensiles Cuisine</h3>
    <p>8 000 FCFA</p>
    <a class="btn" href="https://wa.me/22956967812?text=Bonjour%20je%20veux%20acheter%20Ustensiles%20Cuisine" target="_blank">
      Commander
    </a>
  </div>

</section>

<footer id="contact">
  <p>Contact WhatsApp : +229 56 96 78 12</p>
</footer>

</body>
</html>
