# Laravel Backend for the course "Laravel Backends for Vue.js 3"

[![](https://vueschool.io/media/1b4b17d7dfaf4a708fbd160ba767b6d8/laravel-backends-for-vue-js-3-not-transparent.jpg)](https://vueschool.io/courses/laravel-backends-for-vue-js-3)

This repository contains the source code for the backend that's used in the course "Laravel Backends for Vue.js 3".

Pair this respository with the front end SPA to power a URL Shortener app.

## Setup Instructions

To run the backend, clone this repo.

```
git clone git@github.com:vueschool/laravel-course-backend.git
```

Install the dependencies with composer (make sure to [have composer installed](https://getcomposer.org/))

```
composer install
```

Start the development server with Laravel Sail (requires [docker](https://www.docker.com/) to be installed and running)

```
./vendor/bin/sail up
```

Run laravel application using docker 100% on windows
```
https://medium.com/dev-genius/setting-up-an-existing-laravel-application-100-with-docker-on-windows-870176679819
```
Resolve possible Sail's errors 
```
 sudo apt-get clean
```
```
 docker system prune
```
```
 ./vendor/bin/sail build --no-cache
```
```
 ./vendor/bin/sail up
```
