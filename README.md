# elkiki99

A modern full‑stack starter kit built with Laravel, Vue 3, and Tailwind CSS, crafted by Bruno Rossani.

## Tech Stack

[![Laravel](https://img.shields.io/badge/Laravel-10.x-F05340?logo=laravel)](https://laravel.com)
[![Vue.js](https://img.shields.io/badge/Vue-3.x-4FC08D?logo=vue.js)](https://vuejs.org)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.x-38B2AC?logo=tailwind-css)](https://tailwindcss.com)
[![PHP](https://img.shields.io/badge/PHP-8.2-777BB4?logo=php)](https://www.php.net)
[![Node.js](https://img.shields.io/badge/Node-20.x-339933?logo=node.js)](https://nodejs.org)

## Features

- Laravel backend with API resources and Sanctum authentication
- Vue 3 composition API with Pinia state management
- TailwindCSS utility‑first styling and dark mode support
- Real‑time notifications via Laravel Echo & Pusher
- Automated testing with PHPUnit and Vitest
- Docker‑ready development environment

## Installation

```bash
# Clone the repository
git clone https://github.com/elkiki99/elkiki99.git
cd elkiki99

# Install PHP dependencies
composer install

# Install Node dependencies
npm install

# Copy env files and generate keys
cp .env.example .env
php artisan key:generate
php artisan storage:link

# Run migrations and seeders
php artisan migrate --seed

# Build assets
npm run dev   # or npm run prod for production

# Start the development server
php artisan serve
```