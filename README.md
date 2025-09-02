# Minikube Nginx Deployment Demo

This project demonstrates how to deploy a **simple Nginx web server** on a **local Kubernetes cluster** using **Minikube**. It covers creating a **Deployment**, exposing it via a **NodePort service**, and accessing the application locally. This is a hands-on example for beginners to understand **Kubernetes concepts** in practice.

---

## 🛠️ Prerequisites

Before starting, ensure the following tools are installed:

- **Windows 10/11** (or any OS supporting Minikube)  
- **Docker Desktop** (for container runtime)  
- **Minikube** (local Kubernetes cluster)  
- **kubectl** (Kubernetes CLI tool)  

**References:**  
- [Install Minikube](https://minikube.sigs.k8s.io/docs/start/)  
- [Install kubectl](https://kubernetes.io/docs/tasks/tools/)

---

## ⚡ Key Kubernetes Concepts

1. **Pod**: Smallest deployable unit. A pod can contain one or more containers.  
2. **Deployment**: Manages pods, ensures the desired number of replicas are running, provides **self-healing** and **rolling updates**.  
3. **Service**: Provides stable network access to pods. **NodePort Service** exposes the application externally on a port.  
4. **Minikube**: Local Kubernetes cluster running inside Docker or VM, ideal for development and learning.  

---
