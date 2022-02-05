<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Required

- PHP 7.4++
- MySQL 8
- Laravel 8
- composer

## How to install

- $ git clone 
- $ cd socialLogin/laravel
- $ composer install
- $ mv .env.example .env
- $ php artisan key:generate

## Edit file .env

DB_CONNECTION=mysql <br>
DB_HOST=**<YOUR_DB_HOST>** <br>
DB_PORT=3306 <br>
DB_DATABASE=**<YOUR_DB_DATABASET>** <br>
DB_USERNAME=**<YOUR_DB_USERNAME>** <br>
DB_PASSWORD=**<YOUR_DB_PASSWORD>** <br>

GOOGLE_CLIENT_ID=**<YOUR_GOOGLE_CLIENT_ID>** <br>
GOOGLE_CLIENT_SECRET=**<YOUR_GOOGLE_CLIENT_SECRET>** <br>
GOOGLE_REDIRECT_URI=http://localhost:8000/api/login/google/callback
 
## RUN
- $ php artisan migrate
- $ php artisan serve
- Go to http://localhost:8000/api/login/google
