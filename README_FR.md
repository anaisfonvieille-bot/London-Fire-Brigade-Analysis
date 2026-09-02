# 🚒 London Fire Brigade — Analyse de données

[🇬🇧 English version](README_EN.md) | 🇫🇷 **Version française**

[← Retour à l'accueil](README.md)

---

<p align="center">
  <img src="https://img.shields.io/badge/Python-Data%20Analysis-blue?logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/pandas-Data%20Preparation-150458?logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black">
  <img src="https://img.shields.io/badge/Power%20Query-Transformation-217346">
  <img src="https://img.shields.io/badge/Projet-Data%20Analytics-red">
</p>

---

## 📌 Présentation du projet

Ce projet analyse les données opérationnelles de la **London Fire Brigade entre 2021 et 2025** afin d'étudier les relations entre :

- les incidents ;
- la mobilisation des ressources ;
- les délais d'intervention ;
- les coûts opérationnels.

L'objectif était d'identifier les principaux facteurs influençant l'activité et les dépenses, tout en évaluant le maintien de la performance opérationnelle.

Les données proviennent des jeux de données publics officiels de la ville de Londres :

- **London Fire Brigade Incident Records**
- **London Fire Brigade Mobilisation Records**

---

## 🎯 Objectifs

L'analyse repose sur trois axes principaux :

### 🔥 Incidents
Analyser l'évolution des incidents et identifier les catégories les plus fréquentes.

### ⏱️ Durées d'intervention
Évaluer les temps d'intervention et mettre en évidence les éventuelles disparités géographiques ou opérationnelles.

### 💷 Coûts
Analyser l'évolution des coûts, comprendre les principaux facteurs explicatifs et identifier des pistes d'optimisation.

---

## 🛠️ Outils utilisés

| Outil | Utilisation |
|---|---|
| **Python** | Pré-traitement, exploration et analyse |
| **pandas** | Manipulation et transformation des données |
| **Google Colab** | Environnement collaboratif |
| **Power BI** | Création du dashboard |
| **Power Query** | Nettoyage et transformation |
| **Data Visualisation** | Analyse et storytelling |

---

## 🔄 Pipeline de traitement

Les données initiales étaient réparties dans **4 fichiers** :

- 2 fichiers Excel ;
- 2 fichiers CSV.

Le workflow du projet :

```text
Importation
    ↓
Exploration
    ↓
Nettoyage
    ↓
Gestion des valeurs manquantes
    ↓
Transformation des dates
    ↓
Jointure des datasets
    ↓
Analyse exploratoire
    ↓
Power BI
    ↓
Dashboard & Storytelling
