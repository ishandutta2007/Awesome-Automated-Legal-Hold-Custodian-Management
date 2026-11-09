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
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Druva Legal Hold Automation](https://www.druva.com/)**  
  Cloud data protection platform with Legal Hold APIs for programmatic policy creation, custodian management, and data access via WebDAV, supporting automated hold workflows at scale [citation:4].

- **[Exterro Legal Hold](https://www.exterro.com/)**  
  Enterprise legal hold solution with automated reminder and escalation rules, custodian acknowledgment tracking, and a matter-centric interface for unified e-discovery project oversight [citation:5].

- **[Logikcull Legal Hold](https://www.logikcull.com/)**  
  Legal hold platform with Microsoft 365 Preserve-In-Place integration, enabling one-click preservation of Exchange mailboxes and OneDrive documents directly from the hold creation workflow [citation:6].

- **[Relativity Legal Hold](https://www.relativity.com/)**  
  Integrated legal hold application within RelativityOne for sending notices, interviewing custodians, automating follow-ups, and generating audit-ready reports on all hold communications [citation:7].

- **[DISCO Legal Hold](https://www.csdisco.com/)**  
  Cloud-based legal hold platform with one-click preserve-in-place across M365, Google Vault, Slack, Dropbox, and Box, plus automated custodian notice/remind/release workflows and defensible audit trails [citation:8].

- **[Everlaw Legal Hold](https://www.everlaw.com/)**  
  Legal holds module with scheduled automatic renotification, escalation notices, periodic reminders, custodian acknowledgment tracking, and support for both internal and external data preservations [citation:9].

- **[Microsoft Purview Legal Hold](https://learn.microsoft.com/en-us/purview/)**  
  Native Microsoft 365 preservation mechanism that intercepts deletion across Exchange, SharePoint, OneDrive, and Teams, overriding standard retention policies until the hold is explicitly released [citation:10].

- **[Onna Legal Hold](https://www.onna.com/)**  
  Legal hold and preservation API with JSON Logic query-based custodian and datasource targeting, job monitoring, and lifecycle management (create, update, finish, delete) for preservation workspaces [citation:11].

- **[Zapproved Legal Hold Pro](https://www.zapproved.com/)**  
  Cloud legal hold software for corporate legal teams with automated workflow for notices, reminders, escalations, custodian questionnaires, and in-place Office 365 hold application [citation:12].

- **[TotalDiscovery](https://www.totaldiscovery.com/)**  
  Cloud-based integrated legal hold, data collection, processing, and ECA solution for corporate legal and IT departments managing investigations and litigation [citation:13].

- **[Casepoint Legal Hold](https://www.casepoint.com/)**  
  Unified eDiscovery platform with legal hold module featuring automated communications, notifications, and custodian management inside a single secure environment [citation:14].

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
