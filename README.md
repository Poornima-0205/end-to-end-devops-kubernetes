# End-to-End DevOps CI/CD Pipeline with Kubernetes

## Project Overview
This project demonstrates an end-to-end CI/CD pipeline using AWS, Jenkins, GitHub, Maven, Docker, and Kubernetes.

The pipeline automates the application build, Docker image creation, image publishing, and Kubernetes deployment.

## Technologies Used
- AWS EC2
- Jenkins
- Git and GitHub
- Maven
- Docker
- Kubernetes
- Java

## Project Workflow
1. Source code is maintained in GitHub.
2. Jenkins fetches the source code.
3. Maven builds the application.
4. Docker builds the application image.
5. Docker image is pushed to Docker Hub.
6. Jenkins deploys the application to Kubernetes.

## Project Structure
- `src/` – Application source code
- `Dockerfile` – Docker image configuration
- `Jenkinsfile` – CI/CD pipeline stages
- `pom.xml` – Maven configuration
- `k8s/` – Kubernetes configuration files (if included)

## Learning Outcomes
- Understanding CI/CD pipeline implementation.
- Application build using Maven.
- Docker image creation and management.
- Automating deployment using Jenkins.
- Understanding Kubernetes deployment.



