# CakePHP Application

Simple application with list of users and CRUD actions.

## Installation

Copy `config/app_local.example.php` to `config/app_local.php`.

Copy `config/.env.example` to `config/.env`.

Create database and edit env variable `DATABASE_URL`.

Install Composer dependencies:

```bash
composer install
```

Run migrations:

```bash
bin/cake migrations migrate --no-lock
```

Run seeds:

```bash
bin/cake migrations seed
```

Run the server:

```bash
bin/cake server -p 8765
```

Then visit `http://localhost:8765` to see the home page.
