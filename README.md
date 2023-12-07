##
# GRADE Portal: Spring Security

 A comprehensive Spring Boot application designed to manage and expose RESTful APIs for various entities, including User, Grade, Course, and Student. In addition to the core functionalities, I have implemented robust Spring Security for token-based authentication to ensure a secure and seamless user experience

 # Project Overview:
 This  Spring Boot project serves as a centralized platform for managing and interacting with critical entities within our system. The main entities include:
    Grade: Represents academic grading information.
    Course: Contains details about the courses offered.
    Student: Holds information about individual students.
    User: Registered Users.

## Concepts Implemented:
1. Three Layer Codebase.
2. Object Relational Mapper.
3. One to Many Relationships
4. Many to Many Relationships.
5. Basic Auth with Spring Security.
6. Token-Based-Authentication.

## What's inside 
This project is based on the [Spring Boot](http://projects.spring.io/spring-boot/) project and uses these packages :
- Maven
- Spring Core
- Spring MVC
- Spring Data JPA (SQL Database)
- Spring Security (JWT)

## Getting Started

The project is created with Maven, so you just need to import it to your IDE and build the project to resolve the dependencies.
First Run the server:
```
./mvnw clean spring-boot: run
```

Open the Postman tool and Test all the end-points using appropriate URLs, authentication tokens, and payload wherever necessary.


