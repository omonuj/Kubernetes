# Kubernetes Configurations and Deployments

This repository contains practical Kubernetes YAML manifests and configuration files used to deploy and manage containerized applications in a cluster environment. It’s a collection of hands-on examples for learning and managing Kubernetes workloads in development or testing environments.

---

## 📦 What’s Included

- **Pods** – Basic pod definitions  
- **Deployments** – Rolling updates and scalable deployments  
- **Services** – ClusterIP, NodePort, and LoadBalancer setups  
- **Ingress** – Route traffic using Ingress controllers  
- **ConfigMaps & Secrets** – Externalize app configuration securely  
- **Namespaces** – Environment isolation  
- **Volumes** – Persistent storage using `hostPath`, `emptyDir`, and `PVC`  
- **RBAC** – Role-based access control with Roles & RoleBindings  
- **Health Checks** – `livenessProbe` and `readinessProbe` examples  

---

## 🧰 Prerequisites

Before you begin, make sure you have the following tools installed:

- [Docker](https://docs.docker.com/get-docker/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/)
- A Kubernetes cluster (e.g. [Minikube](https://minikube.sigs.k8s.io/docs/) or [Kind](https://kind.sigs.k8s.io/))

---

## 🚀 Getting Started

### Start a Local Cluster (Minikube Example)

```bash
minikube start
kubectl get nodes


# Hello World Rest API

### Running the Application

Run omonuj.rest.webservices.restfulwebservices.RestfulWebServicesApplication as a Java Application.

- http://localhost:8080/hello-world

```txt
Hello World V1 abcde
```

- http://localhost:8080/hello-world-bean

```json
{"message":"Hello World"}
```

- http://localhost:8080/hello-world/path-variable/omonuj

```json
{"message":"Hello World, Omonuj"}
```
