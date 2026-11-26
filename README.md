# End-to-End DevOps Pipeline Using Kubernetes

## Project Overview

This project focuses on building and deploying a Spring Boot application using DevOps tools.

I used GitHub for source code management, Jenkins to automate the CI/CD pipeline, Maven to build the application, and Docker to create the container image.

The application was successfully deployed on a Kubernetes cluster hosted on AWS EC2 instances.

## Technologies Used

- AWS EC2
- Git & GitHub
- Jenkins
- Maven
- Spring Boot
- Docker
- Docker Hub
- Kubernetes

## Project Workflow

1. Developed the Spring Boot application.
2. Pushed the application source code to GitHub.
3. Integrated GitHub with Jenkins.
4. Used Maven to build the application.
5. Created a Docker image using the Dockerfile.
6. Pushed the Docker image to Docker Hub.
7. Deployed the application on a Kubernetes cluster running on AWS EC2.
8. Verified the application deployment.

## Jenkins Pipeline Stages

The Jenkins pipeline includes the following stages:

- **Checkout:** Retrieves the source code from GitHub.
- **Build:** Builds the application using Maven.
- **Docker Build:** Creates the Docker image.
- **Docker Push:** Pushes the image to Docker Hub.
- **Kubernetes Deploy:** Updates the Kubernetes deployment and checks its rollout status.

## Project Structure

```text
end-to-end-devops-kubernetes/
│
├── src/
│   └── main/
│       └── java/
│           └── com/devops/app/
│
├── Dockerfile
├── Jenkinsfile
├── pom.xml
└── README.md
```

## What I Learned

- Managing source code using Git and GitHub.
- Creating CI/CD pipelines using Jenkins.
- Building Java applications using Maven.
- Creating and managing Docker images.
- Deploying applications using Kubernetes.
- Working with AWS EC2 instances.

## Project Outcome

Successfully implemented an end-to-end CI/CD pipeline and deployed a Spring Boot application using Jenkins, Docker and Kubernetes on AWS EC2.

This project helped me gain practical experience in CI/CD automation, containerization and application deployment.
