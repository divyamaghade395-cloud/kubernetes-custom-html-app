# Kubernetes Custom HTML Application

## Project Overview

This project demonstrates deployment of a custom HTML application on Kubernetes using Docker Desktop Kubernetes cluster.

The application was containerized using Docker and deployed using Kubernetes Deployment and Service resources.

---

## Technologies Used

* Kubernetes
* Docker
* Docker Desktop
* HTML
* Nginx
* YAML
* Kubectl

---

## Features

* Custom HTML application deployment
* Docker containerization
* Kubernetes Deployment
* Kubernetes Service
* Pod scaling
* Self-healing
* Port forwarding
* Troubleshooting Kubernetes image issues

---

## Project Architecture

Browser → Kubernetes Service → Deployment → Pods → Docker Container

---

## Commands Used

### Deploy Application

```bash
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
```

### Verify Pods

```bash
kubectl get pods
```

### Scale Application

```bash
kubectl scale deployment custom-html-deployment --replicas=4
```

### Delete Application

```bash
kubectl delete -f deployment.yaml -f service.yaml
```

---

## Learning Outcome

This project helped me understand Kubernetes architecture, container orchestration, Docker integration, deployment management, networking, scaling, and troubleshooting.
