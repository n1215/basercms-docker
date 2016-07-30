baserCMS docker-compose
==========================

### Requirements
* git
* docker
* docker-machine
* docker-compose

### Containers 
* web: nginx1.11
* data: data volume
* app: php-fpm (php5.6)
* db: mysql5.6

### Get Started
    git clone https://github.com/n1215/basercms-docker
    cd basercms-docker
    sh ./init.sh  #clone baserproject/basercms repository
    docker-compose up -d

### License
MIT
 
