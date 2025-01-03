---
layout: default
title: "Projet 5 - Méthode d'Analyse de Données : Clustering Hiérarchique sur des Automobiles"
---

<div style="font-size: 16px;">
  <strong>Titre :</strong> Méthode d'Analyse de Données : Clustering Hiérarchique sur des Automobiles
  <br><br>

  <strong>Objectif :</strong> Construction de clusters à partir de données d'automobiles, et analyse de leur consommation de carburant et divers aspects de leur conception et performances. En utilisant la méthode HCPC (Hierarchical Clustering on Principal Component), qui combine l'Analyse en Composantes Principales (ACP) et le clustering hiérarchique, nous avons segmenté un jeu de données de 32 modèles de voitures (1973-1974) en fonction de 11 variables. Cela a permis d'identifier des groupes naturels dans les données et de mieux comprendre les relations entre ces variables.
  <br><br>

  <strong>Langages :</strong> R
  <br><br>

  <strong>Outils :</strong> Tests de corrélation, ACP (Analyse en Composantes Principales), HCPC (Hierarchical Clustering on Principal Component)
  <br><br>
</div>

<div style="display: flex; gap: 20px; justify-content: center; margin-bottom: 20px;">
  <a href="https://Perrinewtr.github.io/Portfolio/automobile.pdf" target="_blank" class="button-link">📊 Voir le projet</a>
  <a href="https://raw.githubusercontent.com/Perrinewtr/Portfolio/main/automobile.pdf" class="button-link">📥 Télécharger le projet</a>
</div>


<div style="display: flex; gap: 10px; justify-content: center;">
  <a href="{{ site.baseurl }}/projet" class="projet-link">Projet 1  |</a>
  <a href="{{ site.baseurl }}/projet2" class="projet-link">Projet 2  |</a>
  <a href="{{ site.baseurl }}/arthero" class="projet-link">Projet 3  |</a>
  <a href="{{ site.baseurl }}/survie" class="projet-link">Projet 4  |</a>
  <a href="{{ site.baseurl }}/bibliometrie" class="projet-link">Projet 6 </a>
</div>

<style>
  .button-link {
      padding: 10px 20px;
      background-color: #68B0AB;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      font-size: 16px;
      font-weight: bold;
      transition: background-color 0.3s;
      display: inline-block;
  }

  .button-link:hover {
      background-color: #4a8b83; 
  }


  .projet-link {
      color: #68B0AB;
      text-decoration: none;
      font-size: 15px;
      font-weight: normal; 
  }

  .projet-link:hover {
      text-decoration: underline;
      color: #4a8b83;
  }
</style>

<div style="position: fixed; bottom: 10px; right: 20px">
  <a href="{{ site.baseurl }}/index.html" class="return-link">Accueil</a>
</div>
