# DevOps CI/CD Pipeline Project

## Project Overview
This project demonstrates a complete CI/CD pipeline using Jenkins, Maven, SonarQube, Nexus, Docker, AWS ECR, and EC2.

The pipeline automatically builds, tests, analyzes, packages, and deploys the application.

---

## Tools & Technologies Used

- GitHub
- Jenkins
- Maven
- SonarQube
- Nexus Repository
- Docker
- AWS ECR
- AWS EC2
- Java Application

---

## CI/CD Pipeline Flow

1. Developer pushes code to GitHub
2. Jenkins triggers the pipeline
3. Maven builds the project
4. Unit tests are executed
5. SonarQube performs code quality analysis
6. Artifact (WAR/JAR) is uploaded to Nexus
7. Docker image is created
8. Image is pushed to AWS ECR
9. Container is deployed on EC2

