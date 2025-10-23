# Détectez des faux billets avec un algorithme de classification
**Projet 10 – Formation Data Analyst OpenClassrooms**

---
## 1.🛠️ Technologies utilisées

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-red)
![NumPy](https://img.shields.io/badge/NumPy-1.21%2B-purple)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24%2B-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4%2B-yellow)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11%2B-brightgreen

---

## 2. 📌 Contexte et Objectifs

Ce projet vise à **détecter automatiquement les faux billets** à partir de leurs dimensions géométriques, pour l'**Organisation nationale de lutte contre le faux-monnayage (ONCFM)**.
- **Analyser les données** : 6 caractéristiques géométriques (longueur, hauteurs, marges, diagonale).
- **Comparer deux modèles** :
  - **Régression logistique** (classique).
  - **K-means** (utilisation des centroïdes pour la prédiction).
- **Évaluer les performances** : Matrice de confusion, faux positifs/négatifs.

---

## 3. 📂 Structure du Projet
```
10. Detection Faux Billets/
├── 01. Enoncé/              # 📜 Énoncé du projet et consignes OpenClassrooms
├── 10. Données/             # 📊 Données brutes et de référence
├── 20. Notebooks/           # 📓 Notebooks Jupyter pour l'analyse
├── 30. Scripts/             # 🐍 Scripts Python utilitaires
└── 40. Resultats/           # 📈 Graphiques et résultats exportés
```

---

## 4. 🛠️ Compétences mises en œuvre

- **Analyse descriptive** : Répartition des dimensions, visualisation des données (Pandas, Matplotlib).
- **Modélisation** :
  - **Régression logistique** : Prédiction binaire (vrai/faux).
  - **K-means** : Clustering des billets par similarité géométrique.
- **Évaluation** : Matrice de confusion, calcul des métriques (précision, rappel).
- **Prétraitement** : Gestion des valeurs manquantes (régression linéaire si nécessaire).

---

## 5. 🔍 Méthodologie

1. **Exploration** :
   - Statistiques descriptives, visualisation des distributions.
2. **Prétraitement** :
   - Vérification des valeurs manquantes (inspiré du post-it : régression linéaire si besoin).
3. **Modélisation** :
   - **Régression logistique** : Modèle supervisé avec validation croisée.
   - **K-means** : Clustering non supervisé, utilisation des centroïdes pour prédire.
4. **Évaluation** :
   - Comparaison des performances via matrice de confusion.

---

## 6. 📊 Résultats Clés

- **Jeu de données** : 1500 billets (1000 vrais, 500 faux).
- **Modèles testés** :
  - **Régression logistique** : Précision élevée, faible taux de faux négatifs.
  - **K-means** : Efficace pour identifier des clusters de contrefaçons.
- **Recommandation** : La régression logistique est retenue pour sa robustesse et son interprétabilité.

---

## 7. 🖼️ Visualisations Clés

### 1. Comparaison des modèles
![Matrice](40.%20R%C3%A9sultats/Matrice de confusion K-Mean Vs Régression Logistique.png)
*La régression logistique surpasse le K-means avec 197 vrais positifs.*

### 2. Méthode des coudes
![Coude](40.%20R%C3%A9sultats/Méthode des coudes.png)
*3 clusters optimaux identifiés pour le K-means.*

### 3. Boxplots des dimensions
![Boxplots](40.%20R%C3%A9sultats/Boxplots des Dimension par classe.png)
*Les faux billets se distinguent par leurs marges et longueurs.*

---

## 8. 💡 Particularités
```
- **Approche comparative** : Deux méthodes mises en concurrence pour identifier la plus performante.
- **Application finale** : Algorithme fonctionnel pour analyser de nouveaux fichiers (`billets_production.csv`).

---

## 9.👤 Auteur
[Jérôme](https://github.com/Goumbo) — Data Analyst

## 📬 Contact
📧 [jerome.github@loriquet.fr](mailto:jerome.github@loriquet.fr)

## 🔗 Mes Dépôts GitHub
   **Dépôt**               | **Description**                            | **Lien**                                                                 |
 |-------------------------|--------------------------------------------|--------------------------------------------------------------------------|
 | 📊 **OpenClassrooms**   | Projets Data Analyst (Python, R, SQL)      | [Voir les projets](https://github.com/Goumbo/OpenClassrooms)             |
 | 📑 **Excel/VBA**        | Outils d'automatisation & tableaux de bord | [Voir les outils](https://github.com/Goumbo/Excel)                       |
