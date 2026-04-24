# Kubernetes ArgoCD Deployment (GitOps)

## Overview
This project implements a GitOps-based continuous deployment approach using ArgoCD on a Kubernetes cluster.

## Tech Stack
- Kubernetes
- ArgoCD
- Docker
- Kind
- kubectl

## Architecture Workflow
1. Kubernetes cluster is created using Kind.
2. ArgoCD is installed and configured.
3. Application manifests are stored in Git.
4. ArgoCD automatically syncs and deploys applications.
5. Kubernetes Dashboard is used for monitoring.

## Key Features
- GitOps-based deployment model
- Automated synchronization with Git repositories
- Continuous delivery using ArgoCD

## Challenges
- ArgoCD configuration
- Cluster setup using Kind
- Port forwarding and dashboard access

## Results
- Fully automated deployment pipeline
- Efficient application lifecycle management

## Documentation
Refer to `project-report.pdf`.
