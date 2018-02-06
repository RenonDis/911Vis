# 911Vis

Projet de data visualisation pour le cours 'Interactive data visualisation' à l'Ecole Centrale Lyon (2018).


## Data

Le Dataset utilisé est disponible sur Kaggle : https://www.kaggle.com/mchirico/montcoalert

Description dans [DATA.md](https://github.com/RenonDis/911Vis/blob/master/DATA.md)

## Problème posé

Quelle est la repartition:

  * Temporelle
  * Geographique
  * Catégorielle

Des appels au 911 aux USA pour l'année 2015?

## Visualisations proposées

Base :

  * Heatmap avec la densité d'appels par jour de l'année
  * Stacked Bar chart avec nombre moye d'appels par catégorie par heure
  * Geo Chart avec répartition des appels (densité par commune et marqueur pour type majoritaire? ou couleur pour type)

Focus :

  * Pie chart bilevel avec les categories (1er niveau) et les incidents les plus courants par catégorie (second niveau)
  
Filtrage :

  * Catégorie (tick box)
  * Jour (en cliquant sur la heat map)

Autres interactions :

  * Zoom sur la carte au niveau
    * Etat -> marqueur par commune pour type majoritaire
    * Commune -> discrétisation 
  * Reset de la carte + filtrage lorsqu'une autre action de filtrage est engagée 
