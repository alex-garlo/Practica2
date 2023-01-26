FROM php:7.4-cli
COPY ./your-script.php /var/www/html/index.php
WORKDIR /home/usuario/Docker-1
CMD [ "php", "-S", "0.0.0.0:8080", "-t", "/var/www/html" ]
