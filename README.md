# Linux-Server
Udacity Project for Linux server

## Overview
This is the project for configuring a Linux Server.

The application can be accessed at http://18.216.84.189/catalog/

### The software installed for this application are - 
	*Apache2
	*Flask
	*SQL Alchemy
	*PostgreSQL
	*libapache2-mod-wsgi
	*Git
	

### Configurations made - 
Disabled remote login as root.
Disabled password logins.
Created user 'grader' with sudo access and generated ssh authentication.
Configured firewall to only accept ports 80,123 and 2200(ssh port).
Modified /etc/apache2/sites-enabled/000-default.conf to use the application.wsgi file to run the application.
Installed PostgreSQL, created user 'catalog' with limited access. 
Created database 'Catalog' and set up the tables using database_setup.py.


This application was created using the python Flask framework, PostgreSQL database and Google Oauth2 authentication.



