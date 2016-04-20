Docker Nginx PHP Node
=====================

![Tavis Image](https://travis-ci.org/arnaudbaali/docker-php-nginx.svg?branch=master)
![Docker logo](https://sematext.com/img/partners-logos/docker.jpg)
![Node logo](http://lorenzostella.it/php/nodejs.png)
![Sf Logo](http://1.bp.blogspot.com/-ItoDJoqdeBs/Uk2WuZdk53I/AAAAAAAADw0/CeubII9wDVA/s1600/symfony_logo.png)

use this docker project if you want to launch a php or node project with Nginx.

## List of components

 * Nginx
 * PHP-FPM
 * Node with Gulp/Bower
 * Composer

## How it works

### Pre-requiste

You must have Docker installed and running on your machine before using this project

### Steps

 1. Create a **src** folder on this project root directory
 2. Pull/Put your code inside it
 3. Run dockers-compose

## Commands for the dockers

### Building all images
`docker-compose build --no-cache`

### Launching all dockers with deamon
`docker-compose up -d`

### Stop all dockers
`docker-compose stop`

### Removing all containers
`docker-compose rm -f`
