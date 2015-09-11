# docker-php
Docker Image with Apache + PHP
Based on xhttp build

## Example configuration ##

`docker-compose.yml`

### Development ###

    app:
        image: xhttpdev/docker-php:dev
        ports:
            - "80:80"
        volumes:
            - /var/www/myapp:/var/www/html

### Production ###

No Volume available

    app:
        image: xhttpdev/docker-php:latest
        ports:
            - "80:80"
