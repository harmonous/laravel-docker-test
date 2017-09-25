# Laravel docker test
http://localhost:8080

Start/stop docker

    docker-compose [up/down] -d
Composer install

    docker run --rm -v E:/docker/laravel:/app composer/composer install
PHP artisan

    docker-compose exec app php artisan [command]

Following tutorial: https://medium.com/@shakyShane/laravel-docker-part-1-setup-for-development-e3daaefaf3c
