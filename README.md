# Orlando Solis

### Platform Engineering | DevSecOps | Site Reliability Engineering

Self-taught platform and infrastructure engineer with about 20 years in IT, building secure hybrid infrastructure, Kubernetes-native CI/CD, and automation-first platforms across Windows, Linux, Azure, Proxmox, Active Directory, and Kubernetes, while documenting the journey through a public, verifiable portfolio.


[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/luis-orlando-solis-8564bbb2/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?logo=gmail&logoColor=white)](mailto:luiso.solis@gmail.com)

---

## Technology Ecosystem

```mermaid
mindmap
  root((Orlando Solis))

    Infrastructure
      Azure
      Active Directory
      Hyper-V
      Proxmox
      Windows Server
      Linux
      Hybrid Infrastructure

    Automation
      Ansible
      Terraform
      PowerShell
      Python
      Bash
      WinRM
      Infrastructure Automation
      Operational Automation

    Security
      WireGuard
      PKI
      mTLS
      Zero Trust
      Ansible Vault
      RBAC
      Service Accounts
      Authentication
      Authorization

    Platform Engineering
      Kubernetes
      Control Plane
      Worker Nodes
      Ingress
      SMB CSI
      Persistent Volumes
      PVC
      Container Runtime
      Dynamic Workloads
      Jenkins on Kubernetes
      HTTPS Services

    CI/CD
      Jenkins
      Static Agents
      Dynamic Kubernetes Agents
      Groovy
      Jenkinsfiles
      Pipeline Automation
      Continuous Delivery

    Recovery Engineering
      Clonezilla
      Backup Automation
      RAID Replication
      Disaster Recovery
      Recovery Validation
      Hybrid Recovery
      Operational Resilience
      Infrastructure Recovery

    Observability
      Grafana
      Prometheus
      Node Exporter
      Custom Telemetry
      PostgreSQL
      FinOps
      Cost Analytics
      Monitoring
      Alerting

    Endpoint Management
      Fleet OSS
      Orbit
      osquery
      Multi-OS Management
      Asset Visibility

    Application Platforms
      Solis Weather Platform
        NGINX Load Balancer
        Weather Node A
        Weather Node B
        Azure DR Node
        WireGuard Mesh

      Azure FinOps Platform
        Azure Cost Data
        Grafana Dashboards
        Cost Analytics
        Cost Visibility

    Delivery Platforms
      GitHub
      GitHub Actions
      Actions Runner Controller
      Static Runners
      Dynamic Runners
      GitHub App Authentication
      cert-manager
      GitOps
      Artifact Management
      Planned
        ArgoCD

    Production Platforms
      Secure Remote Operations Platform
      Multi-OS Automation Platform
      Application Delivery Platform
      Multi-OS Hybrid Data Resilience Platform
      Security Station Deployment Platform
      Source Control and Modernized Delivery Platform

    Community
      Jamf Nation
```

---

## Portfolio

