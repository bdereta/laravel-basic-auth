## Laravel with Basic Auth

This is a Laravel 10.x project with basic authentication.

### Installation

1. Clone the repository: `git clone git@github.com:bdereta/laravel-basic-auth.git`
2. Change directory: `cd laravel-basic-auth`
3. Create local .env: `cp .env.example .env`
4. Run `composer install`
5. Build docker: `./vendor/bin/sail build`
6. Start docker: `./vendor/bin/sail up -d`
7. Generate app key: `./vendor/bin/sail php artisan key:generate`
8. Run npm: `./vendor/bin/sail npm install && ./vendor/bin/sail npm run dev`

### Usage

1. Register: http://localhost/register
2. Login: http://localhost/login
