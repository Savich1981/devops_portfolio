

# devops_portfolio
# Infrastructure & Cloud Engineering Course Portfolio

## 🧭 Overview
This repository contains all lab implementations, automation scripts, and infrastructure-as-code (IaC) artifacts developed throughout the Advanced Cloud Engineering & DevOps Course.

Every phase demonstrates production-ready patterns emphasizing security-first design, immutable infrastructure, and automated delivery pipelines.

---

## 📂 Course Phases & Architecture

| Phase | Focus Area | Primary Tech Stack | Key Deliverables |
| :--- | :--- | :--- | :--- |
| **[Phase 1](./phase-01-foundations/)** | Cloud Foundations & Networking | Terraform, AWS/Azure | VPCs, subnets, IAM least-privilege roles |
| **[Phase 2](./phase-02-configuration-mgmt/)** | Configuration & Automation | Ansible, Python, Bash | Hardened Linux base images, automated patching |
| **[Phase 3](./phase-03-orchestration/)** | Containerization & Orchestration | Kubernetes, Helm, Docker | Microservice deployments, Ingress controllers |

---

## 🔒 Security & Compliance Commitment
* **Zero-Leak Policy:** This repository enforces automated pre-commit hooks and CI/CD secret scanning (via TruffleHog and detect-secrets).
* **State Isolation:** All sensitive state files, variable overrides (`.tfvars`), and credential stores are strictly ignored via `.gitignore`.
