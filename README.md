# Projet de Réservation Immobilière - Test Technique

Application de gestion de réservations immobilières développée avec Laravel, Livewire, Filament v3 et TailwindCSS.

## 🛠️ Fonctionnalités réalisées

### 1. Base de données
- Création des tables `properties` et `bookings` avec les relations nécessaires.
- Mise en place des relations entre Users, Properties et Bookings.
- Ajout de données de test (Villas et Appartements).

### 2. Interface utilisateur
- Authentification avec Laravel Breeze (inscription / connexion).
- Design avec TailwindCSS et couleurs personnalisées.
- Composant Livewire `BookingManager` pour réserver sans recharger la page.

### 3. Administration
- Mise en place d’un panneau d’administration avec Filament.
- Gestion des propriétés et des réservations via formulaires et tableaux.
---

## ⚙️ Installation

### 1. Installer les dépendances

```bash
composer install
npm install && npm run dev
```

### 2. Base de données (SQLite)

```bash
php artisan migrate --seed
```

### 3. Lancement

```bash
php artisan serve
```

---

## 🔐 Accès de test

Utilisateur / Admin : [houssamouaaliti222005@gmail.com]  
Mot de passe : [test]

---

Le dépôt contient le code source complet ainsi que les captures d’écran du projet.
