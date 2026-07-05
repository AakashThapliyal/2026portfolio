<div align="center">

# 🚀 Cloud-Native Portfolio Deployment using Docker & Kubernetes

Deploying a personal portfolio website using **Docker**, **Kubernetes (Minikube)**, and **GitHub Pages** while following modern containerization and deployment practices.

<br>

[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![Minikube](https://img.shields.io/badge/Minikube-02569B?style=for-the-badge&logo=kubernetes&logoColor=white)](https://minikube.sigs.k8s.io/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)](https://github.com/)
[![Docker Hub](https://img.shields.io/badge/DockerHub-2496ED?style=for-the-badge&logo=docker)](https://hub.docker.com/)

</div>

---

# 🌐 Live Demo

### 🔗 Portfolio Website

**https://aakashthapliyal.github.io/2026portfolio/**

---

# 📖 Project Overview

This project demonstrates the deployment of a personal portfolio website using Docker and Kubernetes. The application is containerized with Docker, published to Docker Hub, and deployed on a Kubernetes cluster running on Minikube.

The primary objective of this project is to gain hands-on experience with containerization, Kubernetes deployments, service exposure, and modern DevOps deployment workflows.

---

# ✨ Key Features

- Containerized static portfolio website
- Docker image published to Docker Hub
- Kubernetes Deployment with multiple replicas
- NodePort Service for external access
- Local Kubernetes cluster using Minikube
- YAML-based infrastructure configuration
- Version controlled with Git and GitHub

---

# 🛠️ Tech Stack

| Category | Technologies |
|-----------|--------------|
| Frontend | HTML, CSS, JavaScript |
| Containerization | Docker |
| Container Registry | Docker Hub |
| Orchestration | Kubernetes |
| Local Cluster | Minikube |
| Version Control | Git, GitHub |

---

# 🏗️ Project Architecture

```
              Portfolio Website
                      │
                      ▼
              Docker Image
                      │
                      ▼
               Docker Hub
                      │
                      ▼
        Kubernetes Deployment
                      │
                      ▼
          ReplicaSet / Pods
                      │
                      ▼
          Kubernetes Service
                      │
                      ▼
             Minikube Cluster
```

---

# 📂 Project Structure

```
2026portfolio
│
├── index.html
├── Dockerfile
├── deployment.yaml
├── service.yaml
├── README.md
└── aakashpicture.png
```

---

# ⚙️ Deployment Workflow

### Clone Repository

```bash
git clone https://github.com/AakashThapliyal/2026portfolio.git

cd 2026portfolio
```

---

### Build Docker Image

```bash
docker build -t aakash22sharma/my2026portfolio:v1 .
```

---

### Push Image to Docker Hub

```bash
docker push aakash22sharma/my2026portfolio:v1
```

---

### Start Minikube

```bash
minikube start
```

---

### Create Namespace

```bash
kubectl create namespace my2026portfolio
```

---

### Deploy Application

```bash
kubectl apply -f deployment.yaml -n my2026portfolio
```

---

### Create Service

```bash
kubectl apply -f service.yaml -n my2026portfolio
```

---

### Verify Deployment

```bash
kubectl get all -n my2026portfolio
```

---

### Access Application

```bash
minikube service my2026portfolio-service -n my2026portfolio
```

---

# 📊 Skills Demonstrated

- Docker Image Creation
- Docker Hub Image Management
- Kubernetes Deployments
- Replica Management
- NodePort Services
- YAML Manifest Configuration
- Container Orchestration
- Linux Command Line
- Git & GitHub Workflow

---

# 📸 Project Screenshots

## Portfolio Website

> Replace with your screenshot.

![Portfolio Homepage](screenshots/portfolio-home.png)

---

## Docker Image

> Screenshot of Docker Hub repository.

![Docker Hub](screenshots/dockerhub.png)

---

## Kubernetes Pods

> Running pods after deployment.

![Pods](screenshots/pods.png)

---

## Kubernetes Service

> Output of `kubectl get svc`.

![Service](screenshots/service.png)

---

## Deployment

> Output of `kubectl get deployment`.

![Deployment](screenshots/deployment.png)

---

# 📚 Learning Outcomes

Through this project, I gained hands-on experience with:

- Building Docker images
- Publishing images to Docker Hub
- Creating Kubernetes Deployments
- Managing ReplicaSets and Pods
- Exposing applications using NodePort Services
- Deploying applications on Minikube
- Writing Kubernetes YAML manifests
- Following Git and GitHub workflow for version control

---

# 👨‍💻 Author

**Aakash Thapliyal**

📧 Email: iaakashthapliyal@gmail.com

💼 LinkedIn: *(Add your LinkedIn URL here)*

🐙 GitHub: https://github.com/AakashThapliyal

🌐 Portfolio: https://aakashthapliyal.github.io/2026portfolio/

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.