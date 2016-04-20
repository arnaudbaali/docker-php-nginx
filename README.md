Docker Nginx PHP Node
=====================

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

 1. Create a src folder on this root directory
 2. Pull your code inside it
 3. Launch dockers

## Commands for the dockers

### Building all images
`docker-compose build --no-cache`

### Launching all dockers with deamon
`docker-compose up -d`

### Stop all dockers
`docker-compose stop`

### Removing all containers
`docker-compose rm -f`
