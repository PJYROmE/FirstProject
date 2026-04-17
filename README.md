First Project Java Spring
A simple Spring Boot web application demonstrating MVC architecture with Thymeleaf templating.
Technologies Used

Java 17
Spring Boot 3.x
Spring Web (MVC)
Thymeleaf
Lombok
Maven

Project Setup
The project was generated using Spring Initializr with the following configuration:

Project: Maven
Language: Java
Packaging: JAR
Dependencies: Spring Web, Lombok, Thymeleaf

How to Run

Clone the repository
Open the project in IntelliJ IDEA
Right-click the project → Maven → Reload Project
Run FirstProjectJavaSpringApplication.java
The app starts on http://localhost:8080
src/
└── main/
    ├── java/
    │   └── pl/edu/vistula/firstprojectjavaspring/
    │       ├── controller/
    │       │   └── HelloController.java
    │       └── FirstProjectJavaSpringApplication.java
    └── resources/
        ├── templates/
        │   └── greeting.html
        └── static/
            └── images/
                └── vistula.png
                
