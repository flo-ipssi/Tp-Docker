FROM php:7.0-fpm

##################################### 
# Extension PDO
##################################### 
RUN docker-php-ext-install pdo_mysql

##################################### 
# Exstension GD
##################################### 
# Install the PHP gd library 

RUN apt-get update -y && apt-get install -y sendmail libpng-dev
RUN docker-php-ext-install gd