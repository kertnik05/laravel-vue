# Laravel+Vue Boilerplate #

## Requirements before Installation
* PHP >= 7.3
* RDBMS (MySQL, PostgreSQL, etc.)
* BCMath PHP Extension
* Ctype PHP Extension
* Fileinfo PHP extension
* JSON PHP Extension
* Mbstring PHP Extension
* OpenSSL PHP Extension
* PDO PHP Extension
* Tokenizer PHP Extension
* XML PHP Extension

## Quick Installation
1. Clone this repo
2. `cd <project-directory>`
3. `composer install`
4. Create a database
5. Create new file *.env*
6. Copy all the contents of *.env.example* to *.env*
7. Configure database in *.env*
8. Run `php artisan key:generate`
9. `php artisan migrate --seed` to create and populate tables
10. `php artisan serve` to start the app on http://127.0.0.1:8000/