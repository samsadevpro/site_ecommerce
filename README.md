# 👟 Site E-Commerce - Sneakers Hub

Un site e-commerce moderne pour la vente de chaussures (Nike, Adidas, Asics), développé en **PHP natif** (sans framework) dans le cadre d'un projet académique (E6). Le site permet aux utilisateurs de naviguer, rechercher des produits, gérer un panier et passer des commandes de manière fluide et sécurisée.

---

## ✨ Fonctionnalités Principales

### 👤 Gestion des Utilisateurs
- **Inscription & Connexion** : Système d'authentification sécurisé.
- **Profil Utilisateur** : Consultation des informations personnelles.
- **Déconnexion** : Gestion sécurisée de la session.

### 🛍️ Boutique & Produits
- **Catalogue Dynamique** : Affichage des produits récupérés depuis une base de données MySQL.
- **Filtrage par Marque** : Pages dédiées pour Nike, Adidas et Asics.
- **Recherche Intelligente** : Moteur de recherche par nom de produit ou par marque.
- **Détails Produits** : Fiches descriptives avec images et prix.

### 🛒 Panier & Commandes
- **Gestion du Panier** : Ajout et suppression de produits en temps réel.
- **Calcul Dynamique** : Mise à jour automatique des totaux (sous-total, TVA, total).
- **Processus de Paiement** : Simulation de paiement et confirmation de commande.

### 🎨 Design & UX
- **Responsive Design** : Interface adaptée aux mobiles, tablettes et ordinateurs.
- **Thème Sombre/Clair** : Toggle intégré pour changer l'apparence visuelle.
- **Animations fluides** : Effets de survol et transitions CSS modernes.

---

## 🛠️ Stack Technique

- **Frontend** : HTML5, CSS3 (Custom), JavaScript (Vanilla).
- **Backend** : PHP 8.x (Natif).
- **Base de données** : MySQL via PDO & MySQLi.
- **Serveur recommandé** : Laragon ou WAMP/XAMPP.

---

## 🚀 Installation & Configuration

### 1. Prérequis
- Un serveur local (**Laragon** vivement recommandé).
- PHP >= 7.4.
- MySQL.

### 2. Clonage du projet
Placez les fichiers dans votre répertoire `www` (Laragon) ou `htdocs` (XAMPP) :
```bash
C:\laragon\www\Site_e_commerce
```

### 3. Base de données
1. Créez une base de données nommée `ecommerce`.
2. Importez le fichier SQL (si disponible) ou configurez vos tables `users`, `products`, et `cart`.

### 4. Configuration
Éditez le fichier `config.php` à la racine pour adapter vos identifiants si nécessaire :
```php
$host = "localhost";
$dbname = "ecommerce";
$user = "root";
$password = "";
```

---

## 🎓 Contexte du Projet
Ce projet a été réalisé pour démontrer les compétences en développement web backend (PHP/SQL) et frontend sans l'utilisation de frameworks lourds, mettant l'accent sur la logique métier et la sécurité des données.
