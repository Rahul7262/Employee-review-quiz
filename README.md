![Screenshot 2023-01-27 155614](https://user-images.githubusercontent.com/95207023/215069095-d7be359e-a59b-4a12-bcd7-d44361a0bfe9.png)
![Screenshot 2023-01-27 162015](https://user-images.githubusercontent.com/95207023/215069136-64b94065-e830-4800-8d9b-010619844841.png)
# Employee-review-quiz
Basic MVC type review app using Spring Boot
MCQ based quiz application using Spring Boot, Spring Data JPA, MySQL, react and Bootstrap.
This project was made as a part of my Spring Boot project .
A Performance submission application that Employees and Admin can use to submit/review each other's performance feedback.
This is a Complete MVC Architecture Spring Boot RESTful Application with CRUD APIs for Admin and Employee Controller and Service Classes and Entities.
#REST API Tests
In order to test the REST API, there are E2E tests under POSTMAN. At the moment, there is a single Life Cycle test. The idea of this test is to bring up an app from scratch, with an empty DB and cover a range of scenarios a user is likely to go through. In order to make it more realistic, the test is only allowed to interact with the database via the REST API and shoudln't load any mock data into the database directly. The test has grown quite long and needs refactoring. Other smaller tests would also be desirable.

# Tehcnologies Used
# Backend
# Java
Java 8 - Main Backend Language
Maven - Dependency Management
The Spring Family
Spring Boot - The Framework of Frameworks
Spring MVC - The Web framework
Spring Security - Security, Authentication, Authorization
# Databases
MySQL - The default RDBMS.
H2 - Simple RDBMS to use for testing purposes.
Hibernate - ORM
# Testing
JUnit - The main Testing Framework.
Mockito - Mocking framework for Unit Tests.
Hamcrest - Matcher framework for automated tests.
MockMvc - Test entry point for Spring MVC controllers.
GreenMail - Stub SMTP Server to validate email functionality.
EclEmma - Test Coverage tool for Java.
FindBugs - Static Analysis tool for Java.
# Frontend
HTML/CSS/JS - Just HTML/CSS/JS.
Bootstrap - Design Framework.
ReactJS - Frontend framework.
