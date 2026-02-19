# Social Media & Mental Health Analysis

## Description

Ce projet analyse le dataset **Mental Health and Social Media Balance** (Kaggle).

Les données contiennent des informations sur le **temps d’écran quotidien**, les **plateformes utilisées**, ainsi que plusieurs indicateurs liés au bien-être :
- **Stress** (1–10)
- **Qualité du sommeil** (1–10)
- **Indice de bonheur** (1–10)

Le dataset inclut aussi des variables contextuelles (âge, genre, fréquence d’exercice, jours sans réseaux sociaux).

L’objectif est d’examiner l’existence d’un **seuil critique d’utilisation des réseaux sociaux** au-delà duquel les indicateurs de bien-être se dégradent significativement.

## Objectifs

- Explorer et visualiser la distribution du temps d’écran quotidien
- Analyser la relation entre temps d’écran et :
  - Stress
  - Qualité du sommeil
  - Indice de bonheur
- Identifier un éventuel seuil critique (groupes : 0–2h, 2–4h, 4–6h, 6h+)
- Comparer les résultats selon le **genre** et la **plateforme principale**
- Tester statistiquement les différences entre groupes (ANOVA / tests de comparaison)
- Proposer une interprétation dans une perspective sociétale (sans confondre corrélation et causalité)


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