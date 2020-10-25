FROM nginx:stable-alpine

LABEL maintainer="papahelmsman <papahelmsman@gmail.com>"

ADD ./nginx.conf /etc/nginx/nginx.conf
ADD ./conf.d/default.conf /etc/nginx/conf.d/default.conf

RUN mkdir -p /srv/app/public

RUN addgroup -g 1000 laravel && adduser -G laravel -g laravel -s /bin/sh -D laravel

RUN chown laravel:laravel /srv/app/public

WORKDIR /srv/app/public
