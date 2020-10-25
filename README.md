# Docker for Laravel

##### Minimal Runtime Environment

##### HTTP/2 - Nginx 1.18 - PHP7.4-FPM - Node.js - MySQL 8.0

>> Attention!
>> Documentation is under construction.
>> I'm working on it... )

## Installation

To get started, make sure you have [Docker installed](https://docs.docker.com/desktop/) on your system, and then clone this repository.

```
git clone https://github.com/papahelmsman/laravel-8-docker-env.git [path-to-your-project-folder]
```


```
docker-compose build
```


```
docker-compose up -d
```

## Usage

```
docker compose exec app composer install
```

```
docker compose exec app artisan key:generate
```


```
docker compose exec app artisan migrate
```
