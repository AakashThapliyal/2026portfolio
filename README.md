\# Kubernetes Portfolio Deployment



\## Project Overview



This project demonstrates the deployment of a personal portfolio website using Docker and Kubernetes (Minikube).



\## Technologies Used



\* HTML

\* CSS

\* JavaScript

\* Docker

\* Docker Hub

\* Kubernetes

\* Minikube

\* Git

\* GitHub



\## Project Architecture



Portfolio Website

↓

Docker Image

↓

Docker Hub

↓

Kubernetes Deployment

↓

Kubernetes Service

↓

Minikube Cluster



\## Docker Commands



Build Image



docker build -t aakash22sharma/my2026portfolio:v1 .



Push Image



docker push aakash22sharma/my2026portfolio:v1



\## Kubernetes Commands



Create Namespace



kubectl create namespace my2026portfolio



Deploy Application



kubectl apply -f deployment.yaml



Create Service



kubectl apply -f service.yaml



Check Resources



kubectl get all -n my2026portfolio



Access Application



minikube service my2026portfolio-service -n my2026portfolio --url



\## Features



\* Containerized portfolio website

\* Kubernetes Deployment with replicas

\* NodePort Service exposure

\* Docker Hub image hosting

\* Scalable architecture



\## Author



Aakash Thapliyal



