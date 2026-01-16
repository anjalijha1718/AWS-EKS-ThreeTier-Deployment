# Three-Tier Application Deployment on AWS EKS using Terraform & Kubernetes

This project implements a **three-tier web application architecture** deployed on **Amazon EKS** using **Infrastructure as Code (IaC)** principles. The complete setup covers infrastructure provisioning, containerization, Kubernetes orchestration, autoscaling, and monitoring.

This project is designed to demonstrate real-world **DevOps and Cloud-native practices**.

---

## 🏗️ Architecture Overview

The application follows a standard **three-tier architecture**:

- **Frontend**: Web UI exposed via AWS Load Balancer  
- **Backend**: Node.js REST API running in Kubernetes  
- **Database**: MongoDB deployed inside the Kubernetes cluster  

All components run on an **Amazon EKS cluster** with autoscaling enabled.

---

## 🛠️ Technology Stack

- **Cloud**: AWS  
- **Container Orchestration**: Amazon EKS (Kubernetes)  
- **Infrastructure as Code**: Terraform  
- **Containerization**: Docker  
- **Container Registry**: Amazon ECR Public  
- **Monitoring**: Prometheus & Grafana  
- **Package Manager**: Helm  

---

