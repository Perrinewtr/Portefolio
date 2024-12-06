<head>
  <link rel="stylesheet" href="barre.css"> 
  <style>
    section {
      scroll-margin-top: 60px; /* Permet de ne pas cacher le titre lors du défilement */
    }
  </style>
</head>

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

<head>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/taucharts@2/dist/taucharts.min.css">
  <script src="https://cdn.jsdelivr.net/npm/taucharts@2/dist/taucharts.min.js"></script>
</head>
<body>
  <div id="timeline"></div>
  <script>
    var chart = new Taucharts.Chart({
      type: 'line',
      data: [
        { date: '2020-01-01', milestone: 'Début du master' },
        { date: '2021-06-01', milestone: 'Premier stage en data science' },
        { date: '2024-12-01', milestone: 'Projet de portfolio' }
      ],
      x: 'date',
      y: 'milestone',
      plugins: [Taucharts.api.plugins.get('tooltip')], // Info au survol
    });
    chart.renderTo('#timeline');
  </script>
</body>

Découvrez mon parcours professionnel et mes compétences en Data Science à travers mon CV <br> ci-dessous. </p>

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
