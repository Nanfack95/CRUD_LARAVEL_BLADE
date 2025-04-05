# Documentation Technique - Projet Laravel_CRUD_Client

## Description du Projet
Laravel_CRUD_Client est une application web Laravel qui gère un système de gestion de clients. Elle permet de réaliser les opérations CRUD (Create, Read, Update, Delete) sur les informations des clients.

## Configuration Technique
- Framework : Laravel
- Base de données : MySQL
- Frontend : Blade Templates

## Structure du Projet
```
Firs/
├── app/
│   ├── Http/Controllers/
│   │   └── ClientController.php
│   └── Models/
│       └── Client.php
├── resources/
│   └── views/
├── routes/
│   └── web.php
└── database/
    └── migrations/
```

## Modèle de Données
### Client
- npr (Nom Prénom)
- adresse
- email

## Routes Disponibles
| Méthode | URL | Action | Description |
|---------|-----|--------|-------------|
| GET | /clients | index | Liste tous les clients |
| GET | /clients/create | create | Affiche le formulaire de création |
| POST | /clients | store | Enregistre un nouveau client |
| GET | /clients/{id} | show | Affiche un client spécifique |
| GET | /clients/{id}/edit | edit | Affiche le formulaire d'édition |
| PUT/PATCH | /clients/{id} | update | Met à jour un client |
| DELETE | /clients/{id} | destroy | Supprime un client |

## Fonctionnalités
1. **Gestion des Clients**
   - Affichage de la liste des clients
   - Ajout d'un nouveau client
   - Modification des informations d'un client
   - Suppression d'un client
   - Visualisation des détails d'un client

## Installation
1. Cloner le projet : `git clone https://github.com/Nanfack95/CRUD_LARAVEL_BLADE.git`
2. Installer les dépendances : `composer install`
3. Copier le fichier .env.example : `cp .env.example .env`
4. Générer la clé d'application : `php artisan key:generate`
5. Configurer la base de données dans le fichier .env
6. Exécuter les migrations : `php artisan migrate`
7. Lancer le serveur : `php artisan serve`

## Technologies Utilisées
- PHP 8.x
- Laravel 10.x
- MySQL
- HTML/CSS
- Blade Template Engine

## Auteur
[Nanfack95](https://github.com/Nanfack95)

## Contact

Email: [nanfackjospinduclair@gmail.com](mailto:nanfackjospinduclair@gmail.com)

GitHub: [Nanfack95](https://github.com/Nanfack95)
