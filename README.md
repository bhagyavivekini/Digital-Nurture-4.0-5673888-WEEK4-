# Digital Nurture 4.0 – Java FSE Week 4 Assignments

This repository contains my Week 4 Hands-on Assignments for Cognizant's Digital Nurture 4.0 – Java Full Stack Engineer (FSE) program, focusing on Spring Core fundamentals and implementing RESTful Web Services.

## Repository Content

This repository primarily contains the Spring Boot project demonstrating the completed hands-on tasks for Week 4.

## Task Summaries

### 1. Spring Core Foundations & XML Configuration

* **Hands on 1: Create a Spring Web Project using Maven**
    * **Description:** Setup of a fundamental Spring Boot project using Spring Initializr and Maven for dependency management. Initializes the core application structure.
    * **Files:** `pom.xml`, `SpringLearnApplication.java`, `application.properties`
    * **Output:** output demonstrating successful application startup and initial logs.

* **Hands on 4: Spring Core – Load Country from Spring Configuration XML**
    * **Description:** Demonstrates loading a single `Country` bean (with `code` and `name` properties) from an XML configuration file using Spring's IoC container. Includes debug logging for constructor and setters.
    * **Files:** `country.xml`, `Country.java` (model), `SpringLearnApplication.java` (updated to load bean)
    * **Output:** output showing `Country` bean creation and property injection logs.

### 2. RESTful Web Services Implementation

This section focuses on building and exposing RESTful API endpoints using Spring Web.

* **Hello World RESTful Web Service**
    * **Description:** Implementation of a basic REST endpoint that responds with a "Hello World!" message. This serves as a foundational example for REST controllers.
    * **Files:** `HelloController.java`
    * **Output:** Browser/Postman response: `"Hello World!"` when accessing `/hello`.

* **REST - Country Web Service**
    * **Description:** Creation of a REST endpoint (`/country`) that returns a hardcoded `Country` object (e.g., India) in JSON format.
    * **Files:** `CountryController.java` (with `/country` GET method)
    * **Output:** Browser/Postman response: `{"code":"IN","name":"India"}` when accessing `/country`.

* **REST - Get country based on country code**
    * **Description:** Development of a dynamic REST endpoint (`/country/{code}`) that retrieves a specific `Country` object from the loaded list based on the provided country code in the URL path.
    * **Files:** `CountryController.java` (with `/country/{code}` GET method, using `CountryService`)
    * **Output:** Browser/Postman response: `{"code":"US","name":"United States"}` when accessing `/country/us`, `{"code":"IN","name":"India"}` when accessing `/country/in`.

## Tech Used

* Java 8 (JDK)
* Spring Framework 5.x (Spring Core, Spring Web)
* Spring Boot 2.7.x
* Maven
* SLF4J + Logback (for logging)
* Git & GitHub
* Microsoft Word (for submission document)
* Windows OS

## About Me
**DUGGIRALA BHAGYA VIVEKINI**
Java Full Stack Engineer (FSE) Trainee @ Cognizant DN-4.0
Email: [2200040307ece@gmail.com]
Passionate about backend development, Java logic building, and real-world software engineering practices. Thank you Cognizant & team for this valuable opportunity!
