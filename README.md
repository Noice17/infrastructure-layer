# About

The **Infrastructure Layer** is used to support microservice-based projects.
This repository contains the core infrastructure components required to build and run a distributed microservice architecture. It acts as the **foundation layer** for service discovery, centralized configuration, and request routing.
The goal of this project is to serve as a **driver repository** for building and experimenting with **Spring Boot microservice architectures**.

---
## Purpose of This Repository

This repository exists to:

- Serve as the **core infrastructure for microservice projects**
- Provide **reusable infrastructure components**
- Act as a **learning and experimentation environment for microservice architecture**
- Support other services such as the **User Management System**
---

## Architecture Overview

This infrastructure layer provides the core services that microservices depend on:

- **Service Discovery**
- **Centralized Configuration**
- **API Routing (Gateway)**

---

## Components

### Service Registry (Eureka)

Handles **service discovery** between microservices.

Responsibilities:
- Registers running services
- Enables service-to-service communication
- Allows dynamic scaling of services

Technology:
- Spring Cloud Netflix Eureka

---

### Config Server

Provides **centralized configuration management** for all microservices.

Responsibilities:
- Centralized configuration repository
- Environment-based configuration
- Dynamic configuration updates

Technology:
- Spring Cloud Config Server

---

### API Gateway

Will serve as the **entry point for all client requests**.

Responsibilities:
- Request routing
- Authentication integration
- Logging and monitoring
- Security enforcement

Technology:
- Spring Cloud Gateway

---

## Tech Stack

- Java
- Spring Boot
- Spring Cloud
- Netflix Eureka
- Spring Cloud Config

---
