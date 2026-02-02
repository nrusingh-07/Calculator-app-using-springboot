Spring Boot Calculator Application

Abstract
The Spring Boot Calculator Application is a simple web-based application developed using Java and the Spring Boot framework to perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The application follows the Model–View–Controller (MVC) architecture and uses Thymeleaf as the template engine to render dynamic content on HTML pages. The main objective of this project is to provide hands-on experience with Spring Boot fundamentals, including request mapping, dependency injection, service-layer design, and form handling. The application also includes basic error handling, such as preventing division by zero, making it a reliable and beginner-friendly learning project.

Project Overview
This project demonstrates how a Spring Boot web application processes user input through HTML forms, performs business logic using a service layer, and displays results dynamically using Thymeleaf templates. The application runs on an embedded Tomcat server and uses Maven for dependency management. It is designed primarily for academic and learning purposes and serves as a foundation for building more advanced Spring Boot applications.

Technologies Used
Java
Spring Boot
Spring MVC
Thymeleaf
HTML
CSS
Maven
Embedded Tomcat Server

Application Architecture
The application is built using the MVC (Model–View–Controller) architecture. The controller handles HTTP requests and responses, the service layer contains the core calculation logic, and the view layer consists of HTML pages rendered dynamically using Thymeleaf. This separation of concerns improves code clarity, maintainability, and scalability.

Project Structure
src/main/java
 └── com.example.app
     ├── controller
     │   └── CalciController.java
     └── service
         └── CalciService.java

src/main/resources
 ├── templates
 │   ├── index.html
 │   └── result.html
 └── application.properties

Functional Description

When the user opens the application, a calculator page is displayed where two numeric values can be entered. The user selects an arithmetic operation by clicking the corresponding button. The form data is submitted to the Spring Boot controller using a POST request. The controller receives the input values, calls the appropriate method from the service class, and processes the calculation. The result is then sent back to the view and displayed on the result page. If an invalid operation occurs, such as division by zero, the application displays a meaningful error message instead of crashing.

Screenshots
Calculator Home Page
<img width="1913" height="930" alt="image" src="https://github.com/user-attachments/assets/c67d1469-5e3c-456f-b857-c74211b468b7" />


Result Page
<img width="1917" height="934" alt="image" src="https://github.com/user-attachments/assets/df1bf919-a856-4862-8537-bb319c93f1ee" />


Note: Screenshots can be added here when submitting the project or uploading it to GitHub.

How to Run the Application
Download or clone the project repository
Open the project in Spring Tool Suite (STS), IntelliJ IDEA, or Eclipse
Ensure Maven dependencies are downloaded successfully
Run the main Spring Boot application class
Open a web browser and navigate to:
http://localhost:9090/api/

Error Handling
Division by zero is handled safely
Proper error messages are displayed on the UI
Invalid operations do not crash the application

Advantages
Simple and easy to understand
Beginner-friendly Spring Boot project
Clear MVC architecture
No external server configuration required

Ideal for academic submission and practice

Limitations
Supports only basic arithmetic operations
No database integration
Minimal user interface design
Future Enhancements

Add frontend validation

Improve UI using Bootstrap
Add calculation history
Convert application into REST API
Add unit testing and logging

Conclusion
The Spring Boot Calculator Application successfully demonstrates the fundamental concepts of Spring Boot web development, including MVC architecture, request handling, service-layer logic, and Thymeleaf integration. This project is well-suited for students and beginners who want to gain practical experience with Spring Boot and serves as a strong base for developing more complex web applications in the future.

Author
Nrusingh
Spring Boot Calculator Application
