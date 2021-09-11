# Docker-Wp

Wordpress Dockerizing

* [Mysql](https://www.mysql.com/)
* [Wordpress](https://wordpress.org/download/)
* [Adminer](https://www.adminer.org/)

## Command help

	docker-compose up -d
	docker-compose down # turn-off all containers

Now create a File named `wordpress_data/env_FILE` and set all variables.  
This variables are setting in `docker-compose.yml`

	WORDPRESS_DB_NAME=wordpress
	WORDPRESS_DB_USER=wordpress
	WORDPRESS_DB_PASSWORD=wordpress
	WORDPRESS_DB_HOST=db:3306
	WORDPRESS_DEBUG=true

## App online

Server wordpress: `http://localhost:8000`  
Database manager: `http://localhost:8080`  