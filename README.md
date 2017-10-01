# Docker Magento Configuration

Docker running Nginx, PHP-FPM, and MySQL

## Basic Usage

1. Run `docker-compose up -d`
2. Run localhost di browser
3. Akan muncul tampilan phpinfo() pada browser
4. Jika sudah muncul, matikan container yang berjalan dengan `docker-compose stop`
5. Install PHP Extension untuk magento usage dengan cara `docker-compose build`
6. Delete index.php di dalam folder web/public
7. Clone Project di dalam folder web/public
8. Jalankan `docker-compose up -d` kembali untuk menjalankan instalasi magento 1

## Config File

## Debuging

## SSL Configuration