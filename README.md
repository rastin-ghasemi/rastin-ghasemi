<div align="center">

# Rastin Ghasemi

### DevOps & Platform Engineer
Girne, North Cyprus (Remote)

![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/-Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![ArgoCD](https://img.shields.io/badge/-ArgoCD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)

[![Email](https://img.shields.io/badge/Email-rastinghasemi5%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:rastinghasemi5@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/rastin-ghasemi-269879367)

</div>

## About

DevOps & Platform Engineer building and hardening Kubernetes infrastructure across AWS and Azure. Currently at **Bespokelabs.AI**, designing adversarial Kubernetes incident-response scenarios for AI agent evaluation.

Every project below is a working, documented deployment — not a tutorial clone.

## Experience

**DevOps Engineer — Bespokelabs.AI** · *Mar 2026 – Present, Remote*
Designed 12 hard-difficulty Kubernetes incident-response tasks for an AI agent benchmarking platform (Istio mTLS, MinIO, RabbitMQ, Keycloak SSO, MongoDB replica sets). Achieved a perfect 1.0 solution score on the ephemeral-environments task and authored grader automation in Python/Bash. Hardened sandboxes against reward hacking via scoped RBAC and ValidatingAdmissionPolicies.

**DevOps Engineer — Narvanestan** · *Nov 2023 – Jun 2024*
Ran 3 Kubernetes clusters (12 nodes) with zero-downtime deployments for ~15 microservices. Cut GitLab CI job runtime ~40% through Docker image caching and layer optimization. Deployed Prometheus/Grafana monitoring, reducing MTTD from hours to minutes at 99.9% uptime.

**Linux System & Network Administrator — Parspooyesh Fanavar** · *Aug 2019 – Oct 2023*
Maintained 40+ Linux servers and 20+ PostgreSQL/MongoDB clusters for enterprise clients. Secured infrastructure with iptables and MikroTik VPNs, and automated routine administration with Bash.

## Featured Projects

| Project | Description |
|---|---|
| [**AWS ECS Production Infrastructure**](https://github.com/rastin-ghasemi/Big-project) | Production-grade AWS ECS architecture on Terraform + GitLab CI/CD — VPC, ALB, RDS, EFS, Route53, ACM, ECR — with a 4-stage pipeline and least-privilege IAM throughout. |
| [**Kubernetes Ingress → Gateway API Migration**](https://github.com/rastin-ghasemi/Migrate-Ingress-to-Gateway) | Production-grade migration from NGINX Ingress to the Gateway API (NGINX Gateway Fabric), with a validated 13-step guide and TLS/HTTPRoute troubleshooting. |
| [**Prometheus Operator via OLM**](https://github.com/rastin-ghasemi/Prometheus_Operator) | Prometheus Operator deployed via Operator Lifecycle Manager, with ServiceMonitor/PodMonitor auto-discovery and a node-exporter DaemonSet for host metrics. |
| [**Kubernetes Cluster Security**](https://github.com/rastin-ghasemi/RBAC-NETWORKPLO-TAINT) | 3-node kubeadm cluster on EC2 hardened with RBAC, NetworkPolicies, TLS Ingress, and taints/tolerations. |
| [**Private Docker Registry on K8s + NFS**](https://github.com/rastin-ghasemi/local-registey-nfs) | Private registry on KIND backed by NFS persistent storage, Basic Auth, NetworkPolicy isolation, and a Velero/S3 backup strategy. |
| [**Kubernetes Guestbook Monitoring (Pulumi)**](https://github.com/rastin-ghasemi/kubernetes-guestbook-monitoring) | Pulumi TypeScript IaC (38 resources) adding a full Prometheus/Grafana observability stack, default-deny NetworkPolicies, and PodDisruptionBudgets to the Kubernetes Guestbook app. |
| [**Azure Cloud Infrastructure (Pulumi)**](https://github.com/rastin-ghasemi/azure-aks-appgateway-timescaledb) | Production-shaped Azure environment as code: private VNet, AKS, Postgres Flexible Server + TimescaleDB, TLS Application Gateway, Azure AD RBAC. |

## Full Tech Stack

**Container & Orchestration:** Kubernetes · Docker · Helm · Istio · k3s
**GitOps & CI/CD:** ArgoCD · GitLab CI · Gitea
**Infrastructure as Code:** Terraform · Pulumi
**Cloud:** AWS (EC2, ECS, VPC, RDS, ALB, IAM, Route53, ACM, ECR) · Azure (AKS, VNet, App Gateway)
**Observability:** Prometheus · Grafana · Zabbix
**Data & Messaging:** PostgreSQL · MongoDB · Redis · RabbitMQ
**OS & Languages:** Linux (LPIC 1 & 2) · Python · Bash

## Certifications

AWS Solutions Architect – Associate · LPIC-2 · LPIC-1 · CCNP R&S · CCNA · Network+
