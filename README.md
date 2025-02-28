# Créer et utiliser une base de données immobilières - Projet DATAImmo 🏡📊

# Description du projet 📝

Le projet DATAImmo a pour objectif de créer et d'utiliser une base de données immobilières afin de mieux prévoir le prix de vente des biens immobiliers. Ce projet s'inscrit dans une initiative stratégique de Laplace Immo, un réseau national d’agences immobilières, visant à se démarquer de la concurrence grâce à l’analyse des données du marché.

Le projet consiste à modifier et optimiser une base de données utilisée pour collecter les transactions immobilières et foncières en France 🇫🇷. Une fois la base de données améliorée, elle sera utilisée pour analyser le marché immobilier, fournir des insights sur les tendances du marché et aider les agences régionales à mieux accompagner leurs clients dans leurs achats et ventes de biens immobiliers.

# Objectifs principaux 🎯

Réarranger les données pour construire un dictionnaire de données complet et un schéma relationnel conforme aux normes de la 3NF (Troisième Forme Normale).
Créer une base de données performante ⚙️, avec une structure optimisée pour l’exécution de requêtes complexes.
Effectuer des requêtes SQL 📑 afin d’extraire des données clés permettant d’analyser le marché immobilier, comme les prix de vente 💰, les surfaces 📏, et les tendances régionales 🌍.
Respect du RGPD 📜
Le projet respecte pleinement le Règlement Général sur la Protection des Données (RGPD), garantissant que toutes les données personnelles et sensibles sont manipulées de manière sécurisée 🔒 et respectueuse des droits des utilisateurs.

# Outils utilisés 🛠️

SQLite 🗄️ : Gestion de la base de données relationnelle.
Excel 📊 : Élaboration du dictionnaire de données et analyse préliminaire des données.
Draw.io 🎨 : Création du schéma relationnel de la base de données.
Résultats du premier semestre 2020 📅

# Principaux Résultats :

Région parisienne 🏙️ : Enregistre le plus grand nombre de ventes immobilières en France.
Augmentation des ventes 📈 : Une hausse des ventes entre le premier et le second trimestre de 2020 a été observée.
Surface vs Prix au m² 📏💵 : Plus la surface des biens augmente, plus le prix au m² tend à diminuer.
Centre-Val de Loire 🌳 : Cette région possède la plus grande superficie de terrain parmi les biens immobiliers vendus.

# Structure du projet 📂

La structure du projet est organisée de manière à faciliter l’accès aux différentes ressources et scripts :

BASE_DE_DONNÉE_IMMOBILIERE/
│── data/                      # Données sources en format CSV
│   │── biens.csv              # Liste des biens immobiliers
│   │── Communes.csv           # Informations sur les communes
│   │── departement.csv        # Informations sur les départements
│   │── donnees_de_base.zip    # Archive contenant les données de base
│   │── région.csv             # Informations sur les régions
│   │── ventes.csv             # Historique des ventes immobilières
│
│── documentation_bdd/         # Documentation sur la base de données
│   │── bdd_sql/               # Dossier avec la base SQL
│   │── Dictionnaire_de_donnees.xlsx  # Dictionnaire des données
│   │── schema_relationnel_base_de_donnee_immo.png  # Schéma relationnel de la BDD
│
│── presentation/              # Présentation du projet
│   │── support_presentation_requete_base_immo.pptx  # Présentation PowerPoint
│
│── requetes/                  # Scripts SQL
│   │── creation_bdd.sql       # Script de création de la base de données
│   │── requetes_bdd.sql       # Requêtes SQL pour l'exploitation des données
│
│── .gitignore                 # Fichier pour ignorer certains fichiers dans Git
│── README.md                  # Documentation principale du projet
