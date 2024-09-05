Docker Test Repository
This repository contains resources to demonstrate a Docker-based application setup with Jenkins pipeline and Kubernetes deployment configurations.

Repository Contents
Dockerfile: Defines the application container image.
Jenkinsfile: Automates the build, test, and deployment processes using Jenkins.
Kubernetes deployment (k8sdeploy.yml): Describes the Kubernetes deployment for the application.
HTML/CSS/JS files: Basic frontend web application (index.html, style.css, scorekeeper.js).
Nginx Config (ngnix_default.config): Configuration file for Nginx web server.
How to Use
Clone the repository.
Build the Docker image:
bash
Copy code
docker build -t your-image-name .
Deploy using Kubernetes:
bash
Copy code
kubectl apply -f k8sdeploy.yml
Access the application via the Nginx web server.
