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
DB_HOST=
DB_PORT=3306
DB_DATABASE=laravelApp
DB_USERNAME=laravelRoot
DB_PASSWORD=password
```
