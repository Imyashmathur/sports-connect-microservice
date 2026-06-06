# 🚀 Sports Connect Microservices Platform

A cloud-native microservices application built using Spring Boot and Spring Cloud ecosystem.

## Architecture

The platform consists of:

- API Gateway
- Eureka Service Registry
- Config Server
- User Service
- Event Service
- Message Service
- RabbitMQ
- Keycloak Authentication
- Grafana Monitoring
- Prometheus Metrics
- Loki Logging
- Tempo Distributed Tracing

## Features

- Service Discovery using Eureka
- Centralized Configuration Management
- API Gateway Routing
- OAuth2 Authentication with Keycloak
- Event Driven Communication using RabbitMQ
- Fault Tolerance using Resilience4j
- Distributed Tracing and Monitoring
- Containerized Deployment using Docker

## Tech Stack

- Java 17
- Spring Boot
- Spring Cloud
- Spring Security
- Keycloak
- RabbitMQ
- Docker
- Grafana
- Prometheus
- Loki
- Tempo

## Running the Project

```bash
docker-compose up -d
```

Start services in order:

1. Config Server
2. Eureka Server
3. API Gateway
4. User Service
5. Event Service
6. Message Service

## Learning Objectives

This project demonstrates production-style microservice architecture including:

- Service Discovery
- API Gateway Pattern
- Event Driven Architecture
- Distributed Monitoring
- Security and Authentication
- Fault Tolerance
