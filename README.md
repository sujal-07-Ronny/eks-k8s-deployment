# AWS EKS Kubernetes Deployment

Production-style frontend application deployment on Amazon EKS using Kubernetes, AWS LoadBalancer, Route53, and CloudWatch.

---

# Tech Stack

- Docker
- Kubernetes
- Amazon EKS
- AWS LoadBalancer
- Route53
- CloudWatch

---

# Project Overview

This project demonstrates deployment of a containerized frontend application on Amazon EKS using Kubernetes Deployments and Services.

The application was exposed publicly using AWS LoadBalancer and connected with a custom domain using Route53. CloudWatch logging was enabled for EKS observability and monitoring.

---

# Architecture

User → Route53 → AWS LoadBalancer → EKS Cluster → Kubernetes Pods

---

# Kubernetes Components Used

## Deployment
Used to manage application pods and replicas.

## Pods
Frontend application containers running inside EKS.

## Service (LoadBalancer)
Exposed the application publicly over the internet.

---

# Monitoring

Enabled Amazon CloudWatch logging for EKS control plane observability.

Logs enabled:
- API logs
- Audit logs
- Authenticator logs

---

# Key Learnings

- Containerized application deployment using Docker
- Kubernetes Deployments and Services
- Amazon EKS cluster management
- Public application exposure using LoadBalancer
- Route53 DNS integration
- CloudWatch logging and monitoring

---

