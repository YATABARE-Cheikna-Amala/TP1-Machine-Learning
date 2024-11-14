# README - Analyse et Optimisation des Modèles de Régression : Elastic Net, Ridge et Lasso

## Introduction

Ce projet se compose de deux exercices principaux :  
1. **Exercice 1** : Analyse des résultats du modèle **Elastic Net** et comparaison des performances entre le jeu d'entraînement et le jeu de test.  
2. **Exercice 2** : Optimisation des hyperparamètres dans les modèles **Elastic Net**, **Ridge** et **Lasso**, et sélection du meilleur modèle en fonction des résultats obtenus.

### Objectifs

- **Exercice 1** : Analyser les résultats obtenus avec le modèle **Elastic Net**, évaluer la performance en termes de \(R^2\) et d'autres métriques (MSE, RMSE, MAE), et comparer les performances sur le jeu de test et le jeu d'entraînement.
- **Exercice 2** : Optimiser les hyperparamètres pour les trois modèles de régression (Elastic Net, Ridge, Lasso) et sélectionner le modèle offrant la meilleure performance, en termes de \(R^2\) et d'autres critères.

## Méthodologie

### Données

Le jeu de données contient plusieurs variables explicatives, telles que :
- `is_genuine`
- `diagonal`
- `height_left`
- `height_right`
- `margin_up`
- `length`

Ces variables ont été utilisées pour prédire une variable cible continue.

### Statistiques Descriptives

Avant d'appliquer les modèles de régression, des statistiques descriptives ont été générées pour comprendre la distribution des variables. Les mesures de tendance centrale et de dispersion (moyenne, écart-type, minimum, maximum) ont été calculées pour chaque variable afin d'obtenir un aperçu des données.

## Conclusion

Les deux exercices ont permis de mieux comprendre les performances et les comportements des modèles **Ridge**, **Lasso** et **Elastic Net** :
- **Exercice 1** : Le modèle **Elastic Net** a montré des performances solides, mais la légère différence entre les jeux de test et d'entraînement suggère qu'il pourrait être un peu surajusté.
- **Exercice 2** : Après optimisation des hyperparamètres, **Ridge** a montré les meilleures performances globales. Cependant, **Lasso** et **Elastic Net** offrent une bonne alternative pour la sélection de variables et la régularisation.

### Recommandations :
- Si l'objectif est d'optimiser la performance globale sans simplifier le modèle, **Ridge** est le meilleur choix.
- Si la sélection de variables est une priorité, **Lasso** est préférable.
- **Elastic Net** est utile lorsque les données présentent des relations complexes entre les variables et que l'on souhaite un compromis entre régularisation et sélection de variables.


