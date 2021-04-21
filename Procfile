release: composer release
web: composer warmup && vendor/bin/heroku-php-nginx -C heroku/nginx.conf -F heroku/php-fpm.conf public
