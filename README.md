# IIEC_DOCKER_PROJECT
# INTRODUCTION
Under IIEC-RISE 1.0 Campaign, I Iearnt about DOCKER TECHNOLOGY under guidance of Vimal Daga Sir.This is my final project using docker to Configure Wordpress , Drupal , and Owncloud  using MariaDB database.
# DESCRIPTION
The project is composed by using ".yml or .yaml" file. It uses PAT(Port Address Translation) for outside accessibility(LAN network) and usage of volume for permanent storage of data that includes login details etc. 
	It requires Docker images for setup i.e. "owncloud" ,"drupal" and "wordpress" and "MariaDB" database for storage of data.The infrastructure created can be launched using "docker-compose up" or "docker-compose up -d".
	Owncloud is a self-hosted open source file sync and share server like Dropbox ,Googledrive , Box and others.Owncloud let,s you access your files , contacts , calender and other data.
	Wordpress plugin architecture allows users to extend the features and fuctionality of a website or a blog.
	Drupal is a free and open-source web content management framework written in PHP .With drupal we can have site admins , content editors , individualized access to private content and more.
# versions used- 
- owncloud:10.0-apache
- MariaDB:10.5
- Wordpress:5.1.1-php7.3-apache
- Drupal:latest
- Docker-compose:3
