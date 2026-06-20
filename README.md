# 🚀 Cloud Native Web Application Deployment

## Overview

This project demonstrates end-to-end deployment of a containerized web application using Docker, Docker Hub, GitHub Actions, and AWS EC2.

The application is automatically built and pushed to Docker Hub through a CI/CD pipeline whenever changes are pushed to the GitHub repository.

---

## Architecture

GitHub Repository
↓
GitHub Actions
↓
Docker Hub
↓
AWS EC2 Instance
↓
Live Application

---

## Technologies Used

- HTML
- CSS
- JavaScript
- Docker
- Docker Hub
- GitHub Actions
- AWS EC2
- Nginx
- Linux

---

## Features

- Containerized Web Application
- Docker Image Creation
- Automated CI/CD Pipeline
- Docker Hub Integration
- AWS EC2 Deployment
- Public Application Hosting
- Nginx Web Server

---

## CI/CD Workflow

1. Developer pushes code to GitHub.
2. GitHub Actions automatically triggers.
3. Docker image is built using Docker Buildx.
4. Image is pushed to Docker Hub.
5. AWS EC2 instance pulls the latest Docker image.
6. Container runs and serves the application using Nginx.

---

## Docker Hub Repository

tanishk010/docker-3d-box-app

---

## Live Demo

http://44.211.244.124

---

## Screenshots

### GitHub Actions Workflow
(Add Screenshot)

### Docker Hub Repository
(Add Screenshot)

### AWS EC2 Running Instance
(Add Screenshot)

### Application Output
(Add Screenshot)

---

## Project Structure

```text
.
├── .github/workflows/
│   └── deploy.yml
├── Dockerfile
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## Learning Outcomes

- Docker Image Creation
- Docker Hub Integration
- GitHub Actions Automation
- CI/CD Pipeline Implementation
- AWS EC2 Deployment
- Nginx Configuration
- Linux Server Management

---

## Author

Tanishk Agarwal

B.Tech CSE Student | Cloud & DevOps Enthusiast
