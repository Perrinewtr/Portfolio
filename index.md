---
layout: default
---
<head>
  <link rel="stylesheet" href="barre.css"> 
  <style>
    section {
      scroll-margin-top: 60px; /* Permet de ne pas cacher le titre lors du défilement */
    }
    h2 {
      color: #68B0AB !important; /* Ajoutez !important pour forcer l'application du style */
    }
    
    h4 {
      color: #68B0AB !important; /* Ajoutez !important pour forcer l'application du style */
    }
    
  </style>

<nav>
  <ul>
    <li><a href="#À propos de moi">À propos de moi</a></li>
    <li><a href="#Projets">Projets</a></li>
    <li><a href="#Compétences">Compétences</a></li>
    <li><a href="#Contact">Contact</a></li>
  </ul>
</nav>

<section id="À propos de moi">
  <h2>À propos de moi</h2>
  <p> Actuellement étudiante en master 1 de Data Sciences en Santé à Ilis, je me spécialise dans l'analyse de données appliquée aux domaines de la santé et de la biologie. <br> <br>
    
Voici mon portfolio, qui rassemble une sélection des projets que j'ai pu réaliser dans le cadre de mes études et de mes expériences professionnelles.<br> <br>

Voici un aperçu de mon parcours professionnel et mes compétences en Data Science. </p> <br> <br> <br>

<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Timeline Interactive</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f4f4f9;
    }

    .timeline-container {
      position: relative;
      max-width: 900px;
      margin: 50px auto;
      padding: 0 30px;
    }

    /* Ligne fine avec flèche à droite */
    .timeline-line {
      position: absolute;
      top: 50%;
      left: 0;
      width: calc(100% - 30px);
      height: 2px;
      background-color: #006f8e;
    }

    .timeline-line::after {
      content: '';
      position: absolute;
      top: 50%;
      right: 0;
      width: 0;
      height: 0;
      border-left: 20px solid #006f8e;
      border-top: 5px solid transparent;
      border-bottom: 5px solid transparent;
      transform: translateY(-50%);
    }

    /* Points interactifs */
    .timeline-point {
      position: absolute;
      top: 50%;
      transform: translate(-50%, -50%);
      width: 12px;
      height: 12px;
      background-color: #006f8e;
      border: 3px solid white;
      border-radius: 50%;
      box-shadow: 0 0 10px rgba(0, 111, 142, 0.5);
      transition: all 0.3s ease-in-out;
      cursor: pointer;
    }

    .timeline-point:hover {
      background-color: #0097b6;
      transform: scale(1.5);
      box-shadow: 0 0 15px rgba(0, 151, 182, 0.7);
    }

    /* Événements avec arrière-plan et animations */
    .timeline-event {
      position: absolute;
      width: 180px;
      font-size: 14px;
      text-align: center;
      color: white;
      background-color: #68B0AB;
      padding: 8px;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      opacity: 0;
      transform: translateY(20px);
      transition: all 0.4s ease-in-out;
      border: 2px solid #9ad0d6; /* Bordure de l'événement */
    }

    .timeline-event.visible {
      opacity: 1;
      transform: translateY(0);
    }

    /* Positionnement des événements alternés */
    .event-above { top: calc(50% - 90px); }
    .event-below { top: calc(50% + 30px); }

    .point1 { left: 10%; }
    .point2 { left: 35%; }
    .point3 { left: 60%; }
    .point4 { left: 85%; }

    .event1 { left: calc(10% - 90px); }
    .event2 { left: calc(35% - 90px); }
    .event3 { left: calc(60% - 90px); }
    .event4 { left: calc(85% - 90px); }

  </style>
