# Simple Laravel Breeze API to a course plataform

## #1 Create a MySQL database

```bash
sudo mysql
```

```SQL
create database laravelApp;

CREATE USER 'laravelRoot'@'localhost' IDENTIFIED BY 'password'; 

GRANT ALL PRIVILEGES ON laravelApp.* TO 'laravelRoot'@'localhost' IDENTIFIED BY 'password';
```

## #2 On .env file

```bash
DB_CONNECTION=mysql
DB_HOST=localhost
DB_PORT=3306
DB_DATABASE=laravelApp
DB_USERNAME=laravelRoot
DB_PASSWORD=password
```


# MAKED
 - [x] Create a MySQL database
 - [x] On .env file
 - [X] Create a Laravel Breeze API
 - [X] Create a User model
 - [X] Create a User controller
 - [X] Create a User migration
 - [x] Add Swagger to the project

# TO MAKE
