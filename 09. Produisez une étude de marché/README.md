# Produisez une étude de marché pour un lancement à l'international
**Projet 09 – Formation Data Analyst OpenClassrooms**

---

## 1. 🛠️ Technologies utilisées

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-red)
![NumPy](https://img.shields.io/badge/NumPy-1.21%2B-purple)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24%2B-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.4%2B-yellow)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11%2B-brightgreen)
![NumPy](https://img.shields.io/badge/NumPy-1.21%2B-purple)

---

## 2. 📌 Contexte et Objectifs

Ce projet vise à **identifier des groupements de pays** pour le lancement international de "La poule qui chante", en utilisant des données de la FAO et des critères PESTEL. Les objectifs :
- **Analyser les données** : Population, disponibilité alimentaire, PIB, stabilité politique, etc.
- **Classifier les pays** : Avec des méthodes de clustering (CAH, K-Means) et une ACP.
- **Recommander des cibles** : Pays prometteurs pour l'export de volailles.

---

## 3. 🗂️ Structure du projet
```
04. Produisez une étude de marché/
├── 01. Enoncé/              # 📜 Énoncé du projet et consignes OpenClassrooms
├── 10. Données/             # 📊 Données brutes et de référence
├── 20. Notebooks/           # 📓 Notebooks Jupyter pour l'analyse
├── 30. Scripts/             # 🐍 Scripts Python utilitaires
└── 40. Resultats/           # 📈 Graphiques et résultats exportés
```
---

## 4. 🛠️ Compétences mises en œuvre

- **Préparation des données** : Nettoyage, fusion, et analyse exploratoire (Pandas, NumPy).
- **Clustering** :
  - **CAH** : Dendrogramme pour visualiser les groupes.
  - **K-Means** : Méthode des coudes pour déterminer le nombre de clusters.
  - **ACP** : Réduction de dimension et interprétation des axes (F1-F4).
- **Visualisation** : Heatmaps, cercles de corrélation, projections des individus (Matplotlib, Seaborn).
- **Analyse PESTEL** : Intégration de critères politiques, économiques, et géographiques.

---

## 5. 🔍 Méthodologie

1. **Nettoyage** :
   - Gestion des valeurs manquantes, normalisation des données.
2. **Clustering** :
   - Comparaison des normalisations (Standard, Robuste, MinMax).
   - Choix de la normalisation MinMax pour son équilibre.
3. **ACP** :
   - Sélection des composantes principales (éboulis des valeurs propres).
   - Interprétation des axes (ex. : F1 = stabilité politique vs PIB/habitant).
4. **Recommandations** :
   - Croisement des résultats avec les critères business (proximité, importations).

---

## 6. 📊 Résultats Clés

### 1. Corrélation des variables
- **Variables clés** : Croissance de la population, PIB, stabilité politique, taux d'importation de volailles.
- **Insights** : La stabilité politique est anticorrélée au PIB/habitant, la distance de la France influence les choix logistiques.

### 2. Clustering
- **Méthodes** : CAH (dendrogramme) et K-Means, testées avec 3 types de normalisation (Standard, Robuste, MinMax).
- **Résultats** :
  - **Normalisation MinMax** : 3 groupes distincts.
  - **Groupe 3** : Pays avec forte stabilité politique, proximité géographique, et consommation élevée de volailles.

### 3. Recommandations
- **Top 5** : Pays-Bas, Luxembourg, Autriche, Irlande, Danemark.
- **Critères** : Importations de poulet, PIB élevé, stabilité politique, proximité.

---

## 7. 🖼️ Visualisations Clés

### 1. Corrélation des variables
![Heatmap](40.%20R%C3%A9sultats/Heatmap_de_Corrélation.png)
*Exemple : La stabilité politique est anticorrélée au PIB/habitant (-21%).*

### 2. Dendrogramme (CAH - Normalisation MinMax)
![Dendrogramme](40.%20R%C3%A9sultats/Dendrogramme.png)
*3 clusters identifiés : les pays sont regroupés par similitude économique et géographique.*

### 3. Cercle des corrélations (ACP - F3 et F4)
![Cercle ACP](40.%20R%C3%A9sultats/Cercle_de_Corrélation.png)
*F3 : Variation de stock et stabilité politique. F4 : Classement affaire et croissance économique.*

### 4. Projection des individus
![Projection ACP](40.%20R%C3%A9sultats/Projection_des_Individus_ACP.png)
*Le **groupe bleu** (à droite) regroupe les pays avec une forte stabilité politique et une consommation élevée de volailles, proches de la France.*

### 5. Top 5 des pays recommandés
![Top 5](lien_vers_top5.png)
   Rang | Pays        | Critères clés                                                 |
 |------|-------------|---------------------------------------------------------------|
 | 1    | Pays-Bas    | Importations élevées, stabilité politique                     |
 | 2    | Luxembourg  | Proximité, PIB/habitant élevé                                 |
 | 3    | Suisse      | Stabilité, pouvoir d’achat, consommation de volailles         |
 | 4    | Irlande     | Croissance économique, facilité des affaires                  |
 | 5    | Danemark    | PIB élevé, faible distance                                    |

---

## 8. 💡 Particularités

- **Approche PESTEL** : Intégration de données macro-économiques et géopolitiques.
- **Double validation** : CAH pour le nombre de clusters, K-Means pour la composition des groupes.

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

