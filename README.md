## Laravel with Basic Auth

This is a Laravel 10.x project with basic authentication.

### Installation

1. Clone the repository: `git clone git@github.com:bdereta/laravel-basic-auth.git`
2. Copy `.env.example` to `.env`
3. Run `composer install`
4. Build docker `./vendor/bin/sail build`
5. Start docker `./vendor/bin/sail up -d`
6. Run npm: `./vendor/bin/sail npm install && ./vendor/bin/sail npm run dev`

### Usage

1. Register: http://localhost/register
2. Login: http://localhost/login
