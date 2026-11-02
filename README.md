<div align="center">

# MD MOHIUDDIN

### Cloud DevOps Engineer · Platform Engineering · Site Reliability

AWS infrastructure, Kubernetes operations, and delivery automation.

**Cherry Hill, NJ** · **Certified Kubernetes Administrator (CKA)**

[LinkedIn](https://www.linkedin.com/in/mdmohiuddin45/) · [Email](mailto:mohiuddn45@gmail.com) · [GitHub](https://github.com/mohiuddin89)

</div>

---

## About me

I'm a Cloud DevOps Engineer with experience across AWS infrastructure, Kubernetes, and CI/CD. My work brings together reusable infrastructure, reviewed delivery pipelines, observability, and hands-on production support.

At Kaplan, I support Amazon EKS and GitOps delivery with Argo CD. Previously, I worked in DevOps roles at JPMorgan Chase & Co. and Tripadvisor.

Outside work, I build a bare-metal Kubernetes homelab to deepen my understanding of cluster lifecycle, networking, storage, and security.

## Professional experience

### Kaplan · Cloud DevOps Engineer
*June 2024 - Present*

- Support a production EKS platform spanning roughly **55 namespaces**, **500+ running pods**, and **256+ Argo CD applications**.
- Develop reusable Terraform modules for EKS, VPC, IAM, RDS, and Secrets Manager, with infrastructure changes delivered through reviewed plans and production approval gates.
- Build GitLab CI/CD pipelines with automated testing, container builds, and Trivy scanning; deliver services through Argo CD and standardized Helm charts.
- Carry production on-call and maintain runbooks, with observability across CloudWatch, Prometheus, Grafana, Loki, OpenTelemetry, and Tempo.
- Reduced AWS spend **20%** through right-sizing, orphaned volume cleanup, and tag-based governance.

### JPMorgan Chase & Co. · DevOps Engineer
*May 2022 - May 2024*

- Built CI/CD pipelines with Jenkins, GitHub Actions, and Docker, reducing deployment time **65%**.
- Automated configuration management across **50+ Linux servers** using Ansible Tower and role-based playbooks.
- Created reusable CloudFormation templates and centralized logging with the ELK Stack and CloudWatch.

### Tripadvisor · DevOps Engineer
*November 2019 - April 2022*

- Managed **100+ AWS servers** across development, staging, and production.
- Migrated **200+ Jenkins jobs** to pipeline-as-code.
- Automated routine operations with Python and Bash and maintained delivery tooling across Jenkins, Bamboo, Bitbucket, and Nexus.

## Technical toolkit

| Area | Technologies |
| :--- | :--- |
| Cloud | AWS: EKS, EC2, ECS/Fargate, Lambda, VPC, IAM, RDS, S3, Route 53 |
| Containers | Kubernetes, Docker, Helm |
| Infrastructure & configuration | Terraform, Pulumi (TypeScript), CloudFormation, Ansible |
| Delivery | GitLab CI/CD, GitHub Actions, Jenkins, Argo CD |
| Observability | CloudWatch, Prometheus, Grafana, Loki, OpenTelemetry, Tempo |
| Security | Trivy, Wiz, Kubernetes RBAC, Secrets Manager, cert-manager |
| Automation & systems | Python, Bash, Linux |

## Personal project

### Homelab v2.5 · Bare-metal Kubernetes platform
*Personal learning and platform engineering project · 2025 - Present*

I'm building a Kubernetes platform on Proxmox, bootstrapped manually with kubeadm to work through the underlying infrastructure from first principles.

- **Networking:** Calico CNI and NetworkPolicy, MetalLB, and ingress-nginx.
- **Storage & certificates:** Longhorn and cert-manager, backed by an internal two-tier PKI.
- **Delivery:** Self-hosted GitLab CE, a runner, and a private container registry; CI lints, tests, builds multi-stage images, and blocks publication on Trivy HIGH or CRITICAL findings.
- **Workflow:** AI-assisted Terraform review, CI configuration, and runbook drafting, with manual review of diffs and plans before accepting changes.

**Repository:** Private; available on request.

This is an independent personal project. The professional experience above describes my employer work.

## Certification

**Certified Kubernetes Administrator (CKA)**

## Connect

Interested in discussing cloud infrastructure, Kubernetes operations, or platform engineering?

[Connect on LinkedIn](https://www.linkedin.com/in/mdmohiuddin45/) · [Send an email](mailto:mohiuddn45@gmail.com)
