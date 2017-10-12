# Docker Magento Configuration

Docker running Nginx, PHP-FPM 5.6.31, and MySQL

## Basic Usage

1. Run `docker-compose up -d`
2. Run localhost di browser
3. Akan muncul tampilan phpinfo() pada browser
4. Jika sudah muncul, matikan container yang berjalan dengan `docker-compose stop`
5. Install PHP Extension untuk magento usage dengan cara `docker-compose build`
6. Delete index.php di dalam folder web/public
7. Clone Project di dalam folder web/public
8. Jalankan `docker-compose up -d` kembali untuk menjalankan instalasi magento 1

## Database

## Config File
.env File

`#!/usr/bin/env bash

NGINX_HOST=local.kawanlama.com (Host name)

MYSQL_HOST=mysql
MYSQL_DATABASE=kawanlama (Database name that you want to create)
MYSQL_ROOT_USER=root
MYSQL_ROOT_PASSWORD=root
MYSQL_USER=root
MYSQL_PASSWORD=root`


## Debuging

## SSL Configuration
