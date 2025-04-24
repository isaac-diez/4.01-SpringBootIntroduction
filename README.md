# 4.01-SpringBootIntroduction Level 1

This Spring Boot application is configured to run on port 9000 by setting the following in the application.properties file:

server.port=9000

The application exposes a simple REST API with a controller class named HelloWorldController, located in the controller subpackage.
📌 Endpoints

The controller contains two GET methods that receive a String parameter called name and return the message:

    "Hello, {name}. You are running a Maven project."

1️⃣ GET /HelloWorld

- Accepts name as a RequestParam
- Default value: "UNKNOWN"
- Example requests:
  - http://localhost:9000/HelloWorld
  - http://localhost:9000/HelloWorld?name=YourName

2️⃣ GET /HelloWorld2/{name}

- Accepts name as a PathVariable
- The parameter is optional
- Example requests:
  - http://localhost:9000/HelloWorld2
  - http://localhost:9000/HelloWorld2/YourName




💻Stack used: Project created with:

    Java v.21.
    Maven v.3.9.9.
    IDE IntelliJ Idea v. 24.3.1.1

📋Requirements: No specific requirement but the Java and Maven version or newer.

🛠️Installation:

    Clone this repo: -> git clone

▶️Execution: No specific instruction.

🌐Deployment: N/A.

🤝Contributions:

Contributions are welcome! Please follow the following steps to contribute:

    Fork the repository.
    Create a new: git checkout branch -b feature/News.
    Make your changes and commit them: git commit - 'Add New Functionality'.
    Upload the changes to your branch: git push feature/News.
    Do a pull request.
