# CI/CD Pipeline with Kubernetes Deployment

## 📌 Project Overview
This project demonstrates an end-to-end CI/CD pipeline for a containerized application using GitHub Actions and Kubernetes.  
The pipeline automates code checkout, validation, and deployment workflows without requiring Docker installation on the local machine.

## 🛠️ Tech Stack
- GitHub Actions (CI/CD)
- Docker (simulated build)
- Kubernetes
- YAML
- Python
- Git & GitHub

## 📂 Project Structure
## ⚙️ CI/CD Workflow
The GitHub Actions pipeline performs the following steps:
1. Checks out source code from the repository
2. Lists project files for validation
3. Simulates Docker image build (Docker not required locally)
4. Validates Kubernetes YAML manifests
5. Ensures CI pipeline runs successfully on every push

## ☸️ Kubernetes Deployment
- Kubernetes deployment and service YAML files are included
- Manifests are validated during CI execution
- Designed to be cluster-ready for real deployments

## 🚀 Outcome
- Fully functional CI/CD pipeline
- Kubernetes-ready application
- Demonstrates real-world DevOps workflow
- Suitable for DevOps Engineer interviews and hands-on evaluation

## 📎 Repository Link
This repository is actively maintained and used as a DevOps portfolio project.
