#Worknest

A full-scale, enterprise-grade Human Resource Management System (HRMS) built using Java, Spring Boot, and Microservices architecture. This project is designed to showcase real-world implementation of distributed services, secure communication, and cloud-native patterns suitable for production-grade deployments.

---

## Project Description

This HRMS application follows a modular microservices architecture to support modern enterprise needs such as organization structure, employee records, leave management, and secure authentication. Each service operates independently and communicates via REST APIs, making the system scalable and resilient.

This project is a culmination of over a decade of professional experience in architecting and developing Java-based systems across various domains.

---

## Architecture Overview

### Functional Microservices
- **Organization Service** – Manages company and department structures.
- **Employee Service** – Handles employee registration, profiles, and CRUD operations.
- **Leave Service** – Manages leave requests, approvals, and history.
- **Auth Service** – JWT-based login and role-based access control.

### Infrastructure Services
- **Config Server** – Centralized configuration across services.
- **Eureka Server** – Service discovery and registration.
- **API Gateway** – Unified entry point with routing, load balancing, and security.

---

## Tech Stack

- **Language**: Java 17
- **Framework**: Spring Boot, Spring Cloud, Spring Security
- **Auth**: JWT (JSON Web Token)
- **Database**: PostgreSQL
- **Service Discovery**: Eureka
- **Config Management**: Spring Cloud Config
- **Messaging**: (Optional Kafka support in future)
- **Containerization**: Docker, Docker Compose
- **API Docs**: Swagger / OpenAPI

---

## Prerequisites

- Java 17+
- Maven
- Docker & Docker Compose

---

##  Getting Started

### Clone the Repository
```bash
git clone https://github.com/your-username/hrms-spring-boot-microservices-implementation.git
cd hrms-spring-boot-microservices-implementation
