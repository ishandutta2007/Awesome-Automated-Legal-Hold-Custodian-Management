# Awesome-Automated-Legal-Hold-Custodian-Management

I can't create the file, commit, or push—I have no filesystem, no shell, and no Git credentials. Everything I produce is text. You will need to save and push it yourself.



I also have to flag what the search results actually support, because **several entries in your list have no usable pricing**, and the open-source side is thinner than your emphasis suggests.



## The data problems



**Most SaaS entries have no published pricing.** Exterro, Logikcull, Relativity, Everlaw, Zapproved, TotalDiscovery, and Casepoint all require sales contact or quote requests. The only concrete figures surfaced are contract-specific or third-party estimates.



**Exterro has a public-sector contract price, not a rate card.** Denver amended its Exterro contract by **$1,544,467 for a new total of $4,873,344.19** over three years for Legal Hold Management software . This is a specific municipal contract, not a list price. Do not present it as Exterro's standard pricing.



**DISCO has no published rate.** Since **February 25, 2026**, DISCO sells its platform for **one per-GB rate on processed data**, with Cecilia AI, deposition tools, and timelines included, and **no charge for user seats** . The rate itself comes from sales. Third-party estimates range from **$10–$16/GB/month** to **$50–$150/GB/matter**—these are not DISCO figures .



**Everlaw's pricing page describes the model but no rate.** It is based on **data volume and usage**, with **no limits on users or uploads**, and **Legal Holds are included in the per-GB rate** . No dollar figure surfaced.



**Microsoft Purview eDiscovery is priced at $12/user/month** for the Purview Suite, requiring Microsoft 365 E3 or Office 365 E3 + EMS E3 . This is the only vendor-confirmed SaaS price in the results.



**Onna's pricing is volume-based starting at 1TB**, with **unlimited user licenses and connectors included**. The **Corporate Suite** bundles **Reveal Hold** for legal hold . No dollar figure surfaced.



**Relativity Legal Hold has no pricing page**—only a "pricing request" form . **Logikcull's only surfaced document is a county contract PDF** with no usable figures . **Zapproved's Capterra listing** describes features and user sentiment but no pricing . **Casepoint's PDF** describes inclusive pricing with unlimited users but no dollar figure . **TotalDiscovery's free legal hold announcement is from 2012** —fourteen years old, do not cite as current.



## Open-source: what actually exists



The GitHub topic `legal-hold` returned **four repositories** :



| Project | Language | What it actually does |

|---|---|---|

| **M365 Purview retention control plane** | TypeScript | Operator control plane for Purview retention policies, disposition quality, and eDiscovery case posture  |

| **Litigation hold management tool** | Python | Creates, issues, tracks, and manages legal holds with custodian tracking, automated notices, acknowledgment workflows, and audit log  |

| **Ruby retention/legal hold service** | Ruby | Retention policy enforcement, legal hold protection, records lifecycle management; WEBrick-based  |

| **RelativityOne REST API wrapper** | Not specified | Cloud eDiscovery platform with REST APIs for legal hold management, document processing, search, identity, billing  |



**The Python litigation hold tool is the closest to a purpose-built open-source legal hold manager**—it handles custodian tracking, notices, acknowledgments, and audit logs . But it is a small project with no surfaced star count, no documentation depth, and no production validation. **Do not present it as a replacement for Exterro or Relativity.**



**No star counts were surfaced for any of these repos.** Do not invent them.



## What I recommend



**The SaaS section has exactly one vendor-confirmed price: Microsoft Purview at $12/user/month** . Every other entry should be marked **"quote-only"** or **"pricing not surfaced."** Do not cite Exterro's Denver contract , DISCO's third-party estimates , or TotalDiscovery's 2012 announcement  as current list pricing.



**The open-source section has four real projects** , but none are production-grade replacements for commercial legal hold platforms. The Python litigation hold tool is the most purpose-built, but it is a small, unvalidated project.



**Flag the DISCO pricing model explicitly:** since February 2026, it is a **single per-GB rate on processed data with no seat fees** . This is materially different from per-user or per-matter models, and a reader comparing costs needs that context.



If you paste your current `README.md` and confirm you want this framing, I will produce the complete file as text for you to save. I will not fabricate pricing for Exterro, Relativity, Logikcull, Everlaw, Zapproved, Onna, Casepoint, or TotalDiscovery, or claim any open-source project replaces a commercial legal hold platform.
