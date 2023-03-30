FROM  bitnami/laravel:9

WORKDIR /app

COPY composer.json composer.lock /app/
RUN composer install --ignore-platform-reqs --no-ansi --no-interaction --no-scripts

COPY . .


CMD [ "php","artisan","serve","--host","0.0.0.0" ]