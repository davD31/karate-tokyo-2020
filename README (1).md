# Analyse du Karaté aux Jeux Olympiques de Tokyo 2020

Analyse des performances en karaté lors des JO de Tokyo 2020.

##  Contexte

Le karaté a fait sa première et unique apparition olympique aux JO de Tokyo 2020, avec 8 épreuves réparties entre deux disciplines : le **Kata** (technique) et le **Kumite** (combat). Ce projet analyse les 32 médailles distribuées à 81 athlètes issus de 20 pays différents.

##  Stack technique

| Outil | Utilisation |
|-------|------------|
| **Python 3** | Nettoyage, transformation et analyse des données |
| **Pandas / NumPy** | Manipulation de DataFrames, agrégations, jointures |
| **Matplotlib** | Visualisations statistiques (bar charts, histogrammes, pie charts) |
| **Power BI** | Dashboard interactif avec filtres et KPIs |

##  Démarche d'analyse

### 1. Chargement & Filtrage
- Import des datasets Kaggle (11 656 athlètes, 2 401 médailles toutes disciplines)
- Filtrage sur la discipline Karaté (81 athlètes, 32 médailles)

### 2. Nettoyage des données
- Vérification des valeurs nulles et doublons
- Standardisation des noms de pays (ex : "People's Republic of China" → "China")
- Simplification des types de médailles ("Gold Medal" → "Gold")
- Création d'une colonne subdiscipline (Kata / Kumite)

### 3. Analyses réalisées
- **Classement par pays** : nombre total de médailles et système de points pondéré (Or = 3, Argent = 2, Bronze = 1)
- **Parité hommes/femmes** : répartition parfaitement égalitaire (16/16)
- **Kata vs Kumite** : comparaison du nombre de médailles et de l'âge moyen des médaillés
- **Analyse démographique** : distribution des âges, athlète le plus jeune (20 ans) et le plus âgé (39 ans)

### 4. Visualisation Power BI
Dashboard interactif en 2 pages :
- **Page 1** : Vue d'ensemble par pays (classement, KPIs, système de points)
- **Page 2** : Comparaison Kata vs Kumite (médailles par discipline, âge moyen)

## 📊 Résultats clés

- **20 pays** ont remporté au moins une médaille — aucune domination d'un seul pays
- La **Turquie** a le plus de médailles (4) mais aucune en or — le **Japon** domine au classement par points (6 pts)
- Les médaillés en **Kata** ont en moyenne **30,6 ans** contre **26,6 ans** en Kumite, confirmant que le Kata valorise l'expérience technique
- La plus âgée médaillée d'or : **Sandra Sanchez Jaime** (Espagne, 39 ans, Kata)
- La plus jeune médaillée : **Sofya Berultseva** (Kazakhstan, 20 ans, Kumite)

## 📸 Aperçu du Dashboard

> *Ajouter ici les captures d'écran de votre dashboard Power BI*

<!--
![Dashboard Page 1](images/dashboard_page1.png)
![Dashboard Page 2](images/dashboard_page2.png)
-->

## 🗃️ Source des données

[Kaggle — Tokyo 2020 Olympic Summer Games](https://www.kaggle.com/datasets/piterfm/tokyo-2020-olympics)

## 👤 Auteur

**[Ton Prénom Nom]** — Étudiant en L2 MIASHS  
[LinkedIn](https://linkedin.com/in/ton-profil) · [Email](mailto:ton@email.com)

---

*Projet réalisé dans le cadre d'une analyse exploratoire de données — 2025*
