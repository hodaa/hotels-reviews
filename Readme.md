# Hotels  Restful Api
RESTful API For hotels feedback.

## Installation

```
docker-compose build 
docker-compose up -d
docker-compose exec php composer install
docker-compose exec php bin/console doctrine:database:create
docker-compose exec php bin/console doctrine:migrations:migrate
docker-compose exec php bin/console doctrine:fixtures:load
```

# How to use

Overtime Endpoint Ex:

```
http://localhost:3000/api/v1/hotel-reviews?hotel_id=1&start_date=2018-01-01&end_date=2020-02-01
```

## Tools
* Symfony 5
* Docker
* PHP7.4
* Doctrine
* Mysql


##  API Collection

```
https://www.getpostman.com/collections/edde5b4aa7b913be2ac1
```

## Test

```
docker-compose exec php bin/phpunit
```

