
# Système de Gestion de Bibliothèque - 2iE

## Description

Application web de gestion de bibliothèque développée avec Next.js, Node.js et MySQL.

## Fonctionnalités

* 📚 Gestion du catalogue de livres
* 👥 Gestion des utilisateurs (étudiants et administrateurs)
* 📖 Système d'emprunt de livres
* ⭐ Système de notation et commentaires
* 🔐 Authentification et autorisation

## Technologies utilisées

* **Frontend** : Next.js 15.3.4, React, Tailwind CSS
* **Backend** : Node.js, Express.js
* **Base de données** : MySQL 8.0
* **Containerisation** : Docker, Docker Compose

## Installation et lancement

### Prérequis

* Docker et Docker Compose installés
* Git installé

### Étapes

1. Cloner le repository

```bash
git clone https://github.com/Imaane200/mon-super-projet.git
cd mon-super-projet
```

2. Lancer l'application avec Docker

```bash
docker compose up
```

3. Accéder à l'application

* Frontend : http://localhost:3000
* Backend API : http://localhost:8000

## Utilisation

### Compte administrateur par défaut

* Email : `admin@bibliotheque2ie.com`
* Mot de passe : `admin123`

## Structure de la base de données

* **etudiants** : Gestion des utilisateurs
* **livres** : Catalogue des livres
* **emprunts** : Suivi des emprunts
* **commentaires** : Avis et notes des livres

## Développement

### Commandes utiles

```bash
# Arrêter les conteneurs
docker compose down

# Voir les logs
docker logs backend-container
docker logs frontend-container

# Accéder à MySQL
docker exec -it mysql-container mysql -u appuser -p bibliotheque_2ie
```

### Structure du projet

```
mon-super-projet/
├── frontend/          # Application Next.js
├── backend/           # API Node.js
├── .env              # Variables d'environnement
├── .gitignore        # Fichiers ignorés par Git
├── docker-compose.yml # Configuration Docker
└── README.md         # Documentation
```

## Contribuer

1. Fork le projet
2. Créer une branche pour votre fonctionnalité
3. Commit vos changements
4. Push vers la branche
5. Ouvrir une Pull Request

## Licence

Ce projet est sous licence MIT.

## Auteur

**SAWADOGO Imaane** - Étudiante en Informatique Intelligence Artificielle et Application au 2iE (Institut International d'Ingénierie de l'Eau et de l'Environnement)