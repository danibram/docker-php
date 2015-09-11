# docker-php
Docker Image with Apache + PHP
Based on xhttp build

## Example configuration ##

`docker-compose.yml`

### Development ###

    app:
        image: danibram/docker-php
        ports:
            - "80:80"
        volumes:
            - /var/www/myapp:/var/www/html