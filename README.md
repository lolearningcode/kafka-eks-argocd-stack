# kafka-eks-argocd-stack
# Event-Driven K8s Platform 🚀

A real-world, cloud-native project that combines Terraform, Ansible, GitHub Actions, ArgoCD, Kubernetes, Kafka, and Prometheus to build a scalable, event-driven microservices architecture — perfect for preparing for principal engineer interviews or demonstrating DevOps mastery.

---

## 🧠 Project Goal

Build a fault-tolerant, observable, production-grade platform that:
- Ingests patient update events in real-time
- Streams them through Apache Kafka
- Deploys producer/consumer microservices on Kubernetes (EKS)
- Monitors system health with Prometheus + Grafana
- Uses GitOps CI/CD with GitHub Actions + ArgoCD
- Provisions infra with Terraform and configures Kafka via Ansible (with dynamic EC2 inventory)

---

## 🛠️ Tech Stack

| Category        | Tools Used                             |
|----------------|----------------------------------------|
| Infrastructure | Terraform (VPC, EKS, EC2, RDS)         |
| Config Mgmt     | Ansible w/ AWS EC2 dynamic inventory   |
| Container Platform | Kubernetes (EKS)                   |
| CI              | GitHub Actions                         |
| CD              | ArgoCD + Helm                         |
| Event Streaming | Apache Kafka                          |
| Monitoring      | Prometheus + Grafana                  |
| Language        | Python (Producer + Consumer APIs)     |

---
