<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║        CHINNAYYA CHINTHA  ·  DevOps & Site Reliability       ║
║        Building infra that doesn't wake me up at 3am         ║
╚══════════════════════════════════════════════════════════════╝
```

[![LinkedIn](https://img.shields.io/badge/LinkedIn-chinnayyadevops-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/chinnayyadevops/)
[![Email](https://img.shields.io/badge/Email-chinnayya339@gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:chinnayya339@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-chinnayyachintha-181717?style=flat-square&logo=github)](https://github.com/chinnayyachintha)

</div>

---

## `whoami`

```yaml
name:       Chinnayya Chintha
role:       Associate Consultant · Site Reliability Engineer
company:    Yash Technologies
location:   Hyderabad, India
mission:    Automate everything. Secure by default. Own it end-to-end.
```

I design and operate **cloud-native infrastructure** that is resilient by architecture, not by accident.  
Currently scaling multi-account AWS environments with governance automation, zero-downtime Kubernetes delivery pipelines, and security controls that live in code — not spreadsheets.

---

## 🏗️ What I Build

### Infrastructure as Code
Terraform-first, always. Reusable modules for EKS clusters, VPC networking, IAM Identity Center, EFS storage, and multi-account Control Tower landing zones. Infrastructure that is version-controlled, auditable, and reproducible.

```hcl
# How I think about infra
module "eks_cluster" {
  source          = "./modules/eks"
  cluster_name    = var.cluster_name
  node_groups     = var.node_groups
  # Security-first: encryption, IRSA, private endpoints — defaults, not options
}
```

### Cloud Governance at Scale
Multi-account AWS with **AWS Control Tower + Organizations + SCPs** — policy enforcement baked into account vending, not retrofitted. Cloud Custodian for real-time compliance automation across environments.

### Zero-Downtime Delivery
GitOps with Argo CD, canary strategies with Argo Rollouts, Prometheus health gates as deployment blockers. Pipelines in GitLab CI / GitHub Actions that promote or auto-rollback based on SLO signals.

### Observability That Actually Tells You Something
Prometheus · Grafana · ELK · CloudWatch · Dynatrace — not just dashboards, but alert routing, SLA burn-rate tracking, and post-mortem loops that reduce MTTR over time.

---

## 🧰 Core Stack

| Domain | Tools |
|---|---|
| **Cloud** | AWS (EKS, VPC, IAM, EC2, S3, RDS, Lambda, CloudTrail, Route53) |
| **IaC** | Terraform, CloudFormation, Ansible |
| **Containers & Orchestration** | Docker, Kubernetes, Helm, Argo CD, Argo Rollouts |
| **CI/CD** | GitLab CI, GitHub Actions, Jenkins |
| **Observability** | Prometheus, Grafana, ELK Stack, CloudWatch, Dynatrace |
| **Security** | GuardDuty, Security Hub, AWS Config, KMS, Secrets Manager, Cloud Custodian |
| **Governance** | AWS Control Tower, Organizations, SCPs, IAM Identity Center |
| **Scripting** | Python, Bash, YAML |

---

## 📊 Impact by Numbers

```
  60%   reduction in infrastructure provisioning time via Terraform modules
  40%   faster deployments after CI/CD pipeline redesign
  30%   reduction in downtime post-observability stack implementation
  99.9% uptime maintained across production systems (12+ months)
   ~0   policy violations after SCP and Config rule enforcement rollout
```

---

## 🔭 Current Focus

- **Multi-account AWS governance** — scaling Control Tower patterns with automated account vending and drift detection
- **Platform engineering** — building internal developer platforms that make the right thing the easy thing
- **Cloud security posture** — integrating GuardDuty + Security Hub into GitOps pipelines as pre-merge gates
- **Knowledge sharing** — documenting hard-won infrastructure patterns as reusable open-source modules

---

## 🧠 Engineering Principles

> **Own it end-to-end.** From architecture decision to production alert — if I designed it, I operate it and improve it.

> **Security is a pipeline stage, not a phase.** Policy-as-code, shift-left scanning, least-privilege by default.

> **Automate the toil, document the reasoning.** Scripts save time. READMEs save sanity.

> **Measure what matters.** MTTR, deployment frequency, change failure rate — SRE without SLOs is just on-call rotation.

---

## 📌 Featured Projects

### [`aws-control-tower-governance`](https://github.com/chinnayyachintha)
Multi-account AWS governance framework — Control Tower landing zone, SCP library, Cloud Custodian policies, and automated remediation via Lambda. Enforces CIS benchmarks across all accounts.

`Terraform` `Control Tower` `SCPs` `Cloud Custodian` `Security Hub` `Lambda`

---

### [`eks-gitops-platform`](https://github.com/chinnayyachintha)
Production-grade EKS cluster with GitOps delivery via Argo CD — canary deployments, Prometheus SLO gates, automated rollback, and Helm chart library for internal services.

`Terraform` `EKS` `Argo CD` `Prometheus` `Grafana` `GitLab CI` `Helm`

---

### [`self-healing-infra`](https://github.com/chinnayyachintha)
Runbook automation system — Alertmanager routes incidents to Lambda/Ansible playbooks that self-heal common failure modes. Tracks MTTR improvement over time in Grafana.

`Prometheus` `Alertmanager` `Ansible` `Lambda` `Grafana` `Python`

---

<div align="center">

```
┌─────────────────────────────────────────────────────────────┐
│  Open to infrastructure challenges worth solving.           │
│  Let's talk: chinnayya339@gmail.com                         │
└─────────────────────────────────────────────────────────────┘
```

*"The goal of infrastructure is to disappear. If you notice it, something went wrong."*

</div>
