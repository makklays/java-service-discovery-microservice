# Java Service Discovery Microservice

<p align="left">
    <img src="./src/main/resources/static/images/schema-service-discovery-microservice.png" />
</p>
<p align="left">
    <img src="./src/main/resources/static/images/banco4.jpg" width="170" />
    <img src="./src/main/resources/static/images/banco1.jpg" width="170" />
    <img src="./src/main/resources/static/images/banco3.jpg" width="170" />
    <img src="./src/main/resources/static/images/cards.jpg" width="170" />
</p>

### Overview 

This Java microservice is designed to facilitate service discovery within a distributed system architecture. 
It leverages Spring Boot and Netflix Eureka to enable dynamic registration and discovery of services, allowing for 
seamless communication between different components of the application.

### Features

- **Service Registration**: Services can register themselves with the discovery server upon startup.
- **Service Discovery**: Clients can discover available services and their instances dynamically.
- **Load Balancing**: Integrates with Ribbon for client-side load balancing.
- **Health Checks**: Monitors the health of registered services to ensure reliability.
- **Scalability**: Easily scales to accommodate growing numbers of services and instances.
- **Resilience**: Supports fault tolerance and failover mechanisms.
- **Easy Integration**: Compatible with other Spring Cloud components for building robust microservices.
- **Dashboard**: Provides a web-based dashboard to visualize registered services and their statuses.
- **Configuration Management**: Supports externalized configuration for flexible deployment.
- **Security**: Implements security features to protect service registration and discovery processes.
- **Documentation**: Comprehensive documentation for easy setup and usage.

### Technologies Used
- Java
- Spring Boot
- Netflix Eureka
- Spring Cloud
- Maven
- Docker
- JUnit
- Git
- RESTful APIs
- Spring Security
- Actuator

### Getting Started
#### Prerequisites
- Java Development Kit (JDK) 11 or higher
- Maven 4.0 or higher
- Docker (optional, for containerization)
- Git
- IDE (e.g., IntelliJ IDEA, Eclipse)
- cURL or Postman for API testing