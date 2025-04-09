# food-control-app
# API de Gestion des Équipements

Une API RESTful pour la gestion des utilisateurs, téléphones et équipements.

## 🚀 Fonctionnalités

### Gestion des Utilisateurs
- Création de compte
- Authentification
- Mise à jour des informations
- Suppression de compte
- Récupération des détails utilisateur

### Gestion des Téléphones
- Ajout de nouveaux téléphones
- Recherche par IMEI
- Liste de tous les téléphones
- Mise à jour des informations
- Mise à jour du statut
- Suppression

### Gestion des Équipements
- Ajout de nouveaux équipements
- Recherche par adresse MAC
- Liste de tous les équipements
- Mise à jour des informations
- Mise à jour du statut
- Suppression

## 🛠 Technologies Utilisées
- Java
- HTTP Server (com.sun.net.httpserver)
- Architecture MVC

## 🔧 Installation

1. Clonez le repository
```bash
git clone [URL_DU_REPO]
```

2. Compilez le projet
```bash
javac -d bin src/*.java
```

3. Lancez le serveur
```bash
java -cp bin App
```

## 🌐 Endpoints API

### Utilisateurs
- `POST /api/persons` - Créer un utilisateur
- `GET /api/persons/{id}` - Obtenir un utilisateur
- `PUT /api/persons/{id}` - Mettre à jour un utilisateur
- `DELETE /api/persons/{id}` - Supprimer un utilisateur
- `POST /api/login` - Authentification

### Téléphones
- `POST /api/phones` - Ajouter un téléphone
- `GET /api/phones` - Liste des téléphones
- `GET /api/phones/{imei}` - Détails d'un téléphone
- `PUT /api/phones/{imei}` - Modifier un téléphone
- `PUT /api/phones/{imei}/status` - Modifier le statut
- `DELETE /api/phones/{imei}` - Supprimer un téléphone
- `GET /api/phones/search` - Rechercher un téléphone

### Équipements
- `POST /api/equipments` - Ajouter un équipement
- `GET /api/equipments` - Liste des équipements
- `GET /api/equipments/{mac}` - Détails d'un équipement
- `PUT /api/equipments/{mac}` - Modifier un équipement
- `PUT /api/equipments/{mac}/status` - Modifier le statut
- `DELETE /api/equipments/{mac}` - Supprimer un équipement
- `GET /api/equipments/search` - Rechercher un équipement

## 📝 Configuration
Le serveur fonctionne par défaut sur le port 9000.

## 🤝 Contribution
Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une issue ou à proposer une pull request.

## 📄 Licence
[Type de Licence]

## 👥 Auteurs
[Vos noms] 
