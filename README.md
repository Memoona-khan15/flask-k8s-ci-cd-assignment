# Flask Kubernetes CI/CD Project

## Project Description
This project demonstrates a full CI/CD pipeline for a Flask app using GitHub Actions, Jenkins, Docker, and Kubernetes.

## Features
- Automated CI with GitHub Actions (pytest + flake8)
- Dockerized Flask application
- Kubernetes deployment with scaling, rolling updates, and load balancing
- Jenkins pipeline for Continuous Delivery

## Build & Run Locally
```bash
docker build -t flask-k8s-ci-cd:latest .
docker run -p 5000:5000 flask-k8s-ci-cd:latest

