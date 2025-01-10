# Quiz Service

The Quiz Service is a microservice application designed for managing quizzes. It integrates with the Question Service to fetch questions, create quizzes, and evaluate scores. The service uses Eureka Client for service discovery and OpenFeign for seamless inter-service communication.

---

## Features
- **Create Quiz**: Generate a quiz by fetching questions from the Question Service.
- **Get Quiz**: Retrieve quiz details, including questions, from the Question Service.
- **Submit Quiz**: Submit user responses and calculate the score by leveraging the Question Service.

---

## Tech Stack
- **Language**: Java
- **Frameworks**: Spring Boot, Spring Data JPA
- **Database**: PostgreSQL
- **Tools**: Postman (for testing APIs)
- **Dependencies**: 
  - **Lombok**: For reducing boilerplate code.
  - **Eureka Client**: For service registration with the Eureka Server.
  - **OpenFeign**: For inter-service communication with the Question Service.

---

## Prerequisites
- Java 17 or later
- PostgreSQL installed and running
- Eureka Server running
- Question Service running
- Postman or any API testing tool

---

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd quiz-service
