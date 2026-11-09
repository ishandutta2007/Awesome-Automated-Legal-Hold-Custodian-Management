# Awesome-Automated-Legal-Hold-Custodian-Management
# Awesome-Automated-Legal-Hold-Custodian-Management

## Top Automated Legal Hold Custodian Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Legal Hold Automation, Custodian Tracking & Defensible Preservation Workflows*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Automated Legal Hold Custodian Management**. These tools help legal and IT teams automate the legal hold lifecycle — from custodian identification and notice delivery to acknowledgment tracking, escalation, data preservation, and release — while maintaining a defensible audit trail.

**Examples** include Druva Legal Hold Automation, Exterro Legal Hold, Logikcull Legal Hold, Relativity Legal Hold, DISCO Legal Hold, Everlaw Legal Hold, Microsoft Purview Legal Hold, Onna Legal Hold, Zapproved Legal Hold Pro, TotalDiscovery, and Casepoint Legal Hold (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted preservation services, retention policy engines, email archiving with legal hold capabilities, and compliance workflow automation — ideal for legal ops teams, IT administrators, compliance officers, and developers building transparent, vendor-neutral preservation workflows.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS Products](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global legal hold and custodian management software market is estimated at approximately $1.4B to $1.8B, expanding toward $3.5B–$4.2B at a ~10–12% CAGR driven by stringent data governance mandates and cloud-sprawl preservation requirements. The market is **moderately fragmented** rather than winner-take-all, divided between multi-billion-dollar enterprise infrastructure incumbents (e.g., Microsoft, OpenText), specialized eDiscovery platforms (e.g., Relativity, Everlaw, DISCO), and specialized workflow point solutions.

## SaaS Products

| Platform | Company Valuation / Revenue | Starting Pricing Tier | Free Tier Limits / Free Trial | Key Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Purview Legal Hold](https://learn.microsoft.com/en-us/purview/)** | Valuation: ~$3.1T+ (Microsoft)<br>Revenue: ~$245B+ ARR | $12.00/user/mo (Purview Suite add-on over E3) or $60.00/user/mo (Full M365 E5) | 90-day free trial (includes 25 Purview Suite E5 trial licenses) | Native M365 preservation intercepting deletion across Exchange, SharePoint, OneDrive, and Teams with immutable holds [citation:10]. |
| **[TotalDiscovery](https://www.totaldiscovery.com/)** | Valuation: ~$6.2B (OpenText, parent)<br>Revenue: ~$5.25B ARR | $1,500/year (base cloud collection/hold tier; custom enterprise tiers available) | Free standalone Legal Hold & Data Profiler tier (unlimited basic hold tracking/reminders; paid tiers required for data collection/processing) | Cloud-based legal hold, custodian data collection, automated preservation, and ECA workflow solution [citation:13]. |
| **[Relativity Legal Hold](https://www.relativity.com/)** | Valuation: ~$3.6B (backed by ICONIQ)<br>Revenue: ~$235M–$320M ARR | $15.00/GB/month (RelativityOne data volume tier; custom annual contracts) | No self-serve free trial (14-to-30 day guided pilot / POC available upon qualified sales demo) | Integrated legal hold module inside RelativityOne with custodian interview questionnaires, escalations, and defensible audit reporting [citation:7]. |
| **[Druva Legal Hold Automation](https://www.druva.com/)** | Valuation: ~$2.0B (Series H)<br>Revenue: ~$200M+ ARR | $8.00/user/month (Enterprise tier) | 30-day free trial (full cloud data protection and legal hold workflow evaluation) | Cloud data protection platform with Legal Hold APIs for programmatic hold policies, custodian tracking, and WebDAV access [citation:4]. |
| **[Everlaw Legal Hold](https://www.everlaw.com/)** | Valuation: ~$2.0B (Series D)<br>Revenue: ~$80M–$90M ARR | $18.00/GB/month ($3.50/GB/mo archive tier via GSA; commercial hosting ~$18–$35/GB/mo with unlimited user seats) | No public self-serve free trial (14-day guided sandbox pilot via sales demo; free up to 50 GB for qualified "Everlaw for Good" pro-bono matters) | Scheduled renotifications, escalation notices, custodian acknowledgment tracking, and multi-cloud data preservation [citation:9]. |
| **[Logikcull Legal Hold](https://www.logikcull.com/)** | Valuation: >$1.0B (acquired by Reveal / K1)<br>Revenue: ~$40M–$60M ARR | $40.00/GB/month ($400/month minimum active storage; unlimited matters & user seats) | Free Tier available ("Logikcull Hold" offers free automated notice issuing, reminder scheduling, and release workflows; pay-as-you-go applies if ingesting data) | Microsoft 365 preserve-in-place integration, one-click mailbox/OneDrive holds, and multi-matter custodian management [citation:6]. |
| **[Exterro Legal Hold](https://www.exterro.com/)** | Valuation: >$1.0B (Unicorn recapitalization)<br>Revenue: ~$100M–$130M ARR | $49.00/user/month (or custom annual enterprise contract starting ~$10,000/year) | 30-day free trial / evaluation pilot for platform modules upon request; free FTK Imager standalone tool | Enterprise legal hold with automated escalation cadences, custodian questionnaire tracking, and unified eDiscovery oversight [citation:5]. |
| **[Casepoint Legal Hold](https://www.casepoint.com/)** | Valuation: Undisclosed (Acquired by Thoma Bravo, Jan 2025)<br>Revenue: ~$40M–$60M ARR | $1,200/month (modular legal hold platform base subscription; no per-user license fees) | No self-serve free trial (14-day guided trial sandbox available following customized enterprise consultation) | Unified legal hold module with automated communications, custodian tracking, and in-place preservation in a secure environment [citation:14]. |
| **[DISCO Legal Hold](https://www.csdisco.com/)** | Valuation: ~$350M–$400M Market Cap (NYSE: LAW)<br>Revenue: ~$171M TTM ARR | $500/month (base DISCO Hold flat tier; or all-inclusive per-GB processed data plan with unlimited users) | No self-serve free trial (14-day structured POC pilot upon request; free hosting up to 50 GB for approved pro-bono cases) | Cloud legal hold platform with one-click preserve-in-place across M365, Google Vault, Slack, Dropbox, and Box [citation:8]. |
| **[Onna Legal Hold](https://www.onna.com/)** | Valuation: ~$150M–$200M (Series B; $54M raised)<br>Revenue: ~$5M–$10M ARR | $1,000/month (starting tier based on 1 TB data volume; unlimited user licenses) | No self-serve free trial (custom 14-day guided proof-of-concept environment available upon request) | Legal hold and preservation API using JSON Logic queries for custodian/datasource targeting and workspace lifecycle management [citation:11]. |
| **[Zapproved Legal Hold Pro](https://www.zapproved.com/)** | Valuation: Subsumed under Exterro (Acquired 2023; ~$17M venture funding raised)<br>Revenue: ~$15M–$25M ARR | $4,500/year (ZDiscovery baseline subscription tier) | No self-serve free trial (14-to-30 day guided enterprise evaluation sandbox available upon request) | Automated custodian notifications, reminders, escalations, compliance questionnaires, and Office 365 hold automation [citation:12]. |

## Open-Source GitHub Projects

- **[message-retention-guardian](https://github.com/mizcausevic-dev/message-retention-guardian)**  
  Ruby service for retention policy enforcement and legal hold protection with pressure scoring to decide freeze/watch/clear actions on deletion windows, designed for enterprise compliance workflows [citation:1].

- **[OpenArchiver](https://github.com/nimdassdev/OpenArchiver)**  
  Self-hosted email archiving and eDiscovery platform with legal hold capability (TBD) for Google Workspace, Microsoft 365, IMAP, PST, and Mbox sources; includes deduplication, full-text search, and immutable audit trail [citation:2].

### Additional Strong Open-Source Options

- **[Legal Hold Management Tool (Python)](https://github.com/topics/legal-hold)** — Litigation hold management with custodian tracking, automated notices, acknowledgment workflows, and full audit log for defensibility [citation:15].
- **[M365 Purview Operator (TypeScript)](https://github.com/topics/legal-hold)** — Control plane for Microsoft 365 Purview retention policies, disposition quality, and eDiscovery case posture management [citation:15].
- **Retention policy engines** and **compliance workflow automation** libraries for building custom legal hold pipelines.
- **Email archiving** projects (IMAP sync, PST parsing, .eml processing) as foundational components for preservation workflows.

**Frameworks for building custom systems**: Combine **OpenArchiver** for archival ingestion, **message-retention-guardian** for retention/hold enforcement, and **PostgreSQL + Meilisearch** for searchable, auditable preservation stores.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Legal hold tools must comply with applicable litigation, privacy, and data protection regulations; consult legal counsel for defensibility requirements.
- Self-hosted open-source solutions require proper access control, audit logging, and regular validation of preservation integrity.

---

**Made for legal ops teams, IT compliance administrators, e-discovery professionals, and developers building preservation automation.**  
Let's make legal hold management more open, automated, and defensible.

## ⭐ Star History

<a href="https://star-history.com/#ishandutta2007/Awesome-Automated-Legal-Hold-Custodian-Management&Timeline" align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/ishandutta2007_Awesome-Automated-Legal-Hold-Custodian-Management_growth.svg">
    <img alt="Star History Chart" src="assets/ishandutta2007_Awesome-Automated-Legal-Hold-Custodian-Management_growth.svg">
  </picture>
</a>
