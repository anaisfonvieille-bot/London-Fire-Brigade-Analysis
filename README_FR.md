# 🚒 London Fire Brigade — Analyse de données

[🇬🇧 English](README.md) | 🇫🇷 **Français**

### 📌 Présentation du projet

Ce projet analyse les **données opérationnelles de la London Fire Brigade de 2021 à 2025** afin de comprendre les relations entre les incidents, la mobilisation des ressources, les temps d'intervention et les coûts opérationnels.

L'objectif était d'identifier les principaux facteurs influençant l'activité opérationnelle et les dépenses, tout en évaluant si la London Fire Brigade maintenait un niveau de service performant.

L'analyse repose sur des jeux de données officiels publiés par la **City of London**, combinant :

- London Fire Brigade Incident Records
- London Fire Brigade Mobilisation Records

---

### 🎯 Objectifs

Le projet s'articule autour de trois axes principaux :

- Incidents
- Temps d'intervention
- Coûts opérationnels

L'analyse vise à :

- Identifier les tendances des incidents et des mobilisations
- Évaluer les temps d'intervention
- Comprendre l'évolution et les facteurs influençant les coûts d'intervention
- Identifier les disparités géographiques
- Mettre en évidence des opportunités potentielles d'optimisation des ressources

---

### 🛠️ Outils & Technologies

- Python
- pandas
- Google Colab
- Power BI
- Power Query
- Data Visualization

---

### 🔄 Traitement des données

Les données initiales provenaient de **quatre fichiers : 2 fichiers Excel et 2 fichiers CSV**, contenant les données relatives aux incidents et aux mobilisations.

Le workflow utilisé :

`Importation → Exploration → Nettoyage → Gestion des valeurs manquantes → Transformation des dates → Jointure des datasets → Analyse exploratoire → Power BI → Dashboard & Storytelling`

Les datasets relatifs aux incidents et aux mobilisations ont été reliés grâce à l'identifiant commun **IncidentNumber**.

---

### 📊 Résultats clés

L'analyse finale couvre environ :

- **598K incidents**
- **930K mobilisations**
- **301,67 M£ de coûts opérationnels totaux estimés**
- **504,53 £ de coût moyen par intervention**

Entre 2021 et 2025 :

| KPI | 2021 | 2025 | Évolution |
|---|---:|---:|---:|
| Incidents | 102K | 131K | +28% |
| Mobilisations | 158K | 206K | +30% |
| Coût moyen | 443,19 £ | 588,90 £ | +33% |
| Coût total | 45,24 M£ | 76,91 M£ | +70% |

Les coûts opérationnels ont donc augmenté beaucoup plus rapidement que le volume d'activité, avec une accélération particulièrement importante à partir de 2024.

---

### 🔎 Principaux enseignements

#### Fausses alarmes

Les fausses alarmes représentent le principal levier potentiel d'optimisation.

Elles représentent environ :

- **50% des incidents**
- **41% des coûts totaux**
- Environ **124 M£**

Malgré leur caractère non critique, elles génèrent une charge opérationnelle importante.

#### Activité résidentielle

Les habitations occupent une place centrale dans l'activité opérationnelle.

Elles représentent :

- **63% des mobilisations**
- **56,6% des coûts totaux**

Une part importante de cette activité est liée aux fausses alarmes résidentielles.

#### Disparités géographiques

L'analyse met en évidence une différence claire entre le centre et la périphérie de Londres.

Le centre de Londres concentre les volumes d'intervention les plus importants, tandis que certaines zones périphériques telles que :

- Wennington
- Erith
- Hayes

présentent des temps d'intervention plus longs et des coûts unitaires plus élevés.

#### Performance opérationnelle

Malgré l'augmentation de la pression financière, les performances opérationnelles restent élevées :

- **Temps médian d'intervention : 5,63 minutes**
- **Mobilisations retardées : 0,04%**
- **96,24% des mobilisations effectuées depuis la caserne de rattachement**

---

### 👩‍💻 Ma contribution

Ce projet a été réalisé en équipe.

Ma contribution a couvert plusieurs étapes du pipeline de données :

- Importation des données
- Exploration des données
- Nettoyage des données
- Transformation des données
- Visualisation exploratoire
- Préparation des données pour Power BI

Dans l'analyse Power BI, ma principale responsabilité concernait **l'analyse des coûts opérationnels**.

L'objectif était de :

- Comprendre la structure des coûts
- Identifier les principaux facteurs de coûts
- Analyser l'évolution des coûts
- Mettre en évidence des opportunités potentielles d'optimisation

---
