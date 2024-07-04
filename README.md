# Project Title

This project is built using Spring Boot, Thymeleaf, and Docker. It provides a minimal web application structure that you can modify and build upon.

## Technologies Used

- **Spring Boot**: A framework for building production-ready applications in Java.
- **Thymeleaf**: A modern server-side Java template engine for web and standalone environments.
- **Docker**: A platform for developing, shipping, and running applications inside containers.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- Java Development Kit (JDK) 11 or higher
- Docker
- Maven

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/your-repo/project-name.git
cd project-name
```

### Build the Project

Use Maven to build the project:

```bash
mvn clean install
```

### Run the Application

You can run the application using Maven:

```bash
mvn spring-boot:run
```

Alternatively, you can build a Docker image and run it inside a container:

```bash
# Build the Docker image
docker build -t project-name .

# Run the Docker container
docker run -p 8080:8080 project-name
```

### Access the Application

Once the application is running, you can access it at `http://localhost:8080`.

## Project Structure

```plaintext
src/
├── main/
│   ├── java/
│   │   └── com/
│   │       └── example/
│   │           └── demo/
│   │               ├── DemoApplication.java
│   │               └── controller/
│   │                   └── HomeController.java
│   ├── resources/
│   │   └── templates/
│   │       └── index.html
│   └── docker/
│       └── Dockerfile
└── test/
    └── java/
        └── com/
            └── example/
                └── demo/
                    └── DemoApplicationTests.java
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.