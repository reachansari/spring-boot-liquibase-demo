# spring-boot-liquibase-demo

A simple spring boot application which illustrates how to use Liquibase for your database changes. 
This application uses H2 as in-memory database for demonstration.

Springboot manages the execution of the liquibase updates at startup automatically via spring config prop in application.properties.

## Libraries used
- Spring Boot
- Spring Configuration
- H2
- Development Tools

## Compilation Command
- `mvn clean install` - Plain maven clean and install


## In this example I have 3 tables and one intersection table.
![Alt text](src/main/resources/images/db-design.png?raw=true "Title")

## How to connect H2 instances
<img src="src/main/resources/images/h2-connect.png?raw=true">

## How to verify
<img src="src/main/resources/images/h2-query.png?raw=true">