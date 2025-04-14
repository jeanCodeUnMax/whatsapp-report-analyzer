# Tests et Gestion des Erreurs

Ce document décrit la stratégie de test, la couverture du code et les mécanismes de gestion des erreurs pour l'Analyseur de Rapports WhatsApp. Assurer des tests robustes et une gestion complète des erreurs est crucial pour maintenir la fiabilité et l'exactitude de l'outil.

## Couverture du Code

### Vue d'ensemble

La couverture du code mesure la quantité de code exécutée lors de l'exécution des tests. Une couverture élevée garantit que la majeure partie de la base de code est testée, réduisant ainsi le risque de bugs non détectés.

### Outils Utilisés

- **Jest** : Un framework de test JavaScript utilisé pour écrire et exécuter des tests.
- **Istanbul** : Un outil qui instrumente votre code JS pour suivre la couverture, intégré avec Jest.

### Génération de Rapports de Couverture

Pour générer un rapport de couverture, exécutez la commande suivante :

```bash
npm test -- --coverage
