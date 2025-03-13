# **Kubernetes, Docker, and Jenkins: A Comprehensive Guide**  

## **Introduction**  
In modern DevOps and cloud-native development, **Kubernetes, Docker, and Jenkins** are essential tools that help automate deployments, manage containerized applications, and orchestrate workloads efficiently. This document provides an overview of these technologies, how they work, and how to set up Docker for seamless GitHub integration.

---

## **1. Docker: Containerization Platform**  

### **What is Docker?**  
Docker is an **open-source platform** that allows developers to **build, ship, and run** applications inside lightweight, portable **containers**. Containers package an application with all its dependencies, ensuring it runs consistently across different environments.  

### **Key Features of Docker:**  
- **Lightweight:** Uses OS-level virtualization, unlike traditional virtual machines.  
- **Portable:** Works across any system supporting Docker.  
- **Fast Deployment:** Rapidly spin up and tear down applications.  
- **Isolation:** Each container runs independently with its own resources.  

### **Docker Architecture:**  
- **Docker Client:** CLI tool that interacts with the Docker daemon.  
- **Docker Daemon:** Runs in the background, managing containers.  
- **Docker Hub:** Cloud repository for storing and sharing container images.  
- **Docker Images:** Read-only templates for creating containers.  
- **Docker Containers:** Running instances of Docker images.  

### **Installing Docker**  
#### **On Ubuntu**  
```sh
sudo apt update
sudo apt install docker.io -y
sudo systemctl enable --now docker
