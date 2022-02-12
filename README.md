# Laravel API REST Skeleton Stack

### Built on Laravel Framework - 9.0.2 (LTS, stable version)

This repository is for basic skeleton installation of the Laravel framework, its packages and other's vendors packages. It means that you can use it as a basis for your custom applications. The target is to reduce the time for developers while installing packages to build required stack for the project.


## Installed packages

### Laravel packages

- [Laravel/Passport](https://github.com/laravel/passport) - [docs](https://laravel.com/docs/9.x/passport)
- [Laravel/Breeze](https://github.com/laravel/breeze) - [docs](https://laravel.com/docs/9.x/starter-kits#breeze-and-next)
- [Laravel/Telescope](https://github.com/laravel/telescope) - [docs](https://laravel.com/docs/9.x/telescope)
- [Laravel/Horizon](https://github.com/laravel/horizon) - [docs](https://laravel.com/docs/9.x/horizon)
- [Laravel/Scout](https://github.com/laravel/scout) ([MeiliSearch](https://www.meilisearch.com/) Engine) - [docs](https://laravel.com/docs/9.x/scout)
- [Laravel/Socialite](https://github.com/laravel/socialite) - [docs](https://laravel.com/docs/9.x/socialite)

### Vendor packages

- [L5 Swagger](https://github.com/darkaonline/l5-swagger) - [wiki](https://github.com/DarkaOnLine/L5-Swagger/wiki)
- [Predis](https://github.com/predis/predis) - [wiki](https://github.com/predis/predis/wiki)

## Stack Tips

Cache, queues and sessions work using Redis server.

## Installation process

```
git clone https://github.com/avangardistpro/Laravel-API-REST-Skeleton.git <project_name>
cd <project_name>
cp .env.example .env

php artisan key:generate
php artisan migrate
php artisan passport:keys
php artisan serve
```
After that, your new project is available on [http://127.0.0.1:8000](http://127.0.0.1:8000).


<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

[Laravel Framework link](https://github.com/laravel/laravel)


## License

The Laravel-API-REST-Skeleton is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
