# Postgres DB #

Basic PostgreSQL container for development purposes

### Dependencies ###

* Docker >=17.12.0+
* Docker-Compose

### How to run? ###

* Clone repo
* cd to docker-compose.yml dir
* docker-compose up -d

### Settings ###

Edit "docker-compose.yml" with your favorite editor 

* POSTGRES_USER the default value is postgres
* POSTGRES_PASSWORD the default value is x0123456789
* PGADMIN_PORT the default value is 5050
* PGADMIN_DEFAULT_EMAIL the default value is admin@dbmaster.io
* PGADMIN_DEFAULT_PASSWORD the default value is y0123456789


### Default access to postgres db ###

* localhost:5432
* Username: postgres
* Password: x0123456789


### Default access to pgadmin ###

* URL: http://localhost:5050
* Username: admin@dbmaster.io
* Password: y0123456789
* hostname to use in pgadmin : postgres
