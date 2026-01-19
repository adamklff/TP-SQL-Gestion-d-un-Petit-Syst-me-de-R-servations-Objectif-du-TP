# TP SQL : Système de Gestion de Réservations

## Objectifs du travail
Ce TP consiste à modéliser et interroger une base de données relationnelle pour un restaurant. Les compétences mises en œuvre sont :
- Création de base de données et de tables (DDL).
- Insertion de données (DML).
- Requêtes de sélection simples et conditionnelles.
- Utilisation de **JOINTURES** (INNER JOIN) pour lier les tables.
- Agrégation et tri des données (GROUP BY, ORDER BY).

## Technologies utilisées
- **Langage** : SQL (Standard / MySQL).
- **SGBD** : MySQL ou MariaDB.

## Contenu du dépôt
1. **Script SQL (`src/restaurant.sql`)** : Contient toutes les commandes de création, d'insertion et les requêtes demandées.
2. **Rapport (`rapport/`)** : Document PDF détaillant la solution et les résultats attendus.

## Instructions d'installation
1. Importer le fichier `restaurant.sql` dans votre SGBD :
   ```bash
   mysql -u root -p < src/restaurant.sql
