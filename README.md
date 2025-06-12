# Projet d'Analyse Exploratoire

## Introduction

Ce projet a été réalisé dans le cadre d'une mission d'analyse exploratoire pour la start-up *academy*, qui propose des contenus de formation en ligne. L'objectif est d'explorer les données éducatives de la Banque Mondiale pour identifier les pays présentant un fort potentiel pour les services proposés par l'entreprise.

## Objectif

L'objectif principal est d'identifier les pays présentant un fort potentiel pour les services proposés par *academy* et d'anticiper l'évolution de ce potentiel dans le temps.

## Étapes de l'analyse

1. **Chargement des données** : Importation des bibliothèques nécessaires et chargement des fichiers CSV.
2. **Visualisation des données** : Affichage des premières lignes et dimensions des jeux de données pour une première compréhension.
3. **Nettoyage des données** : Première étape de nettoyage pour préparer les données à l'analyse.

## Jeux de données utilisés

- `EdStatsCountry.csv` : 241 lignes, 32 colonnes
- `EdStatsSeries.csv` : 3665 lignes, 21 colonnes
- `EdStatsCountry-Series.csv` : 613 lignes, 4 colonnes
- `EdStatsFootNote.csv` : 643638 lignes, 5 colonnes
- `EdStatsData.csv` : 886930 lignes, 70 colonnes

## Instructions pour l'exécution

Pour reproduire l'analyse, exécutez le notebook `main.ipynb` en suivant les étapes décrites. Assurez-vous d'avoir les fichiers CSV dans le répertoire `Projet+Python_Dataset_Edstats_csv/` et d'avoir installé les bibliothèques nécessaires (pandas, numpy, matplotlib, seaborn). 