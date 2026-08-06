# 🚀 Serverless Container Deployment on AWS

Deploying a containerized web application on AWS using **Docker**, **Amazon ECR**, **Amazon ECS**, and **AWS Fargate**.

This project demonstrates how to build a Docker image, store it securely in Amazon Elastic Container Registry (ECR), and deploy it on Amazon ECS using AWS Fargate—allowing the application to run **without managing any servers**.

---

# 📖 Project Overview

In this project, I containerized my portfolio website using Docker, tested it on an Amazon EC2 instance, and pushed the Docker image to Amazon Elastic Container Registry (ECR). The image was then deployed using Amazon ECS with AWS Fargate.

AWS Fargate removes the need to provision or manage EC2 instances for the final deployment, making the application a **serverless container deployment**.

---

# 🏗️ Architecture

```text
            Portfolio Website
                   │
                   ▼
              Dockerfile
                   │
                   ▼
             Docker Image
                   │
                   ▼
            Amazon ECR
                   │
                   ▼
          Amazon ECS Cluster
                   │
                   ▼
            AWS Fargate
                   │
                   ▼
        Public IP / Web Browser
```

---

# 🛠️ AWS Services Used

- Amazon EC2
- Amazon ECR
- Amazon ECS
- AWS Fargate
- IAM
- VPC
- Security Groups
- AWS CLI

---

# 💻 Technologies Used

- Docker
- Apache HTTP Server
- Amazon Linux 2023
- HTML
- AWS CLI

---

# ✨ Features

- Containerized portfolio website
- Docker image creation
- Image storage in Amazon ECR
- ECS Task Definition deployment
- Serverless deployment with AWS Fargate
- Publicly accessible web application
- Secure IAM authentication
- Scalable container architecture

---

# 🔄 Workflow

1. Create the portfolio website.
2. Build a Docker image.
3. Test the container locally on Amazon EC2.
4. Push the Docker image to Amazon ECR.
5. Create an ECS Cluster.
6. Create an ECS Task Definition.
7. Deploy the container using AWS Fargate.
8. Access the application through the Fargate public IP.

---

# 📁 Project Structure

```text
.
├── index.html                 # Portfolio website
├── Dockerfile                 # Docker image configuration
├── README.md
├── task.pdf                   # Complete implementation guide
├── architecture/
│   └── architecture.png
└── screenshots/
    ├── 01-ec2-instance.png
    ├── 02-docker-installation.png
    ├── 03-docker-build.png
    ├── 04-docker-container.png
    ├── 05-ecr-repository.png
    ├── 06-image-push.png
    ├── 07-ecs-cluster.png
    ├── 08-task-definition.png
    ├── 09-fargate-task.png
    └── 10-final-output.png
```

---

# ⚙️ Deployment Steps

- Launch an Amazon Linux EC2 instance.
- Install Docker.
- Build the Docker image.
- Test the application inside a Docker container.
- Create an Amazon ECR repository.
- Authenticate Docker with ECR.
- Push the Docker image.
- Create an ECS Cluster.
- Create an ECS Task Definition.
- Deploy using AWS Fargate.
- Access the application using the public IP.

---

# 🔐 Security

- IAM user for Amazon ECR access
- AmazonEC2ContainerRegistryFullAccess policy
- Security Groups configured for:
  - SSH (22)
  - HTTP (80)
  - Docker Testing (8080)

---

# 📷 Screenshots

The repository includes screenshots of:

- EC2 Instance
- Docker Installation
- Docker Image Build
- Running Docker Container
- Amazon ECR Repository
- Image Push
- ECS Cluster
- ECS Task Definition
- Running Fargate Task
- Final Web Application

---

# 📄 Documentation

The complete implementation guide with commands, configurations, screenshots, and deployment steps is available in:

**📄 task.pdf**

---

# 🎯 Skills Demonstrated

- Docker
- Containerization
- Amazon ECR
- Amazon ECS
- AWS Fargate
- IAM
- AWS CLI
- VPC Networking
- Security Groups
- Serverless Computing
- Cloud Deployment

---

# ✅ Result

The portfolio website was successfully containerized using Docker, stored in Amazon ECR, and deployed through Amazon ECS using AWS Fargate. The application became publicly accessible without managing any servers, demonstrating a practical implementation of serverless container deployment on AWS.

---

# 📚 Key Learnings

- Building Docker images
- Managing container registries
- Deploying containers on ECS
- Running applications with AWS Fargate
- IAM authentication for container services
- Container networking on AWS
- End-to-end cloud deployment

---

# 👨‍💻 Author

**Saiprasad Sambhaji Godge**
