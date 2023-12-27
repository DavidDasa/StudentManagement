# StudentManagement

This repository contains a basic Spring Boot REST application for managing students.

## Features

- CRUD operations for students
- Filtering, pagination, and sorting for fetching students
- One-to-many relationship between students and grades
- Image upload to AWS S3 and presigned URL generation
- Async SMS sending integration
- JWT authentication
- Exception handling 
- Swagger API documentation
- Docker deployable
- Tests with JUnit, Mockito, and h2 database
- CI/CD with Jenkins, Postman, and Newman

## Getting Started

1. Clone the repository
2. Configure application.properties
3. Build using Maven 
4. Run the application

The app will start on port 8080. Access the Swagger UI at http://localhost:8080/swagger-ui.html

### Prerequisites

Required:
- Java 8+
- Maven
- Docker

## Running the tests

Run `mvn test` to execute the JUnit tests with code coverage.

## Deployment

The app is dockerized and can be deployed using Docker Compose or to a Kubernetes cluster.

Configuration for production deployment is in docker-compose-aws.yml.

## Built With

- Spring Boot 2.5.2
- Maven
- PostgreSQL
- Hibernate
- Swagger
- AWS SDK
- JUnit

## Contributing

Contributions welcome! 

1. Fork the repository
2. Create your feature branch 
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License.
