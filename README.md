# Orlando Solis

### Infrastructure Automation | Site Reliability Engineering | Hybrid Cloud

Experienced IT professional focused on systems administration, infrastructure operations, automation, and hybrid cloud technologies, building automation-first platforms across Windows, Linux, Azure, Proxmox, Active Directory, and hybrid cloud environments while documenting the journey through a public, verifiable portfolio.


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

    Automation
      Ansible
      Terraform
      PowerShell
      Python
      Bash
      WinRM

    Security
      WireGuard
      PKI
      mTLS
      Zero Trust
      Ansible Vault

    Observability
      Grafana
      Prometheus
      PostgreSQL
      FinOps

    Recovery
      Clonezilla
      Backup Automation
      RAID Replication
      Disaster Recovery
      Recovery Validation

    Endpoint Management
      Fleet OSS
      Orbit
      osquery
      Multi-OS Management

    Platforms
      Software Distribution
      Data Resilience
      Security Station
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
| In Progress | Dev-Ops-07 — Software Distribution | Centralized software deployment platform |
| Complete | [Dev-Ops-08 — Multi-OS Hybrid Data Resilience & Preventive Disaster Recovery](https://github.com/luisorlandosolis/dev-ops-08-multi-os-hybrid-data-resilience-preventive-disaster-recovery-platform) | Cross-environment backup and recovery |
| In Progress | Dev-Ops-09 — Security Station Deployment | Remote-managed kiosk security stations |

### Highlights

- 7-node WireGuard mesh with `/32`-scoped peers and hardened, immutable configs
- Zero Trust PKI with enforced 3-phase mTLS
- Fleet MDM managing enrolled macOS, Linux, and Windows endpoints, including a cross-compiled `orbit.exe` agent build for Windows
- Grafana Security Command Center with one-click breach/remediate webhook actions
- 3-node Proxmox HA cluster with a Terraform destroy/rebuild pipeline
- Full recovery from a multi-day power outage: XFS root filesystem repair, GRUB recovery, fstab/UUID correction, and service restoration across the lab

---

## About Me

What started as self-directed infrastructure learning evolved into a portfolio of infrastructure automation, security, observability, and disaster recovery platforms built through real implementation and incident response rather than isolated lab exercises.

---

## Platform Evolution

```mermaid
flowchart LR
    A[Dev-Ops-01<br>Secure Remote Operations] --> B[Dev-Ops-02<br>Multi-OS Automation]
    B --> C[Dev-Ops-03<br>Infrastructure Provisioning]
    C --> D[Dev-Ops-04<br>FinOps & Observability]
    D --> E[Dev-Ops-05<br>Certificate Lifecycle & Security]
    E --> F[Dev-Ops-06<br>Recovery Automation]
    F --> G[Dev-Ops-07<br>Software Distribution]
    G --> H[Dev-Ops-08<br>Data Resilience & Recovery]
    H --> I[Dev-Ops-09<br>Security Station Deployment]
```
