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

| Product | Description | Starting Tier Price | Free Tier / Free Trial Limits |
|---|---|---|---|
| **[OneTrust](https://www.oneTrust.com/)** | Enterprise privacy management with DSAR automation, data mapping, consent, and assessment modules. Negotiated per module and scaled by headcount/entities. | **$10,000/year** (baseline enterprise package) | **14-day sales-guided POC/trial** (limited evaluation environment; no self-serve free forever plan) |
| **[TrustArc](https://www.trustarc.com/)** | Modular privacy platform with Privacy Rights Automation for DSAR fulfillment. Single module deployments start around $30,000/year. | **$30,000/year** (single module baseline deployment) | **30-day standard trial period** (per TrustArc Master Terms; no self-serve free forever plan) |
| **[Securiti.ai](https://securiti.ai/)** | Unified Data Command Center with DSAR automation, data mapping, and consent orchestration. | **$50,000/year** (median entry-level contract via marketplace/sales) | **14 to 30 days guided POC** (scoped per data connectors; freemium entry available for basic privacy center) |
| **[BigID](https://bigid.com/)** | Data intelligence platform with DSAR fulfillment across 100+ enterprise data sources. | **$525,000** (C4 Discovery Foundation Package, 3-year term) | **14 to 30 days scoped enterprise POC** (no self-serve free forever plan) |
| **[Ketch](https://www.ketch.com/)** | Privacy UX and programmatic data rights automation platform. | **$0/month** (Free consent tier) / **$150/month** (Starter tier) | **Free forever plan**: up to 5,000 monthly visitors (consent management; automated DSAR requires Pro tier) |
| **[DataGrail](https://www.datagrail.io/)** | Privacy management and request fulfillment with 2,000+ pre-built SaaS connectors. | **$30,000/year** (entry-level deployment for <1M data subjects and <500 DSARs/yr) | **Custom sales-scoped POC** (typically 14–30 days upon qualification; no self-serve free forever plan) |
| **[Transcend](https://transcend.io/)** | Privacy infrastructure platform providing automated data subject request orchestration and discovery. | **$10,000/year** (entry-level base subscription) | **30-day standard evaluation/POC** (per Transcend Online Services Agreement Section 1.5; no free forever plan) |
| **[Osano](https://www.osano.com/)** | Data privacy platform featuring cookie consent management, data mapping, and DSAR workflows. | **$0/month** (Developer/Solo tier) / **$199/month** (Plus plan) | **Free forever plan**: 1 user, 1 domain, up to 5,000 monthly visitors; **30-day free trial** available for Plus plan |
| **[Mine PrivacyOps](https://www.mineprivacy.com/)** | Privacy operations platform (MineOS) for continuous data mapping and automated DSAR fulfillment. | **$0/month** (Free tier) / **$8,000/year** (paid tier entry) | **Free forever plan**: up to 2 seats and 5 evidence-backed DSR requests per month (full API automation requires paid plan) |
| **[WireWheel](https://www.wirewheel.io/)** | Privacy management and compliance orchestration platform covering DSAR fulfillment and vendor risk. | **$12,000/year** (entry-level small-business package via AWS Marketplace) | **30-day free trial** (for UPCP/consent products; guided POC for full enterprise DSAR platform) |

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
