# CI/CD Pipeline for a Gaming Application

This project demonstrates an end-to-end **CI/CD pipeline** for a gaming application using DevOps tools like **Jenkins**, **Docker**, **Maven**, **SonarQube**, and **Trivy**. It automates the entire process from code integration to security scanning and container deployment.

## Tools & Technologies

- **GitHub** – Source code management
- **Jenkins** – Pipeline orchestration
- **Maven** – Java project build tool
- **Docker** – Containerization
- **SonarQube** – Static code analysis
- **Trivy** – Vulnerability scanning
- **Linux** – Build server environment

## CI/CD Pipeline Flow

1. **Code Checkout** from GitHub
2. **Build** the project using Maven
3. **Code Analysis** using SonarQube
4. **Security Scan** using Trivy:
   - Filesystem scan
   - Docker image scan
5. **Dockerize** the application
6. **Push Image** to DockerHub / local registry
7. (Optional) **Deploy** to staging server or Kubernetes

## Features

- Fully automated CI/CD process
- Built-in code quality and security checks
- Lightweight and reproducible Docker containers
- Scalable approach for microservices-based applications

## Outcomes

- Gained experience with Jenkins freestyle & pipeline jobs
- Integrated SonarQube and Trivy into a secure DevOps workflow
- Understood secure containerization practices

## Future Enhancements

- Deploy using **Kubernetes** or **AWS ECS**
- Add **Slack notifications** for each pipeline stage
- Use **Jenkinsfile** for fully scripted pipeline (Infrastructure as Code)


