FROM nginx:stable-alpine

WORKDIR /var/www/html

COPY ./ops/docker/nginx/default.conf /etc/nginx/conf.d/default.conf

COPY . .

EXPOSE 80