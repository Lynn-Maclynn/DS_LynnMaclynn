# 🎯 Prédiction de la coupe d’un diamant

Ce projet utilise la base de données `diamonds` de Seaborn pour prédire la **qualité de la coupe** (`cut`) d’un diamant en fonction de ses caractéristiques physiques et économiques.

## 🔍 Objectif

- Prévoir la catégorie de coupe (`Fair`, `Good`, `Very Good`, `Premium`, `Ideal`)
- Analyser les relations entre les variables et la variable cible
- Évaluer les performances d’un modèle de classification

## 📁 Fichiers

- `Predict_cut_diamonds.ipynb` : Notebook avec nettoyage des données, visualisations, préparation du modèle et prédiction
- Aucune donnée externe : jeu intégré via Seaborn

## 🧰 Technologies

- Python (Pandas, Seaborn, Scikit-learn)
- Classification (Random Forest, AdaBoost, SVM, KNN)
- Jupyter Notebook

## ✅ Résultats

Le modèle permet de prédire la coupe avec un score satisfaisant ('f1' 50% et 'accuracy' 75%). Des pistes d’amélioration sont possibles en optimisant le preprocessing et l’équilibrage des classes.
