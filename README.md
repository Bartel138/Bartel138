## 👋 Bonjour, je suis Bartel

Bienvenue sur mon portfolio de **Data Analyst** ! Cet espace centralise mes projets et mes réalisations en lien avec l'analyse et le traitement des données.

---

## 🚀 Mes Projets

# 🚀 Laura E-commerce - Portfolio SQL & Python

## 📋 Description Générale
Ce portfolio rassemble les projets structurants de l'écosystème technique de la marque e-commerce **Laura**. Chaque dépôt représente une brique logique, combinant la modélisation et le traitement SQL (DDL, modélisation relationnelle, segmentation RFM) ainsi que la programmation Python (génération de données de test et scripts d'automatisation).

---

## 📐 1. Conception et Schéma Relationnel
* **Lien du dépôt :** [02_database_ddl_laura-ecommerce-france](https://github.com/Bartel138/02_database_ddl_laura-ecommerce-france)
* **Description :** Phase de conception en amont et de réflexion sur la modélisation des entités, posant les bases relationnelles et l'architecture des tables pour structurer l'écosystème e-commerce.
* **Mots-clés / Stack :** `SQL`, `Modélisation`, `Architecture`, `Conception de Base de Données`, `E-commerce`.

---

## 🗄️ 2. Création de la Base de Données et des Tables (DDL)
* **Lien du dépôt :** [02_database_ddl_laura-ecommerce-france](https://github.com/Bartel138/02_database_ddl_laura-ecommerce-france)
* **Description :** Script SQL complet de création de la base de données et des tables. Intégration de la gestion des types de données optimisés (`Decimal`, `Timestamp`), du moteur de stockage `InnoDB`, ainsi que de l'ensemble des contraintes, clés primaires et clés étrangères.
* **Mots-clés / Stack :** `SQL`, `MySQL`, `DDL`, `InnoDB`, `Contraintes`, `Clés Primaires / Étrangères`, `Decimal`.

---

## 🛍️ 3. Product Catalog & Spinning
* **Lien du dépôt :** [04_product-spinning---laura-ecommerce](https://github.com/Bartel138/04_product-spinning---laura-ecommerce)
* **Description :** Structuration et gestion du catalogue produits de la marque, définissant les catégories et l'arborescence des articles pour alimenter efficacement le système transactionnel (scripts de génération et gestion en Python et SQL).
* **Mots-clés / Stack :** `Python`, `SQL`, `Catalogue Produits`, `Taxonomie`, `E-commerce de Luxe`.

---

## 👥 4. Customer Batch Generator
* **Lien du dépôt :** [05_customer-batch-generator-_laura-ecommerce](https://github.com/Bartel138/05_customer-batch-generator-_laura-ecommerce)
* **Description :** Développement de scripts en Python pour la génération de données clients par batchs massifs, permettant de simuler le comportement d'une base active d'acheteurs et d'injecter des volumes réalistes.
* **Mots-clés / Stack :** `Python`, `Génération de Données`, `Batch Processing`, `Simulation CRM`.

---

## 📊 5. Segmentation RFM Avancée & Persistance SQL
* **Lien du dépôt :** [Segmentation-RFM-Avanc-e-Strat-gie-de-Persistance-SQL](https://github.com/Bartel138/Segmentation-RFM-Avanc-e-Strat-gie-de-Persistance-SQL)
* **Description :** Implémentation d'un modèle de segmentation client RFM (Récence, Fréquence, Montant) de bout en bout en SQL. Utilisation de sous-requêtes corrélées et d'une stratégie de persistance pour stocker durablement les scores, le score global sur 15 et les segments qualitatifs (`VIP`, `Fidèles`, `Occasionnels`, `Dormants`) directement dans la table client.
* **Mots-clés / Stack :** `SQL`, `RFM Analysis`, `Sous-requêtes Corrélées`, `Persistance des Données`, `Segmentation CRM`.


# 📈 Sales Performance & Business Analytics (Python)

## 📋 Description Générale
Projets indépendants d'analyse exploratoire de données (EDA), d'ingénierie de variables (Feature Engineering) et de modélisation visuelle des performances commerciales sous Python.

---

## 📈 1. Analyse Exploratoire & Tendances Temporelles de Ventes
- **Lien du dépôt :** [sales-data-analysis-python](https://github.com/Bartel138/sales-data-analysis-python)
- **Description :** Analyse globale des performances de ventes en Python : audit de la qualité des données, Feature Engineering temporel (extraction d'indicateurs via Pandas `.dt`), analyse de la dynamique mensuelle et cartographie de la structure du Chiffre d'Affaires par statut de commande via des Treemaps.
- **Mots-clés / Stack :** `Python`, `Pandas`, `Matplotlib`, `Seaborn`, `Squarify`, `EDA`, `Feature Engineering`.
- **Statut :** En cours (Partie 1 validée) 🔄

## 2. Analyse des Ventes et Performance Régionale
* **Description :** Exploration avancée d'un jeu de données de ventes pour évaluer la performance commerciale par zone géographique. Calcul automatisé des parts de marché, du panier moyen et des volumes de commandes à l'aide de Pandas, couplé à une visualisation graphique sur-mesure (Matplotlib & Seaborn).
* **Technologies :** Python, Pandas, Matplotlib, Seaborn.
* **Lien du projet :** [Accéder au dépôt GitHub](https://github.com/Bartel138/data-analyst-regional-sales-project)
  

### 📊 1. Analyse et Segmentation Client (SQL / MySQL)
* **[Accéder au projet et à la documentation complète](https://github.com/Bartel138/sql-sakila-vip-analysis)** : Extraction de la valeur client (segment VIP) sur la base Sakila, résolution de limites relationnelles par jointures, nettoyage de données textuelles et requêtage optimisé.
* **Outils** : SQL, MySQL Workbench.
* **Statut** : Terminé ✅

### 1. Audit de Performance et Analyse du Catalogue Sakila (SQL / MySQL)
* **[Accéder au projet et à la documentation](https://github.com/Bartel138/sql-sakila-movie-analysis/blob/main/README.md)** : 
Audit complet de la base Sakila structuré en trois étapes clés : analyse macro de l'offre et des genres du catalogue, étude de la demande et des volumes de locations physiques, et évaluation de la rentabilité financière (chiffre d'affaires par film).Aspects techniques : Maîtrise des jointures relationnelles (INNER JOIN vs LEFT JOIN), sécurisation des clés de liaison pour éviter toute corruption des données (notamment sur les tables de transactions et de paiements), et rédaction de requêtes SQL optimisées.Outils : SQL, MySQL Workbench, Markdown (GitHub).Statut : Terminé ✅

*(D'autres projets viendront s'ajouter ici au fur et à mesure !)*
