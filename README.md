# Gestion des Équipements Volés
Application de gestion et de traçabilité des équipements électroniques volés.

## Description
Cette application permet de :
- Gérer les déclarations d'équipements volés (téléphones, laptops, etc.)
- Rechercher un équipement par IMEI ou adresse MAC
- Alerter les propriétaires lors d'une correspondance
- Suivre l'état des équipements déclarés

## Technologies
- Java (sans framework)
- JavaFX pour l'interface graphique
- MySQL pour la persistance des données
- API REST pour la communication client-serveur

## Structure du Projet
```
src/
├── Controller/
│   ├── UserController.java
│   ├── PhoneController.java
│   └── equipementController.java
├── Model/
│   ├── User.java
│   ├── Phone.java
│   └── Equipment.java
├── View/
│   └── [fichiers JavaFX]
└── App.java
```

## Installation
1. Cloner le repository
2. Installer JavaFX SDK
3. Configurer MySQL
4. Importer les dépendances nécessaires

## Configuration
1. Créer une base de données MySQL
2. Configurer les paramètres de connexion dans le fichier de configuration
3. Lancer le serveur sur le port 9000

## Utilisation
Pour démarrer l'application :
```bash
java -jar app.jar
```

L'application sera accessible à l'adresse : `http://localhost:9000`

## Endpoints API
- `GET /api/persons/{id}` : Récupérer un utilisateur
- `POST /api/persons` : Créer un utilisateur
- `POST /api/phones` : Enregistrer un téléphone
- `GET /api/phones` : Liste des téléphones
- `GET /api/equipments` : Liste des équipements
- `POST /api/equipments` : Ajouter un équipement

## Auteurs
- Balbino Tchoutzine and Five T

## Date de remise
8 avril 2025
