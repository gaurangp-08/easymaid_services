# Easymaid Service

Easymaid Service is a Laravel 12 dashboard starter for a home-cleaning service. It provides an admin interface foundation with dashboard, calendar, profile, sign-in and sign-up screens, charts, forms, and reusable UI components.

> The current application is a dashboard interface foundation. Service booking, staff management, and other business workflows are not implemented yet.

## Requirements

- PHP 8.2 or later
- Composer
- Node.js and npm
- A database supported by Laravel (SQLite is configured by default)

## Setup

Install the dependencies:

```bash
composer install
npm install
```

Create the environment file and application key:

```bash
copy .env.example .env
php artisan key:generate
```

On macOS or Linux, use `cp .env.example .env` instead of `copy`.

Run the database migrations:

```bash
php artisan migrate
```

## Run Locally

Start the Laravel and Vite development services:

```bash
composer run dev
```

Open the URL printed by Laravel, usually `http://localhost:8000`.

To start the services separately, use `php artisan serve` and `npm run dev` in separate terminals.

## Build and Test

Build frontend assets for production:

```bash
npm run build
```

Run the test suite:

```bash
composer run test
```

## Tech Stack

- Laravel 12 and PHP
- Blade templates
- Tailwind CSS 4
- Alpine.js
- Vite

## License

See [LICENSE](LICENSE).
