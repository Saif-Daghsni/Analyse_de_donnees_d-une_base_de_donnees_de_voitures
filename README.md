# 🚗 Analyse des Voitures - Clustering et ACP/ACM

Ce projet consiste en une **analyse exploratoire et en classification non supervisée** d’un dataset de voitures, en utilisant différentes méthodes statistiques et de clustering.

---

## 📂 Contenu du projet

- **notebooks/analyse_voitures.ipynb** : Notebook principal avec toutes les analyses et visualisations.
- **data/cars_data.xlsx** : Dataset contenant les caractéristiques des voitures.
- **requirements.txt** : Librairies Python nécessaires pour exécuter le projet.

---

## 🛠 Méthodes utilisées

### 1. Analyse en Composantes Principales (ACP/ACM)
- Réduction de dimensionnalité pour visualiser les relations entre variables.
- Transformation des variables qualitatives en variables binaires (one-hot encoding).
- Visualisation des individus et variables dans le **plan factoriel**.

### 2. Clustering
- **K-Means** : Classification stricte des voitures en clusters homogènes.
- **CAH (Classification Ascendante Hiérarchique)** : Regroupement des voitures selon la méthode de Ward.
- **FCM simulé avec GMM (Gaussian Mixture Model)** : Permet un **clustering flou**, avec des degrés d’appartenance probabilistes.

---

## 📊 Visualisations

- Histogrammes et distributions des variables.
- Cercle des corrélations pour interpréter les axes factoriels.
- Projection des individus et clusters dans le plan ACP.
- Dendrogramme pour la CAH.
- Courbe du coude pour déterminer le nombre optimal de clusters.


