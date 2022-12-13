# Dockerize Codeigniter
Docker compose to setup nginx, php and mysql for codeigniter 4.0.3.  

## Images
1. nginx → nginx:latest
2. php → php:8-fpm
3. mysql → mysql:8

## Deployment using Docker
1. Deploy nginx, php-fpm, and mysql using docker-compose
    ```bash
    docker-compose up -d
    ```
2. Stop container
    ```bash
    docker-compose stop
    ```

