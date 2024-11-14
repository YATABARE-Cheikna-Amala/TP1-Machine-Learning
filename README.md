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

