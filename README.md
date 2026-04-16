# Contexte du projet

Ce projet consiste à créer un dashboard interactif avec **Streamlit** connecté à une base de données PostgreSQL.

L’objectif est d’analyser les données financières de manière simple et visuelle pour aider à la prise de décision.

---

## Objectifs

* Connexion à PostgreSQL via SQLAlchemy
* Création d’un dashboard multi-pages
* Affichage des KPIs importants
* Visualisations (bar, line, pie, scatter, heatmap)
* Ajout de filtres interactifs
* Détection des clients à risque
* Export des données en CSV

---

## Pages du dashboard

### Page 1 : Vue Exécutive

* KPIs (CA, clients, volume…)
* Évolution des transactions
* CA par agence et produit
* Répartition des clients par segment

---

### Page 2 : Analyse des Risques

* Heatmap des corrélations
* Scatter plot score crédit vs montant
* Top 10 clients à risque

---

## Filtres interactifs

* Agence
* Segment client
* Produit
* Période

 Tous les graphiques changent selon les filtres

---

## Export

* Téléchargement des données filtrées en CSV

---

## Résultat

Un dashboard interactif qui permet une analyse rapide et efficace des données financières.
