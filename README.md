# Services Étudiants

Application Laravel pour la gestion des demandes étudiantes (attestation de scolarité, relevé de notes...).

## Fonctionnalités
- Espace étudiant : formulaire, validation, enregistrement
- Espace admin : gestion des demandes, email, téléchargement
- Dashboard & statistiques

## Technologies
- Laravel (PHP)
- HTML/CSS/JS
- MySQL

## Installation
1. Cloner le dépôt
2. `composer install`
3. `cp .env.example .env`
4. Configurer `.env` avec la base de données
5. `php artisan key:generate`
6. `php artisan migrate --seed`
7. `php artisan serve`

## Auteur
Lamiae Maroun
