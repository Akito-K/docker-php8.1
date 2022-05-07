# docker-php8.1-apache

A Debian LAMP container

It's on [docker-hub](https://hub.docker.com/repository/docker/niclab/php8.1/) and [github](https://github.com/Akito-K/docker-php8.1)

## tags and links
* `latest` [(main/Dockerfile)](https://github.com/Akito-K/docker-php8.1/blob/main/Dockerfile)

## how to build

```sh
git clone git@github.com:Akito-K/docker-php8.1.git
cd docker-php8.1
docker build --rm -t niclab/php8.1 .
```

## running

```sh
docker-compose up -d
```