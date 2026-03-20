# RestApi

# Spring Boot REST API (Hello World)
📌 Overview

This is a simple Spring Boot project that demonstrates how to create a basic REST API.
It includes a single API endpoint that returns a "Hello World" response.

🛠️ Technologies Used

Java
Spring Boot
Maven
IntelliJ IDEA

📁 Project Structure
src/
 └── main/
      ├── java/
      │    └── com.example.restapidemo/
      │         ├── RestApiDemoApplication.java
      │         └── controller/
      │              └── HelloController.java
      └── resources/
           └── application.properties

▶️ How to Run
Open project in IntelliJ IDEA
Run RestApiDemoApplication.java
Wait for:
Tomcat started on port 8080

🌐 API Endpoint
GET Request
http://localhost:8080/hello
Response
Hello World 🚀

📌 Controller Code
@RestController
public class HelloController {

    @GetMapping("/hello")
    public String sayHello() {
        return "Hello World 🚀";
    }
}

----------------------------------------------------------------------------------------------------------------

# Spring Boot Journal App
📌 Overview

This is a Spring Boot backend project for a Journal Application.
It allows users to create, manage, and store journal entries.

🛠️ Technologies Used
Java
Spring Boot
Maven
IntelliJ IDEA

▶️ How to Run
Open project in IntelliJ IDEA
Run main application file
Wait until server starts

⚙️ Features
Create journal entry
View all entries
Update entry
Delete entry

🌐 API (Example)
Method	       Endpoint	         Description
GET            /entries          Get all entries
POST	         /entries	         Create new entry
PUT            /entries/{id}	   Update entry
DELETE	       /entries/{id}	   Delete entry
