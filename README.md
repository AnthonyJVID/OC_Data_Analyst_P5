# 🍷 OC - Projet 5 : Optimisez la gestion des données d’une boutique de vin avec Python

Ce projet simule une mission freelance chez **BottleNeck**, un marchand de vin haut de gamme. L’objectif est de rapprocher deux bases de données (ERP et boutique en ligne) pour améliorer la gestion des stocks et l’analyse des ventes.

---

## 🎯 Objectif de la mission

> Fournir une vue consolidée des ventes, des stocks, et des anomalies de prix entre deux systèmes d’information non connectés.

Les livrables attendus sont :

1. **Rapprochement des données** entre l’ERP et la boutique en ligne via une table de correspondance (`product_id` ↔ `SKU`).
2. **Calcul du chiffre d’affaires** par produit, ainsi que du **chiffre d’affaires total réalisé en ligne**.
3. **Détection et visualisation des prix anormaux** pour identifier des erreurs potentielles de saisie.

---

## 📁 Arborescence du projet

```
├── P5_notebook.ipynb         → Notebook principal contenant l’analyse
├── data/
│   ├── erp.xlsx              → Données produits issues de l’ERP
│   ├── web.xlsx              → Données issues du site de vente en ligne
│   └── liaison.xlsx          → Table de correspondance entre les deux systèmes
├── README.md                 → Présentation du projet
└── requirements.txt          → Dépendances Python
```

---

## 🛠️ Technologies et librairies utilisées

- `pandas` pour la manipulation de données tabulaires
- `numpy` pour le traitement numérique
- `matplotlib`, `seaborn` pour les graphiques
- `jupyter notebook` pour l’analyse interactive

---

## 📊 Résultats obtenus

- Création d’un **DataFrame consolidé** regroupant ventes, prix et références produits
- Calcul automatique du **chiffre d’affaires par produit** et du **CA total**
- Identification des **valeurs aberrantes** dans les prix via les quartiles (méthode IQR)
- Visualisation des anomalies pour faciliter la communication lors du COPIL

---

## 📈 Exemple de visualisations

- Histogrammes des prix
- Boîtes à moustaches (boxplots) pour détecter les outliers
- Tableaux triés des produits les plus chers ou anormaux

---

## 🧠 Auteur

Projet réalisé par **AnthonyJVID** dans le cadre du parcours *Data Analyst* chez OpenClassrooms.

---

## 📄 Licence

Ce projet est disponible à des fins pédagogiques et de démonstration.
