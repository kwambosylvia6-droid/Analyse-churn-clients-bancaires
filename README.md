# Analyse-churn-clients-bancaires
Mon premier projet pratiques d'analyse de données, Exploration (EDA), nettoyage des données et création d'un Dashboard.

##  Présentation du projet

Ce projet consiste à analyser l'attrition des clients d'une banque afin d'identifier les principaux facteurs associés au départ des clients.

L'analyse a été réalisée avec trois outils principaux :

- Python pour l'exploration et l'analyse des données
- SQL pour l'analyse des données et les questions métier
- Power BI pour la création du tableau de bord interactif

## Objectifs

L'objectif du projet est de :

- mesurer le taux d'attrition des clients ;
- identifier les profils de clients les plus susceptibles de partir ;
- analyser l'attrition selon différents critères ;
- créer des indicateurs clés de performance ;
- présenter les résultats dans un tableau de bord interactif.

##  Données

Le jeu de données contient des informations sur les clients bancaires, notamment :

- Score de crédit
- Pays
- Sexe
- Âge
- Ancienneté
- Solde bancaire
- Nombre de produits
- Carte de crédit
- Activité du client
- Salaire estimé
- Statut d'attrition

La variable `Exited` indique si le client a quitté la banque :

- `0` : client resté
- `1` : client parti

##  Analyse avec Python

Python et Pandas ont été utilisés pour :

- explorer les données ;
- vérifier les valeurs manquantes ;
- vérifier les doublons ;
- analyser les statistiques descriptives ;
- étudier la répartition des clients ;
- analyser les facteurs associés à l'attrition ;
- créer des visualisations.

Bibliothèques utilisées :

- Pandas
- Matplotlib
- Seaborn

##  Analyse avec SQL

SQL a été utilisé pour réaliser différentes analyses métier :

- nombre total de clients ;
- nombre de clients partis ;
- taux d'attrition ;
- attrition par pays ;
- attrition par sexe ;
- attrition selon l'âge ;
- attrition selon le nombre de produits ;
- attrition selon l'activité du client ;
- analyse des soldes ;
- segmentation des clients.

Techniques SQL utilisées :

- SELECT
- WHERE
- GROUP BY
- ORDER BY
- HAVING
- sous-requêtes
- CTE

##  Tableau de bord Power BI

Le tableau de bord permet de suivre notamment :

- Nombre total de clients
- Clients partis
- Clients restés
- Taux d'attrition
- Âge moyen
- Attrition par pays
- Attrition par sexe
- Attrition par activité
- Attrition selon le nombre de produits
- Attrition selon les groupes d'âge

### Aperçu du tableau de bord

voir dans les images du projet

##  Outils utilisés

Python | Exploration et analyse 
Pandas | Manipulation des données 
Matplotlib | Visualisation 
Seaborn | Visualisation 
SQL | Analyse des données 
Power BI | Tableau de bord 
GitHub | Documentation du projet 

##  Structure du projet

```text
analyse-churn-clients-bancaires/
│
├── donnees/
│   └── clients_bancaires.csv
│
├── python/
│   └── analyse_churn.ipynb
│
├── sql/
│   └── analyse_churn.sql
│
├── powerbi/
│   └── tableau_de_bord_churn.pbix
│
├── images/
│   └── tableau_de_bord.png
│
└── README.md
