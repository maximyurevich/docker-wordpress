# Docker Wordpress

This is docker stack for my personal usage, may be useful for your projects.

## Stack

* Wordpress
* MySQL 5.7
* PHPMyAdmin
* Nginx
* Xdebug 3

## Installation

`$ docker-compose up -d --build`

## Certificate generation

`$ chmod +x certs.sh`

`$ bash certs.sh`

## Removing files

`$ chmod +x remove_all.sh remove_certs.sh remove_logs.sh remove_wordpress.sh`

### Usage

#### Removing all files

`$ bash remove_all.sh`

#### Removing nginx logs

`$ bash remove_logs.sh`

#### Removing wordpress files

`$ bash remove_wordpress.sh`
