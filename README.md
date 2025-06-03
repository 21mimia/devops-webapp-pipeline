# 🚀 DevOps WebApp Pipeline

This project demonstrates a simple web application integrated with a complete DevOps pipeline using **Docker** and **GitHub Actions**. It is designed to showcase core DevOps practices such as containerization, automation, and CI/CD workflows.

## 📦 Project Structure



devops-webapp-pipeline/
├── .github/
│ └── workflows/
│ └── ci.yml # GitHub Actions CI workflow
├── app.py # Flask web application
├── Dockerfile # Docker image definition
├── .gitignore # Ignored files
└── README.md # Project documentation


## 🌐 About the Application

This is a minimal Python Flask application that serves a simple greeting message:

```bash
Hello from DevOps Engineer!


## 🌐 About the Application

This is a minimal Python Flask application that serves a simple greeting message:

```bash
Hello from DevOps Engineer!


## 🌐 About the Application

This is a minimal Python Flask application that serves a simple greeting message:

```bash
Hello from DevOps Engineer!
🐳 Docker Instructions
Build the Docker Image

docker build -t devops-app .


Run the Container

docker run -d -p 5000:5000 devops-app


Test in Browser
Navigate to: http://localhost:5000



CI/CD with GitHub Actions
A GitHub Actions workflow is included to automate:

Code checkout

Python environment setup

Dependency installation

Basic test (verifying app endpoint)

Path: .github/workflows/ci.yml


Technologies Used
Python 3.9

Flask

Docker

GitHub Actions



Future Enhancements
Add unit testing and code coverage

Push Docker image to Docker Hub/GitHub Container Registry

Deploy to Azure App Service or Kubernetes

Infrastructure as Code with Terraform




🧑‍💻 Author
Mimia 
Azure Cloud Engineer | DevOps Enthusiast
