<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - [Prénom Nom]</title>
  <link rel="stylesheet" href="styles.css">
  <style>
    /* Styles généraux */
    body {
      background-color: #000;
      color: #00ff00;
      font-family: 'Courier New', monospace;
      margin: 0;
      padding: 0;
    }

    /* Styles de l'en-tête */
    header {
      background-color: #000;
      text-align: center;
      padding: 40px;
    }

    h1 {
      font-size: 36px;
      margin: 10px 0;
    }

    p {
      font-size: 18px;
      margin-bottom: 20px;
    }

    /* Styles de la navigation */
    nav {
      background-color: #000;
      padding: 10px;
      text-align: center;
    }

    nav ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
    }

    nav ul li {
      display: inline;
    }

    nav ul li a {
      color: #00ff00;
      font-size: 16px;
      text-decoration: none;
      margin: 0 10px;
      transition: color 0.3s;
    }

    nav ul li a:hover {
      color: #00cc00;
    }

    /* Styles des sections */
    section {
      background-color: #000;
      padding: 40px;
      margin-bottom: 20px;
    }

    h2 {
      font-size: 24px;
      margin: 0 0 20px 0;
    }

    article {
      margin-bottom: 40px;
    }

    article h3 {
      font-size: 20px;
      margin-bottom: 10px;
    }

    article p {
      margin-bottom: 10px;
    }

    article img {
      max-width: 100%;
      margin-bottom: 10px;
    }

    article a {
      display: block;
      margin-bottom: 10px;
      font-weight: bold;
      transition: color 0.3s;
    }

    article a:hover {
      color: #00cc00;
    }

    /* Styles du pied de page */
    footer {
      background-color: #000;
      text-align: center;
      padding: 20px;
      font-size: 14px;
    }

    footer p {
      margin: 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>[Prénom Nom]</h1>
    <img src="photo.jpg" alt="Photo de [Prénom Nom]">
    <p>Élève en 2ème année de BTS SIO, Option SISR</p>
  </header>

  <nav>
    <ul>
      <li><a href="#accueil">Accueil</a></li>
      <li><a href="#projets">Projets réalisés</a></li>
      <li><a href="#competences">Compétences techniques</a></li>
      <li><a href="#formation">Formation</a></li>
      <li><a href="#certifications">Certifications</a></li>
      <li><a href="#contact">Contact
