# jenkins-docker-amazon-ecr-cicd-pipeline
This project demonstrates how to extend a Continuous Integration (CI) pipeline into a complete Continuous Integration and Continuous Delivery (CI/CD) workflow using Jenkins, Docker, and Amazon Elastic Container Registry (Amazon ECR).

The pipeline automatically builds, tests, analyzes code quality, creates Docker images, and publishes container images to Amazon ECR whenever code is pushed to GitHub.

This project demonstrates modern DevOps practices including automation, containerization, secure credential management, and cloud-native software delivery.

## Technologies Used
| Technology | Purpose              |
| ---------- | -------------------- |
| GitHub     | Source Code          |
| Jenkins    | CI/CD Automation     |
| Maven      | Build Tool           |
| Java       | Application          |
| Checkstyle | Static Code Analysis |
| SonarQube  | Code Quality         |
| Docker     | Containerization     |
| Amazon ECR | Container Registry   |
| AWS CLI    | AWS Authentication   |
| IAM        | Secure Access        |
| Linux      | Jenkins Server       |

## Project Objectives
• Automate software builds

• Perform unit testing
• Execute static code analysis
• Enforce Quality Gates
• Build Docker images automatically
• Push Docker images to Amazon ECR
• Secure AWS authentication using IAM
• Demonstrate CI/CD automation using Jenkins

## Pipeline Workflow
Developer

↓

Pushes code to GitHub

↓

GitHub Webhook triggers Jenkins

↓

Jenkins pulls latest source code

↓

Build application using Maven

↓

Run Unit Tests

↓

Run Checkstyle

↓

Run SonarQube Analysis

↓

Validate Sonar Quality Gate

↓

Build Docker Image

↓

Authenticate to AWS

↓

Push Docker Image to Amazon ECR

↓

Remove Local Docker Image

## Jenkins Pipeline Stages
Docker

Docker Pipeline

Amazon ECR

AWS SDK

CloudBees Docker Build & Publish

SonarQube Scanner

Pipeline

Git

Maven Integration
## AWS Services Used
Amazon ECR

IAM

EC2

AWS CLI

## Jenkins Plugins
Docker

Docker Pipeline

Amazon ECR

AWS SDK

CloudBees Docker Build & Publish

SonarQube Scanner

Pipeline

Git

Maven Integration

## Key Skills Demonstrated
CI/CD

Continuous Integration

Continuous Delivery

Docker

Containerization

Jenkins

AWS

Amazon ECR

IAM

GitHub

Maven

Linux

SonarQube

Automation

Cloud Computing

DevOps

## Future Improvements
Deploy Docker images to Amazon ECS

Deploy to Amazon EKS

Automate Infrastructure using Terraform

Implement GitHub Actions

Implement GitLab CI/CD

Deploy using ArgoCD

Implement Kubernetes

Implement Monitoring using Prometheus & Grafana

## Author
Nokuthula Patience Zulu

Cloud & DevOps Engineer in Development

GitHub:
https://github.com/Nok2lapatience

LinkedIn:
https://linkedin.com/in/Nokuthula-zulu-762a4157
