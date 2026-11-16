# Laravel 12 - Clean Starter

This is a clean Laravel 12 project skeleton. Composer dependencies are not bundled.

## Requirements
- PHP 8.2 or newer
- Composer 2
- Required PHP extensions for Laravel 12

## Setup
```bash
composer install
cp .env.example .env
php artisan key:generate
touch database/database.sqlite
php artisan migrate
php artisan serve
```

Open http://127.0.0.1:8000

To use MySQL instead, update the `DB_*` values in `.env` and create the database first.
