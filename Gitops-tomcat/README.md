# Tomcat GitOps Deployment (Custom WAR)

This repository contains Kubernetes manifests for deploying a custom WAR application on Apache Tomcat using GitOps via ArgoCD.

---

## 📦 Project Overview

- **Base Image:** [`bitnami/tomcat:9.0`](https://hub.docker.com/r/bitnami/tomcat)
- **Custom Image:** `dcOllOctOr/tomcat-war:v1`
- **Deployment Type:** GitOps (ArgoCD)
- **Target Platform:** Minikube / Kubernetes

---

## 📁 File Structure
.
├── deployment.yaml # Deployment for custom Tomcat + WAR image
├── service.yaml # NodePort service exposing Tomcat
└── README.md # This file
## 🚀 Deployment Instructions (Manual)

You can apply the manifests directly:

```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml


✍ Author
Created and maintained by [Davod Azari]
DockerHub: dc0ll0ct0r


