
Add multi site

1. Add folders

- mysql
- src

2. Execute. Flag `-d` means, run docker in the background

$ docker-compose up -d

3. 

$ cd src
$ composer create-project laravel/laravel .


4. Migrate
$ docker-compose exec php php /var/www/html/artisan migrate