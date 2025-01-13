# Springboot Kafka Microservices Project

This project demonstrates a microservices architecture using Spring Boot and Apache Kafka for event-driven communication.

## Overview

The project consists of multiple microservices that communicate with each other using Kafka messages. This architecture provides loose coupling and scalability.

## Prerequisites

- Java 17 or higher
- Maven
- Docker
- Apache Kafka

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/springboot-kafka-microservices.git
```

2. Build the project:
```bash
mvn clean install
```

3. Start Kafka using Docker:
```bash
docker-compose up -d
```

## Project Structure

- `service1` - Description of service 1
- `service2` - Description of service 2
- `common` - Shared libraries and utilities

## Configuration

Each service has its own configuration in `application.properties` or `application.yml`.

## License

This project is licensed under the MIT License - see the LICENSE file for details.