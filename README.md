# Analyseur de Rapports WhatsApp

L'Analyseur de Rapports WhatsApp est un outil conçu pour extraire et analyser les rapports de maintenance à partir de conversations WhatsApp. Il structure les informations en tâches, todos/observations et autres catégories, facilitant ainsi la gestion et le suivi des interventions.

## Objectif

L'objectif principal de cet outil est de simplifier l'analyse des rapports envoyés via WhatsApp en automatisant l'extraction des informations clés. Cela permet aux utilisateurs de gagner du temps et de réduire les erreurs liées à la saisie manuelle des données.

## Utilisation

### Prérequis

- Un navigateur web moderne (Chrome, Firefox, Safari, etc.)
- Accès à l'application WhatsApp pour copier les conversations

### Instructions

1. **Ouvrir l'outil** : Accédez à l'outil via votre navigateur web.
2. **Coller les rapports** : Copiez les conversations WhatsApp contenant les rapports de maintenance et collez-les dans la zone de texte prévue à cet effet.
3. **Analyser** : Cliquez sur le bouton "Analyser les rapports" pour traiter les données.
4. **Consulter les résultats** : Les informations extraites seront affichées dans un tableau et pourront être exportées au format CSV.

## Fonctionnalités

### Reconnaissance des expressions régulières

L'outil utilise des expressions régulières pour identifier et extraire les différentes parties des rapports :

- **Dates et heures** : Identification des formats de date et d'heure courants.
- **Utilisateurs** : Association des identifiants aux prénoms des utilisateurs.
- **Tâches** : Reconnaissance des tâches effectuées, marquées par des symboles comme ✓, ✔, ☑, -, •.
- **Todos/Observations** : Identification des éléments marqués par le symbole `#`, mettant en avant les actions à entreprendre ou les observations importantes.
- **Autres informations** : Toute autre information non catégorisée.

### Exportation CSV

L'outil permet d'exporter les données analysées au format CSV. Voici un aperçu de la structure du fichier CSV généré :

- **Date** : La date à laquelle l'intervention a été rapportée.
- **User** : Le nom de l'utilisateur ayant effectué le rapport.
- **Task** : La description de la tâche effectuée.
- **Todo / Observation** : Les éléments marqués comme todo ou observations. Utilisez des filtres dans Excel pour extraire rapidement ces éléments et gagner en productivité.
- **Other** : Toute autre information pertinente.

#### Exemple de fichier CSV

```csv
Date,User,Task,Todo / Observation,Other
"01/01/2025","Jean-Sébastien","Tâche effectuée","","Pièces utilisées: XYZ"
"02/01/2025","Dylan","","Vérifier le stock","Problème signalé par le client"
