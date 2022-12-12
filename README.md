# Containerizing Java application with Apache tomcat, Nginx and Mysql server

## Setps   

- 1. Fetch source code from git repository
- 2. Create Dockerfiles for nginx, tomcat and mysql server and build images
- 3. Create the docker-compose file to build and test the services
- 4. Push the docker images onto dockerhub if everything is ok

## Prerequisites

- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later

## Technologies 

- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL 

## Database

* Here,we used Mysql DB 
    * /src/main/resources/accountsdb
    * accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
    * `mysql -u <user_name> -p accounts < accountsdb.sql`  

    


