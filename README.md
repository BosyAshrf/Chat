# Chat

A small authenticated chat built with Laravel and Livewire. Signed-in users send messages that are stored and shown in the chat view.

## Stack

PHP 8, Laravel 8, Livewire 2, Laravel Breeze

## Run locally

```bash
cp .env.example .env
composer install
npm install
npm run dev
php artisan key:generate
php artisan migrate
php artisan serve
```
