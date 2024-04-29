# Secure Web Application with Spring Boot

This repository contains a simple demonstration of a secure web application built with Spring Boot. It utilizes Spring Security to handle authentication and authorization.

## Features

- **Login Page**: Provides a login form for users to authenticate themselves.
- **Home Page**: Upon successful login, users are redirected to the home page.
- **Hello Page**: Accessible after authentication, displays a greeting.
- **Security Configuration**: Configures security rules using `WebSecurityConfig` and `MvcConfig` classes.
- **Thymeleaf Templates**: Uses Thymeleaf for server-side rendering of HTML templates.

## Technologies Used

- **Spring Boot**: For rapid application development.
- **Spring Security**: Provides authentication, authorization, and other security features.
- **Thymeleaf**: Server-side Java template engine for web and standalone environments.
- **Maven**: Build automation tool and dependency management.
- **Java 17**: Programming language for the backend.

## Prerequisites

- Java 17
- Maven

## Setup and Usage

1. Clone this repository.
2. Navigate to the project directory.
3. Build the project using Maven: `mvn clean package`.
4. Run the application: `mvn spring-boot:run`.
5. Access the application in your web browser at `http://localhost:8080`.

## Project Structure

- `src/main/java/com/WebApplication/secureWebApplication/securingweb`: Contains Java source files.
  - `MvcConfig.java`: Configures Spring MVC.
  - `WebSecurityConfig.java`: Configures Spring Security.
- `src/main/resources`: Contains static resources and Thymeleaf templates.
- `pom.xml`: Maven project configuration file.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
