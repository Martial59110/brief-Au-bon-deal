# Sommaire du dépôt

1. [Règles gestion](/doc/regles-gestion.md) 📄 
2. [Propositions d'améliorations](/doc/proposition-amelioration.md) 📄 
3. [Politique de rétention](/doc/securite/politique-de-retention.md) 📄 
4. [RGPD](/doc/securite/RGPD.md) 📄 
5. [Stratégie de sécurisation](/doc/securite/strategie-de-securisation.md) 📄 
6. [RBAC](/doc/securite/RBAC.md) 📄 
7. [Benchmark de la base de données](/doc/benchmarks/bdd.md) 📄 
8. [Dictionnaire de données](/doc/BDD/dictionnaire-donnees.md) 📄 
9. [Base de données initiale](/doc/BDD/init_database.sql) 📄 
10. [Dossier sauvegardes](/doc/BDD/sauvegardes/) 📁


# Table des Matières
1. [Contexte du projet](#contexte-du-projet)
2. [Définition de MERISE](#définition-de-merise)
3. [Critères de Performance](#critères-de-performance)
4. [Documents Fournis](#documents-fournis)





## Contexte du Projet

Bienvenue sur **AuBonDeal** 🚀, une plateforme en cours de développement dédiée au commerce en ligne, visant à fournir une solution performante pour la gestion des transactions, la mise en relation des vendeurs et acheteurs, ainsi que la gestion des produits. Ce projet ambitionne de créer un espace sûr et efficace où les utilisateurs peuvent acheter, vendre et échanger des biens en ligne de manière fluide.

Dans le cadre de ce projet, plusieurs aspects techniques et fonctionnels doivent être pris en charge pour garantir un fonctionnement optimal et sécurisé. L'objectif est de concevoir et d'implémenter une base de données relationnelle robuste, qui répond aux besoins de gestion des données commerciales tout en assurant la sécurité et la performance de la plateforme.

### Objectifs de la Mission

1. **Analyse des Modèles de Données**
   - Examiner et interpréter les Modèles Conceptuels (MCD) et Logiques (MLD) de Données fournis pour identifier les entités, attributs et relations clés.
   - Cette étape permet de comprendre l'architecture des données, préalable nécessaire pour une mise en œuvre cohérente.

2. **Création de la Base de Données**
   - Traduire le MCD et le MLD en une base de données relationnelle SQL.
   - Définir les tables, les clés primaires et étrangères, ainsi que les contraintes d’intégrité pour assurer la cohérence des données.

3. **Gestion des Opérations CRUD**
   - Implémenter des opérations CRUD (Create, Read, Update, Delete) pour assurer une interaction efficace et sécurisée avec la base de données.
   - Porter une attention particulière à la performance et à la sécurité, incluant la gestion des rôles et permissions.

4. **Exportation et Sauvegarde de la Base de Données**
   - Mettre en place une stratégie d'exportation et de sauvegarde de la base de données avec les commandes SQL appropriées.
   - Définir une **politique de rétention des sauvegardes**, documentée pour spécifier la fréquence, la durée de conservation et les procédures de restauration, en assurant une protection contre les menaces potentielles.

## Définition de MERISE


**MERISE** est l'acronyme de **Méthode d'étude et de réalisation informatique pour les systèmes d'entreprise**. Il s’agit d’une méthodologie française d’analyse et de conception de systèmes d’information, créée pour structurer et modéliser les données et les traitements d'une manière cohérente. Elle est particulièrement utile pour concevoir des bases de données et des systèmes d’information robustes et évolutifs.

 L'approche MERISE repose sur plusieurs modèles, chacun apportant une vue spécifique de l'application :

- **Modèle Conceptuel de Données (MCD)** : Il représente les entités principales du système, leurs attributs et les relations qui les lient. Il se concentre sur la structure des données sans se préoccuper de la manière dont elles seront physiquement stockées.
  
- **Modèle Logique de Données (MLD)** : Il découle du MCD et est adapté aux contraintes techniques d'une base de données relationnelle. Le MLD décrit comment les données seront organisées en tables avec des clés primaires, des clés étrangères et des relations respectant les règles d'intégrité.

La méthodologie MERISE est particulièrement utile pour **concevoir des bases de données robustes et évolutives**, car elle offre une vision complète de l'organisation des données tout au long du cycle de vie du projet. Elle est employée dans ce projet pour guider la conception et la structuration de la base de données de la plateforme **AuBonDeal**.



## Critères de Performance

Pour assurer la qualité et la robustesse de la base de données conçue pour AuBonDeal, les critères suivants seront respectés :

- **Fidélité de la Transposition** : La traduction des modèles MCD et MLD en une base de données PostgreSQL doit être précise, avec une structure conforme aux modèles fournis.
- **Sécurité des Accès** : Mise en place d’une gestion des rôles et des permissions, garantissant des accès contrôlés et sécurisés aux différentes parties de la base de données.
- **Qualité de la Documentation** : La documentation doit être complète et claire, permettant à tout utilisateur de comprendre facilement la structure de la base de données et les choix techniques effectués.
- **Amélioration des Diagrammes** : Les diagrammes fournis contiennent volontairement des erreurs ; une analyse critique et des suggestions d’amélioration devront être proposées, avec des explications structurées et justifiées.
- **Qualité du Dépôt GitHub** : Le dépôt GitHub doit être bien organisé, sans erreurs, et suivre les bonnes pratiques de gestion de version pour faciliter la compréhension et l’accès au projet.

## Documents Fournis

Dans le cadre de ce projet, les documents suivants ont été mis à disposition pour guider la création de la base de données et sa structure :

- **Modèle Conceptuel de Données (MCD)** : Ce modèle illustre les entités principales et leurs relations, servant de base pour la compréhension des données.

![MCD](/doc/BDD/MCD.png)

- **Modèle Logique de Données (MLD)** : Le MLD traduit le MCD en une version adaptée à une base de données relationnelle, incluant les tables et les relations entre elles.

![MLD](/doc/BDD/MLD.png)
  
**Note** : Le MLD contient des erreurs intentionnelles ; ils nécessitent donc une analyse critique et des propositions d’amélioration avant la mise en œuvre.
