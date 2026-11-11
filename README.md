# Awesome-Cloud-Backup-Disaster-Recovery-BAAS-DRaaS

## Top Cloud Backup & Disaster Recovery (BaaS/DRaaS) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Backup as a Service, Disaster Recovery as a Service & Cyber-Resilient Recovery*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Backup & Disaster Recovery (BaaS/DRaaS)**. These tools help organizations protect workloads across on-premises, cloud, and SaaS environments—covering continuous data protection, immutable backups, orchestrated failover, and clean-room recovery for ransomware resilience.

**Examples** include Druva Backup and Disaster Recovery, Veeam Cloud Connect, Commvault Complete Backup & Recovery, Cohesity DataProtect, Rubrik Cloud Data Management, Acronis Cyber Protect Cloud, Datto SIRIS, Zerto Disaster Recovery, HYCU R-Cloud, and Carbonite Server (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted backup engines, disaster recovery orchestration, and multi-cloud data protection—ideal for SREs, platform engineers, and organizations seeking transparent, vendor-neutral resilience without per-TB cloud billing surprises.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Pricing (Starting) | Free Tier / Trial Limits | Description |
|---------|-----------------------------------|-------------------|--------------------------|-------------|
| **[Rubrik Cloud Data Management](https://www.rubrik.com/)** | **~$25.7B** Market Cap (~$1.54B ARR) | Starts at ~$1.50/user/mo (M365) or ~$50,000–$60,000/yr enterprise commit (Cloud Edition) | 30-day proof-of-concept / evaluation via sales (capped at 10 TB or targeted user quotas; user covers underlying cloud storage/compute) | Cloud data management platform with zero-trust architecture, immutable backups, anomaly detection, and orchestrated ransomware recovery. |
| **[Veeam Cloud Connect](https://www.veeam.com/)** | **~$15B** Valuation (~$2B+ ARR) | Starts at $2.63/user/mo (Veeam Data Cloud M365) or $14/TB/mo (Data Cloud Vault storage); VUL perpetual/rental from ~$155/instance/yr | Free forever Community Edition up to 10 workloads (VMs, physical servers, or cloud instances); 30-day trial for enterprise platform | Multi-tenant platform for service providers and hybrid enterprises to deliver Veeam-powered off-site backup, cloud replication, and DRaaS. |
| **[Cohesity DataProtect](https://www.cohesity.com/)** | **~$7B–$8B** Valuation (~$1.5B+ pro forma revenue) | DPaaS baseline starts at ~$29,100/yr on AWS Marketplace (10 BETB pack, ~$242/TB/mo) | 30-day free trial for DataProtect as a Service (DPaaS) via assisted partner evaluation | AI-powered data protection with immutable snapshots, threat detection, and DataProtect as a Service (DPaaS) for fully managed cloud backup. |
| **[Commvault Complete Backup & Recovery](https://www.commvault.com/)** | **~$7.0B** Market Cap (~$1.18B Revenue) | Starts at $1.70/user/mo (Commvault Cloud SaaS for M365) or ~$58.50–$90/TB/mo; $98/VM/yr | 30-day free trial (no credit card required; full access to test hybrid cloud workloads and SaaS apps) | Enterprise data protection with immutable backups, air-gapped cloud copies, and automated cleanroom recovery. |
| **[Datto SIRIS](https://www.datto.com/)** | **$6.2B** Acquisition by Kaseya (Parent ARR: ~$1.5B+) | Starting at $995 upfront hardware (or $0 down on commit) + ~$300–$500/mo service fee (1–2 TB baseline) | 14-day free trial for software products (Datto SaaS Protection / RMM); hardware appliance evaluations provided via MSP partner PoC | Business continuity and disaster recovery appliance with local and cloud virtualization, screenshot verification, and ransomware detection. |
| **[Druva Backup and Disaster Recovery](https://www.druva.com/)** | **~$2.0B** Valuation (~$200M+ ARR) | Starts at ~$200–$250/TB/month (deduplicated cloud storage) or $4–$8/user/month (inSync endpoint tier) | 30-day free trial (full-featured cloud backup evaluation; no credit card or hardware required) | 100% SaaS cloud-native data protection with agentless backup, global deduplication, and automated multi-cloud DR. |
| **[Acronis Cyber Protect Cloud](https://www.acronis.com/)** | **~$1.5B–$3.5B** Valuation (~$420M+ Revenue) | Starts at $1.30–$2.00/seat/mo (M365), $3–$5/workstation/mo, $6.00/VM/mo, or $22.00/server/mo | 30-day free trial for service providers and enterprises (full access to cyber protection suite and cloud backup console) | Cyber protection platform combining backup, disaster recovery, vulnerability management, and AI-based ransomware detection. |
| **[Carbonite Server](https://www.carbonite.com/)** | **$1.45B** Acquisition by OpenText (Parent Rev: ~$5.8B) | Safe Server Power plan starts at $799.99/year (~$66.66/month billed annually) | 30-day free trial for business/server tiers (up to 500 GB cloud storage, database & bare-metal backup testing) | Server backup with encrypted cloud storage, granular restore, bare-metal recovery, and compliance support (HIPAA/FERPA). |
| **[Zerto Disaster Recovery](https://www.zerto.com/)** | **$374M** Acquisition by HPE (~$130M+ Run-Rate Rev) | Enterprise Resilience Edition starts at ~$686–$772 per VM/year (or ~$745–$1,000/VM entry tier) | 14-day software free trial / 30-day cloud marketplace trial (up to 10–15 VMs protected) | Continuous data protection with sub-minute RPOs, journal-based recovery, and orchestrated multi-VM failover. |
| **[HYCU R-Cloud (Protégé)](https://www.hycu.com/)** | **~$250M–$500M** Valuation ($140M funding raised) | SaaS app protection starts at ~$1.20–$4.00/user/mo; cloud infrastructure from ~$0.08–$0.10/GiB/mo | 14-day free trial on Azure/AWS Marketplace (30-day for selected SaaS integrations; user covers underlying cloud storage) | Multi-cloud data protection platform protecting 100+ workloads and SaaS applications across AWS, Azure, Google Cloud, and Nutanix. |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Restic](https://github.com/restic/restic)** | [![Stars](https://img.shields.io/github/stars/restic/restic?style=social&color=white)](https://github.com/restic/restic/stargazers) | Fast, secure, deduplicated backup tool with encryption and support for S3, GCS, Azure Blob, SFTP, and local storage. CLI-first, widely used as a self-hosted BaaS foundation. |
| **[BorgBackup](https://github.com/borgbackup/borg)** | [![Stars](https://img.shields.io/github/stars/borgbackup/borg?style=social&color=white)](https://github.com/borgbackup/borg/stargazers) | Deduplicating, compressing, authenticated backup tool with encryption. Supports local, SSH, and cloud storage backends; mature and battle-tested. |
| **[Velero](https://github.com/vmware-tanzu/velero)** | [![Stars](https://img.shields.io/github/stars/vmware-tanzu/velero?style=social&color=white)](https://github.com/vmware-tanzu/velero/stargazers) | Kubernetes backup and restore tool for cluster resources and persistent volumes. Supports AWS, Azure, GCP, and on-premises storage; includes schedules and pre/post hooks. |
| **[cloud-dr-orchestrator](https://github.com/Kobeep/cloud-dr-orchestrator)** | [![Stars](https://img.shields.io/github/stars/Kobeep/cloud-dr-orchestrator?style=social&color=white)](https://github.com/Kobeep/cloud-dr-orchestrator/stargazers) | Multi-cloud disaster recovery orchestrator with automated backup scheduling, encryption, and restore workflows targeting Oracle Cloud Free Tier. Includes cron/systemd automation and Grafana monitoring hooks . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[ReaR (Relax-and-Recover)](https://github.com/rear/rear)** | [![Stars](https://img.shields.io/github/stars/rear/rear?style=social&color=white)](https://github.com/rear/rear/stargazers) | Linux disaster recovery framework producing bootable rescue images; supports Bacula, Borg, Duplicity, rsync, and many enterprise backup backends. |
| **[Duplicati](https://github.com/duplicati/duplicati)** | [![Stars](https://img.shields.io/github/stars/duplicati/duplicati?style=social&color=white)](https://github.com/duplicati/duplicati/stargazers) | Open-source backup software with web-based management, encryption, and support for S3, SFTP, WebDAV, and cloud storage destinations. |
| **[LitmusChaos](https://github.com/litmuschaos/litmus)** | [![Stars](https://img.shields.io/github/stars/litmuschaos/litmus?style=social&color=white)](https://github.com/litmuschaos/litmus/stargazers) | Chaos engineering platform for validating disaster recovery and resilience through controlled failure injection. |

**Frameworks for building custom systems**: Combine **Restic** or **BorgBackup** for encrypted, deduplicated backup storage, **Velero** for Kubernetes workload protection, **cloud-dr-orchestrator** for multi-cloud DR automation, and **ReaR** for bare-metal Linux recovery—creating a fully self-hosted BaaS/DRaaS stack on commodity infrastructure or Oracle Cloud Free Tier.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Backup and DR tools handle sensitive production data; enforce encryption at rest and in transit, least-privilege access, and regular restore testing.
- Self-hosted open-source solutions require capacity planning, off-site replication, and immutable storage strategies to protect against ransomware; always validate RTO/RPO against business requirements.

---

**Made for SREs, platform engineers, backup administrators, and organizations building cyber-resilient infrastructure.**  
Let's make cloud backup and disaster recovery more open, automated, and provable.
