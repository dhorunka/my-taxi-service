# 🚕taxi-service🚕

## Features :rocket:

*- login/logout*

*- create/update/delete car, driver, manufacturer*

*- display list of cars/manufacturers/drivers*

## Project structure :clipboard:
**This project has N-tier architecture**

*- DAO - all work with database is here*

*- Service - all business logic is here*

*- Controller - accept requests and sends responses to clients*

## Technologies :bulb:

*- Java 11*

*- Maven*

*- TomCat*

*- MYSQL*

*- JSP*

## How to run this project 🔑
*- Fork this repo*

*- Copy link of project and create new project from VCS*

*- Edit ConnectionUtil class:*

```
private static final String URL = "URL";
private static final String USERNAME = "USERNAME";
private static final String PASSWORD = "PASSWORD";
private static final String JDBC_DRIVER = "com.mysql.cj.jdbc.Driver";

```
*- Run in your database this file - init_db.sql*

*- Install TomCat - https://tomcat.apache.org/download-90.cgi*

*- Configure TomCat in your IDE and run project*
