# Optimisez la gestion des données d'une boutique avec R et Python
**Projet 05 – Formation Data Analyst OpenClassrooms**

---

## 1. 🛠️ Technologies utilisées

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![R](https://img.shields.io/badge/R-4.0%2B-darkblue)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-red)
![NumPy](https://img.shields.io/badge/NumPy-1.21%2B-purple)
![dplyr](https://img.shields.io/badge/dplyr-1.0%2B-lightblue)
![ggplot2](https://img.shields.io/badge/ggplot2-3.3%2B-pink)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Excel](https://img.shields.io/badge/Excel-VBA-green)

---

## 2. 📌 Contexte et Objectifs

Ce projet consiste à **rapprocher deux bases de données** (ERP et CMS) pour BottleNeck, un marchand de vin, afin d’améliorer la gestion des stocks et l’analyse des ventes en ligne. Les missions clés :
- **Rapprochement des données** : Lier les références produits entre l’ERP et la boutique en ligne via une table de liaison.
- **Calcul du chiffre d’affaires** : Par produit et total, à partir des ventes en ligne.
- **Détection d’anomalies** : Analyse des prix pour identifier des valeurs aberrantes.

---

## 3. 🗂️ Structure du projet
```
05. Optimisez la gestion d'une Boutique/
├── 01. Enoncé/              # 📜 Énoncé du projet et consignes OpenClassrooms
├── 10. Données/             # 📊 Données brutes et de référence
├── 20. Notebooks/           # 📓 Notebooks Jupyter pour l'analyse
├── 30. Scripts/             # 🐍 Scripts Python utilitaires
└── 40. Resultats/           # 📈 Graphiques et résultats exportés
```

---

## 4. 🛠️ Compétences mises en œuvre

### **Avec Python**
- **Manipulation de données** : Nettoyage et fusion avec **Pandas** (jointures, gestion des valeurs manquantes).
- **Analyse univariée** : Détection d’anomalies sur les prix avec **NumPy** et visualisation avec **Matplotlib/Seaborn**. 
- **Automatisation** : Scripts reproductibles pour le calcul du chiffre d’affaires.

### **Avec R**
- **Manipulation de données** : Utilisation de **dplyr** et **tidyr** pour le nettoyage et les jointures.
- **Visualisation** : Graphiques avec **ggplot2** pour identifier les anomalies.
- **Analyse statistique** : Calculs de statistiques descriptives.

---

## 5. 🔍 Méthodologie

1. **Nettoyage des données** :
   - Correction des noms de colonnes (ex. : `id_web` → `SKU`).
   - Jointure des tables via la table de liaison.
2. **Analyse des ventes** :
   - Calcul du chiffre d’affaires par produit et global.
3. **Détection d’anomalies** :
   - Identification des prix aberrants (boxplots, seuils statistiques).
   - Visualisation des résultats.

---

## 6. 📊 Résultats Clés

### Analyse Python
- Nettoyage et fusion des données ERP/web/stocks.
- Visualisation des **produits les plus vendus**, **stocks critiques**, et **corrélations** entre trafic et ventes.
- Utilisation de **Pandas** pour le traitement et **Seaborn/Matplotlib** pour les graphiques.

### Analyse R
- Approche similaire avec **dplyr** pour le nettoyage et **ggplot2** pour les visualisations.
- Focus sur les **tendances saisonnières** et segments clients.

---

## 7. 🖼️ Visualisations Clés

### Analyse Python
- **Chiffre d'affaires par prix** :
  ![Chiffre d'Affaire par Prix](40.%20R%C3%A9sultats/Chiffre_d_Affaire_par_Prix_du_Produit.png)
- **Prix et anomalies** :
  ![Prix et Anomalies](40.%20R%C3%A9sultats/Visualisation_des_Prix_et_des_Prix_en_Anomalie.png)
- **Boîte à moustaches** :
  ![Boîte à Moustaches](40.%20R%C3%A9sultats/Visualisation_des_Prix_et_des_Prix_en_Anomalie_Boite_a_Moustache.png)

### Analyse R
- **Détection des Prix en Anomalie** :
  ![Détection des Prix en Anomalie](40.%20R%C3%A9sultats/Détection_des_Anomalies_dans_les_Prix_R.png)
- **Distribution des Prix** :
  ![Distribution des Prix](40.%20R%C3%A9sultats/Distribution_des_Prix_R_Horizontal.png)
- **Distribution des Prix V2** :
  ![Distribution des Prix V2](40.%20R%C3%A9sultats/Distribution_des_Prix_R_Vertical.png)
  
---

## 8. 💡 Particularités

- **Double implémentation** : Le projet a été réalisé en **Python** et en **R**, montrant une maîtrise des deux langages.

**Pourquoi deux langages ?**
- **Python** : Idéal pour l'intégration dans des pipelines data et le traitement de gros volumes.
- **R** : Excellente visualisation et analyse statistique.
- **Comparaison** : Les deux approches permettent de valider les résultats et d'identifier les forces de chaque outil.

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


