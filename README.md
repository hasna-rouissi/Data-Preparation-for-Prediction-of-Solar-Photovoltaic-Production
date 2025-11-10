+ Description

Ce projet vise à analyser et modéliser la production d’énergie solaire (Active Power) à partir de données temporelles réelles.
L’objectif est de prévoir la puissance produite par un panneau photovoltaïque en fonction de conditions météorologiques et de facteurs temporels (heure, saison, durée d’ensoleillement…).

Le pipeline de traitement comprend :

Exploration et nettoyage des données (gestion des valeurs manquantes, rééchantillonnage temporel).

Fusion avec les données du lever et coucher du soleil.

Détection et correction des anomalies avec l’algorithme DBSCAN.

Interpolation et enrichissement des données (ajout des saisons et du temps écoulé depuis le lever du soleil).

Préparation au Machine Learning pour la prédiction de la puissance solaire.
