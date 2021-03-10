FROM vaugenwake/laravel:latest

WORKDIR /var/www/html

COPY . .

# PHP Extentions
RUN docker-php-ext-install bcmath
RUN docker-php-ext-install pdo_mysql

EXPOSE 9000