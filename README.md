# Social Media & Mental Health Analysis

## Description

Ce projet analyse le dataset **Mental Health and Social Media Balance** provenant de la plateforme Kaggle.

Les données regroupent des informations sur le temps quotidien passé sur les réseaux sociaux, les plateformes utilisées, ainsi que plusieurs indicateurs liés à la santé mentale (stress, anxiété, estime de soi, qualité du sommeil, etc.).

L’objectif est d’examiner l’existence d’un **seuil critique d’utilisation des réseaux sociaux au-delà duquel la santé mentale se dégrade significativement**.

Le dataset contient des variables quantitatives (temps d’utilisation, scores psychologiques) et qualitatives (genre, plateformes utilisées).

## Objectifs

- Explorer et visualiser le temps d’utilisation des réseaux sociaux
- Analyser la relation entre durée d’usage et indicateurs de santé mentale
- Identifier un éventuel seuil critique d’heures d’utilisation
- Comparer les résultats selon le genre et les plateformes
- Appliquer des analyses statistiques (corrélation, comparaison de moyennes, régression simple)
- Interpréter les résultats dans une perspective sociétale

## Installation et Configuration

### Prérequis
- Python 3.10.0
- Jupyter Notebook
- Gestionnaire de paquets : `pip`

### Installation des dépendances
```bash
pip install -r requirements.txt
```

## Méthodologie

1. **Collecte des données** : Importation du dataset depuis Kaggle.
2. **Nettoyage des données** : Traitement des valeurs manquantes et encodage des variables catégorielles.
3. **Analyse exploratoire (EDA)** : Création de groupes d’heures d’utilisation (0–2h, 2–4h, 4–6h, 6h+).
4. **Modélisation** : Statistiques descriptives, visualisations (barplots, boxplots, heatmap).
5. **Analyse statistique** : Corrélations, comparaison de moyennes, régression linéaire simple.
6. **Interprétation** : Identification d’un seuil critique et discussion des limites.

### Documents de référence
- **[Documentation des données](socialmedia_analysis/doc/data_documentation.md)** : Sources et descriptions détaillées des datasets utilisés

*Projet réalisé dans le cadre d'un cours de Data Visualisation*