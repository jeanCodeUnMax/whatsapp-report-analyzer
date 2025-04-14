# Présentation de l'Analyseur de Rapports WhatsApp

## Introduction

Bienvenue dans la présentation de l'Analyseur de Rapports WhatsApp, un outil conçu pour rationaliser l'extraction et l'analyse des rapports de maintenance à partir de conversations WhatsApp. Cet outil vise à améliorer la productivité et à réduire les erreurs de saisie manuelle des données.

## Fonctionnalités Clés

### Analyse Automatisée des Rapports

- **Extraction de Données Sans Effort** : Extrayez automatiquement les informations clés des conversations WhatsApp.
- **Sortie Structurée** : Organisez les données en tâches, todos/observations et autres catégories pour une gestion facile.

### Utilisation des Expressions Régulières

- **Reconnaissance des Dates et Heures** : Identifiez et formatez diverses structures de date et d'heure.
- **Identification des Utilisateurs** : Associez les identifiants aux noms des utilisateurs pour une attribution claire.
- **Marqueurs de Tâches et Todos** : Utilisez des symboles (✓, ✔, ☑, -, •) pour les tâches et `#` pour les todos/observations afin de mettre en avant les actions importantes.

### Fonctionnalité d'Exportation CSV

- **Exportation des Données** : Exportez les données analysées au format CSV pour un traitement ultérieur dans des outils comme Excel.
- **Structure du Fichier CSV** :
  ```csv
  Date,User,Task,Todo / Observation,Other
  "01/01/2025","Jean-Sébastien","Tâche effectuée","","Pièces utilisées: XYZ"
  "02/01/2025","Dylan","","Vérifier le stock","Problème signalé par le client"
