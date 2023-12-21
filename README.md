# Projet d'Entrepôt de Données et Datamarts avec Talend

![Alt text](https://maghreb.simplonline.co/_next/image?url=https%3A%2F%2Fsimplonline-v3-prod.s3.eu-west-3.amazonaws.com%2Fmedia%2Fimage%2Fpng%2Fdependent-data-marts-1024x574-64ea1175c0e87247689077.png&w=1280&q=75)

## Contexte du Projet

Une société a une plateforme d'e-commerce prospère, souhaite mettre en place une solution d'entrepôt de données pour optimiser ses opérations et comprendre le comportement de ses clients. En tant que développeur Data, votre mission est de mettre en œuvre un ETL optimisé avec Talend, créer un entrepôt de données avec des datamarts, et accomplir les tâches suivantes.

## Tâches Principales

1. **Préparation des Données:**
   - Appliquer le script Data Splitter sur le dataset pour le diviser en formats JSON, base de données et CSV.

2. **Conformité RGPD:**
   - Élaborer un plan de conformité avec le RGPD pour assurer le traitement adéquat des données.

3. **Orientation Technique:**
   - Choisir les outils et technologies conformes au RGPD pour la collecte, le stockage, le traitement, et la mise à disposition des données.

4. **Implémentation d'un Job ETL Optimisé:**
   - Créer un job ETL optimisé avec Talend, incluant une gestion robuste des erreurs.

5. **Construction de la Zone de Staging:**
   - Mettre en place la zone de staging pour faciliter le traitement efficace des données.

6. **Modélisation de l'Entrepôt de Données:**
   - Concevoir le schéma de l'entrepôt de données en définissant les tables, les relations et les clés.

7. **Création de 2 Data Marts:**
   - Data Mart 1: Axé sur la démographie des utilisateurs, les tendances d'inscription, l'analyse de rétention et le taux de désabonnement.
   - Data Mart 2: Se concentre sur les ventes mensuelles/trimestrielles/annuelles, les produits et catégories les plus vendus, et les tendances des ventes dans le temps.

8. **Gestion d'Accès Basé sur les Rôles:**
   - Mettre en place une gestion d'accès basée sur les rôles pour assurer la sécurité des datamarts.

9. **Visualisation des Données des Datamarts:**
   - Intégrer des outils de visualisation (par exemple, Power BI, Tableau) pour présenter les données résultant des datamarts.

## Structure du Projet

Le projet est organisé en plusieurs répertoires :

- **scripts :**
  - Contient le script Data Splitter et tout autre script nécessaire pour la préparation des données.

- **etl_jobs :**
  - Comprend les jobs Talend pour l'ETL et la gestion des erreurs.

- **data_modeling :**
  - Contient la modélisation de l'entrepôt de données.

- **data_marts :**
  - Inclut les définitions et les scripts de création des deux datamarts.

- **access_management :**
  - Contient les configurations pour la gestion des accès basée sur les rôles.

- **visualization :**
  - Comprend des rapports ou des configurations pour la visualisation des données.

## Comment Démarrer

1. Clonez le dépôt :
   ```bash
   git clone <repository-url>
   cd entrepot-donnees-datamarts-talend
