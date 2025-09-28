# 🚀 Laravel Project

A **modern Laravel application** built with performance, scalability, and clean code in mind.

![Laravel](https://img.shields.io/badge/Laravel-11.x-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-8.1+-777BB4?style=flat-square&logo=php&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## ✨ Features
- ⚡ Built with **Laravel 11+**
- 🔑 Authentication & Authorization
- 🌐 RESTful APIs
- 📦 Database Migrations & Seeders
- 🗄️ Eloquent ORM
- 🎨 Blade Templates with Vite
- ✅ Unit & Feature Testing

---

## ⚙️ Requirements
- **PHP** >= 8.1  
- **Composer** >= 2.x  
- **Laravel** >= 11.x  
- **MySQL / MariaDB**  
- **Node.js & NPM** (for frontend assets)  

---

## 🚀 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/laravel-project.git

# Go to project folder
cd laravel-project

# Install PHP dependencies
composer install

# Install frontend dependencies
npm install && npm run dev

# Copy environment file
cp .env.example .env

# Generate app key
php artisan key:generate

# Configure database in .env and run migrations
php artisan migrate --seed

# Start local development server
php artisan serve
