# CGI Automation Challenge

This project demonstrates how to provision, deploy, secure, and operate a cloud-native application on Kubernetes using modern DevOps tooling.

## Tech Stack

- Kubernetes (Kind)
- Docker
- kubectl
- Ingress
- TLS (Self-Signed Certificates)
- Metrics Server
- Horizontal Pod Autoscaler (HPA)
- Ansible
- Vagrant
- Linux

## Getting Started

```bash
vagrant up
ansible-playbook -i ./inventory.yml ./k8s-cluster-creation.yml --timeout 30
ansible-playbook -i ./inventory.yml ./k8s-configuration.yml
```

## Goals

- Demonstrate Kubernetes fundamentals
- Apply DevOps best practices
- Automate infrastructure provisioning
- Build a reproducible deployment pipeline

---

Created as part of the **CGI Automation Challenge.**
