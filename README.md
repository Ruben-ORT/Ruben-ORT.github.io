<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - [Prénom Nom]</title>
  <link rel="stylesheet" href="styles.css">
  <style>
    body {
      background-color: #f3f3f3;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    
    header {
      background-color: #ffffff;
      text-align: center;
      padding: 40px;
    }
    
    h1 {
      font-size: 36px;
      margin: 10px 0;
      color: #333333;
    }
    
    p {
      font-size: 18px;
      margin-bottom: 20px;
      color: #666666;
    }
    
    nav {
      background-color: #333333;
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
      color: #ffffff;
      font-size: 16px;
      text-decoration: none;
      margin: 0 10px;
    }
    
    section {
      background-color: #ffffff;
      padding: 40px;
      margin-bottom: 20px;
    }
    
    h2 {
      font-size: 24px;
      color: #333333;
      margin: 0 0 20px 0;
    }
    
    article {
      margin-bottom: 40px;
    }
    
    article h3 {
      font-size: 20px;
      color: #333333;
      margin-bottom: 10px;
    }
    
    article p {
      color: #666666;
      margin-bottom: 10px;
    }
    
    article img {
      max-width: 100%;
      margin-bottom: 10px;
    }
    
    article a {
      display: block;
      margin-bottom: 10px;
      color: #333333;
      text-decoration: none;
      font-weight: bold;
    }
    
    footer {
      background-color: #333333;
      color: #ffffff;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>[Prénom Nom]</h1>
    <script src="https://tryhackme.com/badge/1995687"></script>
    <p>Élève en 2ème année de BTS SIO, Option SISR</p>
    <script src="https://tryhackme.com/badge/1995687"></script>
  </header>

  <nav>
    <ul>
      <li><a href="#accueil">Accueil</a></li>
      <li><a href="#projets">Projets réalisés</a></li>
      <li><a href="#competences">Compétences techniques</a></li>
      <li><a href="#formation">Formation</a></li>
      <li><a href="#certifications">Certifications</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <section id="accueil">
    <h2>À propos de moi</h2>
    <p>Je suis passionné par les technologies de l'information et je poursuis actuellement un BTS SIO option SISR. Mon objectif est de développer mes compétences en matière d'infrastructure, de systèmes et de réseaux pour devenir un professionnel qualifié dans le domaine de l'informatique.</p>
  </section>

  <section id="projets">
    <h2>Projets réalisés</h2>
    <article>
      <h3>Projet 1</h3>
      <p>Description du projet 1.</p>
      <img src="projet1.jpg" alt="Capture d'écran du projet 1">
      <a href="lien_projet1">Démo du projet 1</a>
      <a href="lien_github_projet1">GitHub du projet 1</a>
    </article>
    <article>
      <h3>Projet 2</h3>
      <p>Description du projet 2.</p>
      <img src="projet2.jpg" alt="Capture d'écran du projet 2">
      <a href="lien_projet2">Démo du projet 2</a>
      <a href="lien_github_projet2">GitHub du projet 2</a>
    </article>
    <!-- Ajoutez plus d'articles pour chaque projet réalisé -->
  </section>

  <section id="competences">
    <h2>Compétences techniques</h2>
    <ul>
      <li>Réseaux</li>
      <li>Systèmes d'exploitation</li>
      <li>Sécurité</li>
      <li>Bases de données</li>
      <li>Programmation</li>
      <li>Administration système</li>
      <!-- Ajoutez plus de compétences spécifiques -->
    </ul>
  </section>

  <section id="formation">
    <h2>Formation</h2>
    <p>BTS SIO (Services Informatiques aux Organisations) - Option SISR</p>
    <p>[Nom de l'établissement] - [Année en cours]</p>
  </section>

  <footer>
    <p>&copy; 2023 [Prénom Nom]. Tous droits réservés.</p>
  </footer>
</body>
</html>
