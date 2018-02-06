A docker-compose lamp config
===
Quickly get a LAMP stack up and running through docker-compose

Usage
==
1) git clone https://github.com/TomCan/docker-compose-lamp.git *myproject*
2) cd *myproject*
3) docker-compose up -d
4) browse to https://localhost. It will serve the content from the htdocs/web folder

Customization
==
Apache config: see apache2/conf/httpd.conf  
Adding Php libraries: see Dockerfile-php