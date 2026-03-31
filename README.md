# Blog Laravel

Un système de blog minimaliste avec Laravel 10 et Tailwind CSS.

## 🚀 Installation

1. **Cloner le projet**
   ```bash
   git clone <url-du-repo>
   cd blog
   ```

2. **Dépendances PHP**
   ```bash
   composer install
   ```

3. **Dépendances JS**
   ```bash
   npm install && npm run dev
   ```

4. **Configuration**
   - Créer un fichier `.env` (copier `.env.example`).
   - Configurer la base de données dans `.env`.
   - Générer la clé : `php artisan key:generate`.
   - Migrations : `php artisan migrate`.

5. **Lancement**
   ```bash
   php artisan serve
   ```

## ✨ Fonctionnalités

- Authentification (Laravel Breeze)
- Création / Édition d'articles (CRUD)
- Système de commentaires
- Like des articles
- Profils publics des auteurs
- Dashboard utilisateur

---