</head>
<body>

  <div class="timeline-container">
    <!-- Ligne avec flèche -->
    <div class="timeline-line"></div>

    <!-- Points -->
    <div class="timeline-point point1"></div>
    <div class="timeline-point point2"></div>
    <div class="timeline-point point3"></div>
    <div class="timeline-point point4"></div>

    <div class="timeline-event event1 event-above">
      <strong>2019</strong><br>Baccalauréat Scientifique
    </div>
    <div class="timeline-event event2 event-below">
      <strong>2021</strong><br>Licence Sciences de La Vie
    </div>
    <div class="timeline-event event3 event-above">
      <strong>2023</strong><br>Stage à l'IPMC au CNRS
    </div>
    <div class="timeline-event event4 event-below">
      <strong>2024</strong><br>Master Data Science en Santé
    </div>
  </div>

  <script>
    // Animation d'apparition des événements avec un délai
    document.addEventListener("DOMContentLoaded", function() {
      const events = document.querySelectorAll(".timeline-event");
      events.forEach((event, index) => {
        setTimeout(() => {
          event.classList.add("visible");
        }, index * 500); // Délai entre chaque apparition
      });
    });
  </script>

</body>
</html>

<br> <br> <br> <br> <br> <br>

  <p> Pour un aperçu complet de mes qualifications et expériences professionnelles, n'hésitez pas à consulter mon CV.</p>

<a href="https://raw.githubusercontent.com/Perrinewtr/Portfolio/main/CV%20Perrine_12%3A2024.pdf" download>CV</a>
</section>
 <br>
<section id="Projets">
  <h2>Mes projets</h2>
  <p>Voici les différents projets que j'ai pu réaliser durant mes études : </p>

  <ul>
    <li>
      Projet 1 : Prédiction des maladies hépatiques à partir des taux d'enzymes sanguines. <br>
      <em> Pour en savoir plus : </em><a href="projet.html">Projet 1</a> 
    </li>
    <br> 
    <li>
      Projet 2 : Identification et caractérisation des mutations responsables de la dystrophie musculaire d'Emery-Dreifuss.<br>
      <em> Pour en savoir plus : </em><a href="projet2.html">Projet 2</a>
    </li>
    <br> 
    <li>
      Projet 3 : Analyse de l'impact des facteurs de risque sur l'athérosclérose. <br>
      <em> Pour en savoir plus : </em><a href="arthero.html">Projet 3</a>
    </li>
    <br> 
    <li>
      Projet 4 : Survie de patients dans une unité de soins intensifs. <br>
      <em> Pour en savoir plus : </em><a href="survie.html">Projet 4</a>
    </li>
    <br> 
    <li>
      Projet 5 : Méthode d'Analyse de Données : Clustering Hiérarchique sur des Automobiles. <br>
      <em> Pour en savoir plus : </em><a href="automobile.html">Projet 5</a>
   </li>
</ul>
</section>

 <br>
<section id="Compétences">
  <h2>Mes compétences</h2>
  <h4 style="margin-top: 5px;">Langage de programmation :</h4>
  <ul>
    <li>Python</li>
    <li>R</li>
    <li>SQL</li>
  </ul>
  
  <h4 style="margin-top: 5px;">Outil de Data Sciences :</h4>
  <ul>
    <li>Jupyter, Rstudio, Visual Studio Code, Pycharm</li>
    <li>Outils statistiques</li>
    <li>Gestion et nettoyage des données</li>
    <li>Web scraping</li>
    <li>Web crawling</li>
  </ul>
  
  <h4 style="margin-top: 5px;">Base de données et gestion de données :</h4>
  <ul>
    <li>SQLite</li>
    <li>DataHub</li>
    <li>DBeaver</li>
    <li>GitLab</li>
  </ul>
</section>

 <br>
<section id="Contact">
  <h2>Contact</h2>
  <p> Téléphone 📞 : 0781640860 <br>
    Email 📧 : <a href="mailto:warter.perrine@orange.fr">warter.perrine@orange.fr</a> <br>
    LinkedIn 🔗 : <a href="https://www.linkedin.com/in/perrine-warter-140a3026a" target="_blank">Perrine Warter</a> </p>
</section>

