# Awesome-Data-Subject-Access-Request-DSAR-Privacy

## Top Data Subject Access Request (DSAR) & Privacy Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on DSAR Automation, Privacy Request Orchestration & GDPR Compliance Workflows*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Subject Access Request (DSAR) & Privacy Management**. These tools help organizations receive, verify, and fulfill data subject requests—access, erasure, rectification, portability, and objection—within regulatory deadlines (GDPR Art. 12 mandates one month), while maintaining audit trails and managing consent across disparate data silos.

**Examples** include OneTrust, TrustArc, Securiti.ai, BigID, Ketch, DataGrail, Transcend, Osano, Mine PrivacyOps, and WireWheel (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted DSAR automation, open-source privacy request engines, and community-driven consent management—ideal for organizations seeking data sovereignty and predictable costs over per-request or per-record SaaS pricing. The open-source DSAR landscape is **genuinely nascent but functional**: most projects are early-stage (2026 releases) with narrow scope, and **no open-source project matches the integration breadth of DataGrail or Transcend**. The practical path is composing open-source DSAR engines with custom connectors and self-hosted consent platforms.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[OneTrust](https://www.oneTrust.com/)** | Enterprise privacy management with DSAR automation, data mapping, consent, and assessment modules. **No self-serve pricing**—subscriptions negotiated per module, scaled by headcount, entity count, and geography. Trial tenants are sales-provisioned, not self-serve. | Quote-only (module-based enterprise) | No free tier; trial provisioned via sales |
| **[TrustArc](https://www.trustarc.com/)** | Modular privacy platform with Privacy Rights Automation for DSAR fulfillment. **Implementation fees $10,000–$50,000+**; professional services add **$20,000–$100,000+ annually**. Small deployments (single module) often see **$30,000–$75,000/year** including implementation; mid-market multi-module **$100,000–$250,000/year**. | ~**$30,000–$75,000/year** (single module, incl. implementation) | No free tier; demo via sales |
| **[Securiti.ai](https://securiti.ai/)** | Unified Data Command Center with DSAR automation, data mapping, and consent. **Quote-only pricing** with no public tiers—expect custom enterprise quotes based on data volume and connectors. Acquired by Veeam for **$1.725B** in 2025. | Quote-only (enterprise, volume-based) | No free tier; demo via sales |
| **[BigID](https://bigid.com/)** | Data intelligence platform with DSAR fulfillment across 100+ data sources. **C4 Discovery Foundation Package required**: **$525,000 one-time** (3-year term, >100 data sources). Purview integration: **$35,000/year** or **$70,000–$105,000 one-time**. | **$525,000** (C4 Foundation, 3-year) | No free tier; enterprise sales only |
| **[Ketch](https://www.ketch.com/)** | Privacy UX platform with transparent self-serve pricing. **Free tier includes consent management up to 5k visitors/month**. Starter **$150/month** (30k visitors); Plus **$499/month** (100k visitors). **DSR automation is Pro-tier only** (custom pricing). | Free: $0 (5k visitors/month); Starter: **$150/month**; Plus: **$499/month** | **Free**: consent management up to 5k visitors/month; DSAR requires Pro tier |
| **[DataGrail](https://www.datagrail.io/)** | Privacy automation with 2,000+ integrations for DSAR fulfillment. **Implementation quoted separately: $10,000–$40,000+**. Small deployments (<1M data subjects, <500 DSARs/year): **$30,000–$70,000/year**. Multi-year discounts of **15–30%**. | ~**$30,000–$70,000/year** (small deployments) | No free tier; demo via sales |
| **[Transcend](https://transcend.io/)** | Privacy infrastructure platform with DSAR automation and data discovery. Positioned as a modern alternative to legacy privacy suites. | Quote-only | No free tier; demo via sales |
| **[Osano](https://www.osano.com/)** | Privacy platform with consent management and data subject rights. Software Advice lists starting price at **$119.99/month** with free trial and free version available. | **$119.99/month** (Software Advice) | **Free trial** and **free version** available |
| **[Mine PrivacyOps](https://www.mineprivacy.com/)** | Privacy operations platform with data mapping, DSAR automation, and consent. **Free tier for basic data mapping**. Paid plans start around **$8,000/year**. | ~**$8,000/year** (paid tier) | **Free tier**: basic data mapping |
| **[WireWheel](https://www.wirewheel.io/)** | Privacy management platform with DSAR automation, data mapping, and vendor risk. Positioned for mid-market and enterprise. | Quote-only | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Fides (Ethyca)](https://github.com/ethyca/fides)** | [![Stars](https://img.shields.io/github/stars/ethyca/fides?style=social&color=white)](https://github.com/ethyca/fides/stargazers) | **The most mature open-source privacy engineering platform for DSAR orchestration.** ~382 GitHub stars. Open-source privacy-as-code platform for managing data privacy requests **in your runtime environment** and enforcing privacy regulations in code. Connects directly to disparate databases to fulfill access and erasure requests. **Fidesops was deprecated and merged into Fides**—use Fides, not Fidesops. Apache 2.0. Active development (3,396 commits over 1,095 days) . |
| **[inithq/dsar](https://github.com/inthhq/dsar)** | [![Stars](https://img.shields.io/github/stars/inthhq/dsar?style=social&color=white)](https://github.com/inthhq/dsar/stargazers) | **Open-source standard for handling DSAR requests programmatically.** Developer-first Data Subject Access Request engine. Separates authentication into machine access (API keys for CLI/SDK/automation) and trusted host identity (host apps authenticate end users, then project identity into DSAR). Keeps end-user login in the host product while DSAR focuses on tenant scoping and route authorization. Apache 2.0. Recently active (Sept 2026) . |
| **[privacy-dsar-mcp-server](https://github.com/AiAgentKarl/privacy-dsar-mcp-server)** | [![Stars](https://img.shields.io/github/stars/AiAgentKarl/privacy-dsar-mcp-server?style=social&color=white)](https://github.com/AiAgentKarl/privacy-dsar-mcp-server/stargazers) | **MCP server for GDPR privacy compliance and DSAR management**—open-source alternative to Transcend MCP. Manages DSARs with **automatic 30-day deadline tracking (GDPR Art. 12)**. Tools for creating/listing/updating DSARs, checking GDPR compliance (15 rules, A–F scoring), registering Article 30 data processing activities, and a privacy officer dashboard. **Data stored locally** (`~/.privacy_dsar_store.json`)—no external services required. MIT. Early-stage (v0.1.0, April 2026) . |
| **[gdprkit](https://github.com/cognis-digital/gdprkit)** | [![Stars](https://img.shields.io/github/stars/cognis-digital/gdprkit?style=social&color=white)](https://github.com/cognis-digital/gdprkit/stargazers) | **Self-hosted GDPR/CCPA DSAR, RoPA, and cookie-consent toolkit.** CLI that tracks data-subject access requests and **deadlines from a JSON file**. Also validates Record of Processing Activities (Art. 30) and audits cookie-consent compliance (ePrivacy Art. 5(3)). Outputs table, JSON, or SARIF for CI gating. Runs offline. Python package. Early-stage (v0.1.0, June 2026) . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[ConsentOS](https://github.com/consentos/consentos)** | [![Stars](https://img.shields.io/github/stars/consentos/consentos?style=social&color=white)](https://github.com/consentos/consentos/stargazers) | **Self-hosted consent management platform (not DSAR-specific, but critical privacy infrastructure).** Comparable to OneTrust or Cookiebot but deployed on your own infrastructure. **Your consent records stay in your database.** No per-domain fees. Covers IAB TCF v2.3, Google Consent Mode v2, GPP v1, auto-blocking, cookie scanner (2,200+ patterns), dark pattern detection, and compliance checks for GDPR, CNIL, CCPA/CPRA, ePrivacy, and LGPD. Elastic License 2.0 (source-available, self-host indefinitely). Active (April 2026) . |
| **[Klaro](https://github.com/Ressmann/privacy-manager)** | [![Stars](https://img.shields.io/github/stars/Ressmann/privacy-manager?style=social&color=white)](https://github.com/Ressmann/privacy-manager/stargazers) | **Simple, free, open-source consent manager for websites.** GDPR and ePrivacy compliant. **57 kB minified+gzipped** (includes styles and translations). Multilingual (17 languages). Ensures no third-party apps execute without consent, **even when JavaScript is disabled or Klaro itself is blocked**. Easy integration with a JS snippet and config. MIT-style free license . |

**Frameworks for building custom systems**: The open-source DSAR path is **engine + connectors + evidence**. Use **Fides** for runtime privacy request orchestration connected directly to your databases (the most mature option), **gdprkit** for CLI-based deadline tracking and RoPA validation, and **privacy-dsar-mcp-server** for a lightweight MCP-driven DSAR tracker with local storage. For consent management, **ConsentOS** provides self-hosted compliance with no per-domain fees. **No open-source project offers the 2,000+ pre-built integrations of DataGrail**—expect to build custom connectors for your specific data silos.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- DSAR platforms process personal data and regulatory deadlines; enforce role-based access, audit logging, and compliance with applicable data protection regulations. **Missed deadlines (GDPR Art. 12: one month) can trigger regulatory fines.**
- **Open-source DSAR tooling is early-stage and narrow in scope.** Fides is the most mature option (~382 stars, active development since 2021) but requires engineering effort to connect to your data sources . privacy-dsar-mcp-server and gdprkit are both **v0.1.0 releases from 2026**—functional for tracking and compliance checking, but not production-hardened for high-volume DSAR fulfillment. **Commercial DSAR pricing is quote-only and expensive**: DataGrail starts at **$30,000–$70,000/year** for small deployments , TrustArc at **$30,000–$75,000/year** , and BigID requires a **$525,000 Foundation package** . Ketch is the notable exception with a **free consent tier** and transparent self-serve pricing, though DSAR automation requires the Pro tier . **Validate your DSAR workflow against legal counsel before relying on any tool for regulatory compliance.**

---

**Made for privacy officers, DPOs, compliance analysts, and developers building privacy-preserving infrastructure.**  
Let's make DSAR and privacy management more open, transparent, and deadline-safe.
