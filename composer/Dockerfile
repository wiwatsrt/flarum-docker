FROM php:7.1-alpine

RUN curl -sS https://getcomposer.org/installer | php -- --install-dir=/usr/bin --filename=composer 

WORKDIR /var/www/html

RUN composer self-update

CMD ["bash"]

ENTRYPOINT ["composer"]

CMD ["--help"]