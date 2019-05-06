FROM php:fpm-alpine

RUN docker-php-ext-install pdo_mysql

CMD ["php-fpm"]

# install composer
RUN apk update && apk add git zip
RUN curl --silent --show-error https://getcomposer.org/installer | php

EXPOSE 9000