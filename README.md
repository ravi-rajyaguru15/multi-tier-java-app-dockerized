# Multi-Tier Java App (Dockerized)

This project demonstrates a clean, containerized multi-tier Java web application using Docker Compose.

## Stack
- Java Web App (Tomcat)
- MySQL 8.0.33
- Memcached 1.6
- RabbitMQ 4.0
- Nginx 1.27

## Structure
- `web-app`: Built from source using Maven
- `mysql-db`: Official MySQL with init script
- `nginx-proxy`: Handles HTTP routing to app

## Coming Soon
- CI/CD pipeline
- Kubernetes orchestration
- Monitoring
