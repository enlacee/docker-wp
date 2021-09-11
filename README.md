# WP-EXAMPLE
Wordpress dockerization

* mysql
* wordpress
* adminer (database admin)

## Command help

	docker-compose up -d
	# off container
	docker-compose down

Now create a File named `wordpress_data/env_FILE` and set all ariables.  
This variables are setting in `docker-compose.yml`

	WORDPRESS_DB_NAME=wordpress
	WORDPRESS_DB_USER=wordpress
	WORDPRESS_DB_PASSWORD=wordpress
	WORDPRESS_DB_HOST=db:3306
	WORDPRESS_DEBUG=true

## App online
live in `localhost:8000`
