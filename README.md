# Hemanthakumar S
### Site Reliability Engineer | DevOps | Cloud Infrastructure

📍 Bangalore, India  
✉️ hemanthakumar.dev@gmail.com  
🌐 [Portfolio](https://hemanthakumar.dev) | [LinkedIn](https://www.linkedin.com/in/hemanthhs/) | [GitHub](https://github.com/hemanthakumar97)

---

## About Me

SRE and DevOps Engineer with **5+ years of experience** in cloud infrastructure, Kubernetes, and CI/CD automation on AWS. At GoGuardian, driving reliability and cost efficiency across EKS-based systems — including AI-augmented workflows that cut hours of manual security analysis to minutes.

Focused on problems where automation has clear leverage: a 90-minute DDoS outage redesigned into a zero-impact edge defense, a 3-day patch cycle compressed to 4 hours, and a 60-minute vulnerability review reduced to under 2 minutes. My goal is infrastructure that's observable, secure, and boring to operate.

---

## Skills

### Cloud Platforms
`AWS` `GCP`

### Containers & Orchestration
`Kubernetes` `Docker` `EKS` `GKE` `Helm` `Karpenter` `Microservices`

### CI/CD
`Jenkins` `GitLab CI` `GitHub Actions` `ArgoCD`

### Infrastructure as Code
`Terraform` `Ansible` `Packer`

### Observability
`Datadog` `Prometheus` `Grafana` `CloudWatch` `SLO Monitoring` `Log Analysis`

### Security
`AWS WAF` `AWS Shield` `DDoS Protection` `AWS Secrets Manager` `IAM` `Patch Management`

### Incident Management
`PagerDuty` `On-Call` `Post-Mortems` `Runbooks`

### Programming & AI
`Python` `AI/LLM Tooling` `Claude` `Codex`

### Databases
`MongoDB Atlas` `SQL`

---

## Work Experience

### Site Reliability Engineer — GoGuardian, Bangalore (Remote)
**July 2023 – Present**

- Built AI skill files for CLI agents (Claude/Codex) to automate vulnerability analysis and DDoS alert investigation, reducing analysis time from 60+ min to under 5 min — enabling engineers to self-serve security investigations without SRE involvement
- Migrated Jenkins from EC2 to EKS, reducing CI/CD infrastructure costs by 50% and eliminating agent queue wait times from 20–30 min to under 1 minute
- Implemented AWS CloudFront and WAF as a layered DDoS mitigation strategy, blocking 4 attacks with zero production impact over 2 years
- Managed AWS infrastructure with Terraform using reusable modules and remote state, ensuring consistent, auditable provisioning aligned with ISO compliance standards
- Migrated Amazon EKS cluster (v1.23 → v1.28) using a blue-green strategy with zero downtime
- Automated kernel and package upgrades using Python & AWS Systems Manager, reducing security vulnerabilities by 80% and cutting patch cycle from 2–3 days to 4 hours
- Developed Python automation scripts reducing manual operational effort by 70%, freeing teams to focus on higher-impact work
- Built centralized Datadog dashboards for all-services health, traffic breakdowns, and DDoS monitoring; defined SLOs with burn-rate alerts to surface reliability risk before customer impact
- Owned end-to-end incident management — configured PagerDuty routing and escalation policies, authored runbooks for common failure scenarios, and led post-mortem reviews
- Designed disaster recovery strategy with defined RTO targets: stateless workloads reprovisionable in <1 hr via Terraform; databases restorable in 1–6 hrs with tested restore procedures
- Centralized secrets management with AWS Secrets Manager, eliminating hardcoded credentials and enforcing least-privilege IAM policies across services
- Managed server configuration and compliance across EC2 fleets using Ansible playbooks, reducing configuration drift
- Led MongoDB Atlas version upgrades via staged rollout (dev → QA → prod), validated index integrity post-upgrade, and maintained a tested revert plan

### DevOps Engineer — 42Gears Mobility Systems, Bangalore
**Nov 2020 – July 2023**

- Implemented Karpenter to replace Cluster Autoscaler, reducing compute costs by 25% and cutting node startup time from 3–5 min to 45 sec
- Designed and implemented GitLab CI/CD pipelines from scratch, reducing manual intervention by 60% and enabling one-click deployments across 5+ microservices
- Developed Python scripts to automate log analysis, reporting, and data processing tasks — 300% increase in processing speed
- Designed AWS VPC architecture with public/private subnet segmentation, routing tables, internet gateways, and security group/NACL rules across dev, QA, and production environments
- Set up and managed GKE clusters including node pool configuration, workload deployment, and version upgrades across environments
- Managed EKS cluster upgrades across environments with zero downtime
- Mentored 2 junior engineers on CI/CD, Kubernetes, and cloud infrastructure — both delivering independently within 3 months

---

## Projects

### Personal Investment Tracker (Wealthfolio)
[GitHub](https://github.com/hemanthakumar97/wealthfolio) — *2026*
- Built a full-stack investment tracking app from scratch using AI-assisted development, self-hosted on a Raspberry Pi
- Automated email parsing to ingest transaction notifications and update portfolio data without manual input

### EKS Cluster and Terraform Modules
[EKS](https://github.com/hemanthakumar97/EKS) · [Terraform](https://github.com/hemanthakumar97/Terraform-IaC) — *2023–2024*
- Provisioned production-grade EKS clusters and reusable Terraform modules for AWS infrastructure
- Built custom AMIs via Packer integrated into CI/CD pipelines for automated image creation

---

## Certifications

- **AWS Certified Solutions Architect – Associate** — Amazon Web Services  
  Valid: Jun 2024 – Jun 2027 · [Verify on Credly](https://www.credly.com/badges/ea38ce64-a146-454c-be61-7206ab7b4e53/)

---

## Education

**Bachelor of Engineering in Computer Science**  
Visvesvaraya Technological University · 2015 – 2019
