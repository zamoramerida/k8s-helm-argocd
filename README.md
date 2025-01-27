# Kubernetes Deployment with Helm and ArgoCD 🚀

This repository demonstrates deploying a microservice to a Kubernetes cluster using Helm charts and ArgoCD for GitOps.

## Features
- **Helm Charts**: Template-based Kubernetes configurations.
- **ArgoCD**: Continuous deployment with GitOps practices.
- **CI/CD Pipeline**: Automated deployments with GitHub Actions.

## Prerequisites
- Kubernetes cluster (e.g., Minikube, EKS, GKE).
- Helm installed locally.
- ArgoCD installed on the cluster.

## Deployment Steps

### 1. Install ArgoCD
```bash
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml
