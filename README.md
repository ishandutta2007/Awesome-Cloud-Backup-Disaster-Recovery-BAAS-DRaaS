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

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Druva Backup and Disaster Recovery](https://www.druva.com/)** | Cloud-native data protection with agentless backup, global deduplication, and automated cloud DR. Business tier covers core backup; Enterprise adds cross-cloud backup and automated DR; Elite adds self-service rollback and curated cyber recovery . | Quote-only (billed per TB/month after deduplication; 1 credit = 1 TB compressed/deduped data/month)  | No published free tier; trial available via sales |
| **[Veeam Cloud Connect](https://www.veeam.com/)** | Multi-tenant platform for service providers to deliver Veeam-powered off-site backup and DRaaS. Licensed per protected workload (PPU); tenants with rental licenses consume zero points for backup/backup copy, while subscription/perpetual tenants consume 5 PPU per VM . | Free platform (Veeam backup licenses required; VCSP rental points apply)  | Free to deploy; 14-day trial available via service providers  |
| **[Commvault Complete Backup & Recovery](https://www.commvault.com/)** | Enterprise data protection with immutable backups, air-gapped copies, and cleanroom recovery. Command Center provides centralized policy and license management across physical, virtual, and cloud workloads . | Physical server license: ~$1,885–$1,890 per operating instance; VM license: ~$2,729–$2,736 per VM; Endpoint: ~$120 per user  | No free tier; trial available via sales |
| **[Cohesity DataProtect](https://www.cohesity.com/)** | AI-powered data protection with immutable snapshots, threat detection, and DataProtect as a Service (DPaaS) for fully managed cloud backup. DPaaS bundles infrastructure, software, and support into a per-TB subscription . | DPaaS: $200–$500+ per TB annually (based on retention, replication, SLA)  | No free tier; trial available via sales |
| **[Rubrik Cloud Data Management](https://www.rubrik.com/)** | Cloud data management platform with immutable backups, anomaly detection, and orchestrated recovery. Available via Azure Marketplace with long-term billing; Scale Subscription and Utility consumption models available . | Marketplace listing starting at $90,000/month (enterprise scale); Scale Subscription: quote-only (3-year minimum)  | No free tier; trial available via sales |
| **[Acronis Cyber Protect Cloud](https://www.acronis.com/)** | Cyber protection platform combining backup, disaster recovery, and AI-based ransomware detection. Service providers choose per-workload or per-GB pricing; self-hosted storage included in workload price, Acronis data center storage billed separately . | Per-workload: Server €31.20/month, VM €8.84/month, Workstation €4.42/month, M365 seat €2.60/month (EUR)  | Free licensing model for onboarding (limited functionality); pay-as-you-go from there |
| **[Datto SIRIS](https://www.datto.com/)** | Business continuity and disaster recovery appliance with local and cloud virtualization, screenshot verification, and ransomware detection. Pricing based on data usage (2.5:1 sizing ratio; 3:1 if encrypting agents) and server count . | Starting at $995 (varies by device model, storage, retention, contract length)  | No free tier; trial via partner program |
| **[Zerto Disaster Recovery](https://www.zerto.com/)** | Continuous data protection with 5–15 second RPO, journal-based recovery, and multi-VM failover orchestration. Advanced Resilience Edition licensed per VM on annual subscription . | Advanced Resilience Edition: ~$686–$772 per VM/year  | No free tier; trial available via sales |
| **[HYCU R-Cloud (Protégé)](https://www.hycu.com/)** | Multi-cloud data protection platform protecting 100+ workloads across AWS, Azure, GCP, and SaaS apps. Usage-based pricing by VM, TiB, or GiB depending on environment and service options . | Usage-based (quote-only; per VM/TiB/GiB)  | Free trial available; no free version  |
| **[Carbonite Server](https://www.carbonite.com/)** | Server backup with cloud storage, granular restore, and compliance support (HIPAA). Available in Safe (1–3 computers), Safe Pro (up to 25 computers), and Safe Server Backup (1+ servers, up to 25 computers) tiers . | Safe Server Backup: $50/month ($599.99/year billed annually)  | No free tier; 30-day money-back guarantee typically offered |

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