| Status | Platform | Focus |
|---|---|---|
| Complete | [Dev-Ops-01 — Secure Remote Operations](https://github.com/luisorlandosolis/dev-ops-01-secure-remote-operations-platform) | Hardened remote access foundation for the lab |
| Complete | [Dev-Ops-02 — Multi-OS Automation](https://github.com/luisorlandosolis/dev-ops-02-multi-os-automation-platform) | Cross-platform configuration management (Windows/Linux) |
| Complete | [Dev-Ops-03 — Hybrid Infrastructure Provisioning](https://github.com/luisorlandosolis/dev-ops-03-hybrid-infrastructure-provisioning-platform) | Azure + Proxmox provisioning via Terraform and Ansible |
| Complete | [Dev-Ops-04 — FinOps & Cost Observability](https://github.com/luisorlandosolis/dev-ops-04-finops-cost-observability-platform) | Azure cost ingestion and observability pipeline |
| Complete | [Dev-Ops-05 — Certificate Lifecycle & Security Response](https://github.com/luisorlandosolis/dev-ops-05-certificate-lifecycle-security-response-platform) | Automated certificate remediation and closed-loop security response |
| Complete | [Dev-Ops-06 — High Availability & Recovery Automation](https://github.com/luisorlandosolis/dev-ops-06-hybrid-infrastructure-recovery-automation-platform) | Post-outage recovery automation across the lab |
| In Progress | Dev-Ops-07 — KrakkenOS Universal Asset Operations Platform | Universal software distribution, asset lifecycle management, governance, compliance, and automation platform |
| Complete | [Dev-Ops-08 — Multi-OS Hybrid Data Resilience & Preventive Disaster Recovery](https://github.com/luisorlandosolis/dev-ops-08-multi-os-hybrid-data-resilience-preventive-disaster-recovery-platform) | Cross-environment backup and recovery |
| Complete | [Dev-Ops-09 — Security Station Deployment & Recovery Platform](https://github.com/luisorlandosolis/dev-ops-09-security-station-deployment-operations-platform) | Security Station virtualization, deployment automation, recovery workflows, camera integration, WinRM/RDP automation, and operational standardization |
| Complete | [Dev-Ops-10 — Kubernetes Platform Engineering & Operations Platform](https://github.com/luisorlandosolis/dev-ops-10-kubernetes-platform-engineering-operations-platform) | Kubernetes platform engineering, operations, and workload hosting |
| Complete | [Dev-Ops-10.5 — CI/CD Platform](https://github.com/luisorlandosolis/dev-ops-10-5-ci-cd-platform) | GitHub integration, Jenkins automation, Pipeline-as-Code, static and dynamic agents, operational validation, and hybrid infrastructure validation |
| Complete | [Dev-Ops-11 — Source Control & Modernized Delivery Automation Platform](https://github.com/luisorlandosolis/dev-ops-11-source-control-modernized-delivery-automation-platform) | GitHub Actions, static self-hosted runners, ARC dynamic runners, Kubernetes-native workflow execution, custom telemetry, Prometheus, Grafana, platform observability, desired-state monitoring, and operational dashboards |

### Highlights

- Designed and operated a multi-platform DevOps portfolio spanning infrastructure provisioning, automation, FinOps, security operations, recovery automation, Kubernetes platform engineering, and CI/CD delivery.

- Built a 7-node WireGuard mesh with `/32`-scoped peers, Zero Trust PKI, and enforced mutual TLS authentication across hybrid infrastructure environments.

- Implemented cross-platform automation for Windows, Linux, and macOS using Ansible, Fleet, PowerShell, Bash, and Infrastructure-as-Code practices.

- Engineered Azure and Proxmox hybrid infrastructure provisioning workflows using Terraform and automated configuration management.

- Developed FinOps ingestion and observability pipelines providing automated Azure cost collection, reporting, and operational visibility.

- Designed and validated a multi-tier backup, replication, archive, and cloud offsite recovery architecture supporting preventive disaster recovery objectives.

- Built a Kubernetes Platform Engineering & Operations Platform featuring multi-node cluster operations, SMB CSI persistent storage, ingress services, workload hosting, and platform lifecycle management.

- Built a Kubernetes-hosted CI/CD Platform with GitHub integration, Pipeline-as-Code workflows, static and dynamic Jenkins agents, and operational validation automation.

- Built a GitHub Actions delivery platform with a dual runner architecture: a persistent static runner plus ephemeral Kubernetes-hosted runners managed by Actions Runner Controller (ARC), using GitHub App authentication and cert-manager PKI.

- Added end-to-end runner observability with custom telemetry scripts, Node Exporter's textfile collector, Prometheus, and a Grafana operations dashboard covering runner health, ARC desired state, and runtime activity.

- Successfully validated hybrid operational workflows spanning load-balanced application services, WireGuard connectivity, Azure disaster recovery resources, and platform health verification.

---

## About Me

What started as self-directed infrastructure learning evolved into a portfolio of infrastructure automation, security, observability, and disaster recovery platforms built through real implementation and incident response rather than isolated lab exercises.

---

## Platform Evolution

```mermaid
flowchart LR
    subgraph F["Foundation"]
        direction TB
        D01[Dev-Ops-01<br>Secure Remote Operations] --> D02[Dev-Ops-02<br>Multi-OS Automation]
        D02 --> D03[Dev-Ops-03<br>Infrastructure Provisioning]
    end
    subgraph O["Observability & Security"]
        direction TB
        D04[Dev-Ops-04<br>FinOps & Observability] --> D05[Dev-Ops-05<br>Certificate Lifecycle & Security]
        D05 --> D06[Dev-Ops-06<br>Recovery Automation]
    end
    subgraph R["Administration & Resilience"]
        direction TB
        D07[Dev-Ops-07<br>KrakkenOS Asset Operations] --> D08[Dev-Ops-08<br>Data Resilience & Recovery]
        D08 --> D09[Dev-Ops-09<br>Security Station Deployment]
    end
    subgraph K["Cloud Native Delivery"]
        direction TB
        D10[Dev-Ops-10<br>Kubernetes Platform] --> D105[Dev-Ops-10.5<br>CI/CD Platform]
        D105 --> D11[Dev-Ops-11<br>GitHub Actions + ARC + Observability]
    end
    F --> O --> R --> K
```

**Next:** Dev-Ops-11.5 (GitOps and ArgoCD delivery), Dev-Ops-12 (AIOps and multi-OS operations intelligence).
