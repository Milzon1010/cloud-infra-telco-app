# Cloud Infra Setup for Telco App

This project simulates a cloud-based infrastructure designed for a telecom application, such as network monitoring or KPI tracking. The infrastructure is provisioned using Terraform and deployed on AWS to reflect a real-world environment like Telkomsel’s operational ecosystem.

## 💡 Use Case

Telecommunication companies often require scalable, secure, and resilient infrastructure to monitor network performance, automate alerts, or manage fault detection. This setup reflects:

- 🧭 A multi-AZ VPC for isolation and availability
- 🖥️ EC2 instances acting as monitoring agents or app servers
- ☁️ S3 buckets for storing logs or telemetry data
- 🔒 IAM and Security Groups for secure access
- ⚙️ Terraform for repeatable, scalable infrastructure deployment

## 🔧 Stack & Tools

- **AWS**: EC2, VPC, S3, IAM
- **Terraform**: Infrastructure-as-Code provisioning
- **Bash**: EC2 bootstrap scripting (e.g. for agent install)
- *(Optional next step: Docker / Jenkins / CloudWatch integration)*

## 📁 Structure
cloud-infra-telco-app/
├── terraform/ # All IaC (Terraform files)
├── scripts/ # Bash scripts for EC2 bootstrap
├── diagrams/ # Architecture diagrams (PNG, draw.io, etc.)
├── README.md
└── LICENSE


## 🚀 Status

🔧 Phase 1: Basic VPC + EC2 setup  
📈 Phase 2: Monitoring agent & automation  
🧪 Phase 3: Optional CI/CD or alert system

---
@milzon1010 git hub, milzon.ltf@gmail.com
This repository demonstrates hands-on capabilities in deploying infrastructure for telco operations using modern DevOps principles and cloud-native tools.


