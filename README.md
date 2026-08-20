# Eureka Discovery Server 🔍

Service registry mapping for the WorkForceHub microservices ecosystem.

## 🛠️ Tech Stack
- **Java**: 25
- **Spring Boot**: 4.1.0
- **Netflix Eureka**

## ✨ Architecture Highlights
- Microservices automatically register themselves with this server upon startup.
- Allows the API Gateway and inter-service communication (via `@LoadBalanced RestTemplate`) to dynamically discover services by ID rather than hardcoded IP addresses.

## 🚀 Running Locally
- Port: `8761`
- Start this immediately after the Config Server.
