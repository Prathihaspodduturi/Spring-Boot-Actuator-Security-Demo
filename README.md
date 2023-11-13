# Spring-Boot-Actuator-Security-Demo

This project is a demonstration of Spring Boot's actuator and security features. It showcases how to expose and secure actuator endpoints, provides custom application information through actuator info endpoints, and offers a basic REST controller with various endpoints.

# Features
- REST API with fortune endpoints.
- Full expose of Spring Boot Actuator endpoints with custom application.
- Basic authentication for secure access to actuator information.

# Technologies Used
- Spring Boot 3.1.5
- Spring Security
- Java 17

# Getting Started

# Prerequisites
- Java Development Kit (JDK) 17
- Maven 3.3+
- IntelliJ IDEA

# Running the Application Locally
1. Clone the repository to the local machine.
2. Open the directory in the IntelliJ IDEA.
3. In the src directory, right click on MycoolappApplication file and select RUN 'MycoolappApplication'.

In the browser visit 'http://localhost:8080/' to access the endpoints. Access the actuator endpoints at 'http://localhost:8080/actuator'. You will be asked to enter username and password. 
The default username is 'user' and the password is generated on the terminal.

# Configuration
The 'application_properties; file is pre-configured to expose all actuator endpoints. You can modify this file to restrict or extend the exposed data by updating the line: management.endpoints.web.exposure.include=*

# Security
The application uses Spring Security to restrict access to the actuator endpoints. You will need to authenticate with a username and password to view the actuator information.
