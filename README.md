# Mohiuddin

**DevOps / Platform Engineer** · Kubernetes (CKA) · Bare-metal to Cloud · GitOps · Observability

Building production-shape platforms by hand — every layer manually, then automated only where the reasoning survives review. Currently running a bare-metal Kubernetes platform with a distributed OpenTelemetry reference workload, hardened through a real CVE remediation cycle and verified with recovery drills.

📍 New Jersey, US · Open to remote DevOps / Platform Engineer / SRE roles

---

### About

```yaml
name: Mohiuddin
role: DevOps / Platform Engineer
location: New Jersey, US (remote-open)
certifications:
  - Certified Kubernetes Administrator (CKA)
current_focus:
  - Bare-metal Kubernetes platform (kubeadm, Calico, Longhorn)
  - GitOps with ArgoCD, CI with GitLab + Kaniko + Trivy
  - Observability (Prometheus, Loki, Jaeger, OpenTelemetry)
  - Secret management with External Secrets Operator
  - CVE hardening and recovery drills as first-class work
next:
  - AWS / EKS migration via Terraform (Phase 15)
  - ESO backend swap to AWS SSM Parameter Store
```

---

### Certifications

**Certified Kubernetes Administrator (CKA)** — Cloud Native Computing Foundation

---

### How I Work

- **Manual first, then automate.** I install every layer by hand before letting a tool automate it, because I want to know what a tool is doing before I trust it.
- **Break-it discipline.** Every phase closes with a controlled failure and a documented recovery. A capability is not proven until I have broken it and brought it back.
- **Evidence over assertion.** "It worked" is not closure. Closure means terminal output, committed runbooks, and honest scoping of what still doesn't work.
- **Honest limits.** Every case study I write ends with "where the work stops." A claim without a boundary is a claim I can't defend in an interview.

---

### Tech Stack

| Category | Technologies |
| --- | --- |
| **Kubernetes** | kubeadm, containerd, Calico, Longhorn, MetalLB, ingress-nginx, cert-manager, metrics-server |
| **GitOps & CI/CD** | ArgoCD, GitLab CI, GitLab Runner, Kaniko, Trivy |
| **Secrets** | External Secrets Operator, Kubernetes-native source plane |
| **Observability** | Prometheus, Grafana, Loki, Promtail, Jaeger, OpenTelemetry Collector |
| **Infrastructure** | Proxmox, Ubuntu Server, Bash |
| **Cloud (in progress)** | AWS (EKS, VPC, SSM, IAM, Route 53), Terraform |
| **Languages** | Bash, YAML, some Python |

---

### Featured Project

**[bare-metal-kubernetes-platform-astroshop](https://github.com/mohiuddin89/bare-metal-kubernetes-platform-astroshop)** — Production-inspired Kubernetes on bare-metal with a distributed OpenTelemetry reference workload (Astroshop).

- Built from the ground up: hypervisor, cluster install, CNI, storage, LoadBalancer, ingress, CA
- **CVE hardening cycle:** 18 of 18 HIGH/CRITICAL findings closed with real fixes and dated per-service suppressions
- **Recovery drill:** etcd snapshot restored into an isolated target with 7-step verification, live datastore untouched
- **NetworkPolicy debugging case study:** selective silent drops on Calico's post-DNAT policy evaluation — a real debug story with a generalizable lesson
- **CI pipeline:** 6 stages (lint → build → scan → size-check → health-test → push), Kaniko-based (no privileged runners), Trivy-gated

Read the case studies, architecture decisions, and honest limits: [github.com/mohiuddin89/bare-metal-kubernetes-platform-astroshop](https://github.com/mohiuddin89/bare-metal-kubernetes-platform-astroshop)

---

### What's Next

Extending the same platform into an AWS/EKS deployment via Terraform — same workload, same GitOps repos, ESO backend swap from Kubernetes-native to AWS SSM Parameter Store. Written as a comparison exercise, with residual-audit and next-day billing verification as first-class evidence practices.

---

*Available for remote DevOps, Platform Engineering, and SRE roles in the US. Reach out via LinkedIn or open an issue on any of my repos.*
