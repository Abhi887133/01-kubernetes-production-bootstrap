# Kubernetes Production Bootstrap

## Overview

This project documents the design, deployment, and operation of a production-ready Kubernetes cluster built using kubeadm on VMware.

## Lab Environment

- Hypervisor: VMware Workstation
- Kubernetes: kubeadm
- Control Plane: 1
- Worker Nodes: 2
- Operating System: Ubuntu 22.04 LTS (update with your OS)
- Container Runtime: containerd
- CNI Plugin: (To be documented)
- Ingress: Planned
- Load Balancer: Planned (MetalLB)

## Objectives

- Build a production-ready Kubernetes platform.
- Learn Kubernetes administration at CKA level.
- Implement GitOps using ArgoCD.
- Add observability using Prometheus, Grafana, and Loki.
- Implement DevSecOps with Vault, Trivy, and Falco.
- Deploy production workloads.

## Repository Structure

```text
docs/
manifests/
scripts/
diagrams/
screenshots/
```

## Progress

- [x] Repository Created
- [x] Cluster Audit
- [x] Control Plane Study
- [x] Networking Fundamentals
- [ ] Ingress
- [ ] Storage
- [ ] Monitoring
- [ ] GitOps
- [ ] Security
