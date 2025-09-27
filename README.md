# SDD-BE-meteo


## Folder Structure
Le fichier CSV est à glisser dans le dossier data, à créer pour faire tourner le code. Structure attendue du dossier, avec les dossiers à créer en jaune :  


.  
└── SDD-BE-METEO  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├── <span style="color:gold">data</span>  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── donnees-synop-essentielles-omm.csv  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;│&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── <span style="color:gold">mesures</span>  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├── CR.ipynb  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└── README.md


## Getting Started

1. Cloner ce repo
2. Vérifier que R est installé, ainsi que Python 3.11+
3. Ouvrir CR.ipynb

## Dependencies

- Dépendances standards sdd 

## Consignes 

Le document rendu, sous la forme d'un notebook Jupyter, devra contenir au moins :

    1) Une présentation des données avec plusieurs résumés numériques et graphiques des données.
    2) Un calcul et une étude d'estimateur.
    3) Des tests (au moins un sur un paramètres et une ANOVA).
    4) Une régression et étude de corrélation.
    5) Une ACP et une PLS.
    6) Une méthode de clustering.

L'objectif étant, pour chaque méthode utilisée et illustrée, de répondre aux questions suivantes :

    1) Quelle question est-ce que je me pose sur les données ? Qu'est ce que je veux illustrer ? 
    2) Pourquoi la méthode que je vais utiliser est pertinente ? 
    3) Quelles conclusions j'en retire ? 
    4) Quelles sont les possibles limitations de ce que je propose ? 

## Dataset
Le projet consiste en l'étude du jeu de donnée météo : https://public.opendatasoft.com/api/explore/v2.1/catalog/datasets/donnees-synop-essentielles-omm/exports/csv?lang=fr&qv1=(date%3A%5B2015-08-03T22%3A00%3A00Z%20TO%202025-09-03T21%3A59%3A59Z%5D)&timezone=Europe%2FBerlin&use_labels=true&delimiter=%3B.

Pour récupérer le jeu de données, récupérer le fichier CSV ci-dessus.
