# soclogix-threat-data
Public threat intelligence feeds and indicators of compromise (IOCs) curated by the SOClogix SOC. Designed for automation, detection engineering, and defensive security operations.

# SOClogix Threat Feeds
Publicly available threat intelligence feeds curated and maintained by the **SOClogix Security Operations Center (SOC)**.

This repository provides **open, machine-consumable threat data** intended to support detection engineering, security operations, research, and defensive automation.

---

## What This Repository Contains

This repo hosts **public threat intelligence artifacts**, including but not limited to:

- Indicators of Compromise (IOCs)
  - IP addresses
  - Domains
  - URLs
  - File hashes (MD5, SHA1, SHA256)
- Threat signal datasets
- Curated blocklists and watchlists
- Detection-enrichment reference data

All content is designed to be **automation-friendly** and **safe for public use**.

---

## Data Scope & Philosophy

- **Defensive use only**
- **No customer data**
- **No proprietary or sensitive intelligence**
- **No attribution to specific victims**
- No active exploitation tooling
- No offensive tradecraft

These feeds are intended to **augment existing security controls**, not replace commercial intelligence platforms.

---

## Repository Structure

soclogix-threat-feeds/
├── feeds/
│ ├── ip/
│ ├── domain/
│ ├── url/
│ ├── hash/
│ └── misc/
├── schemas/
├── examples/
└── metadata/

The Folder structure may evolve over time as new feed types are added.

---
## Update Cadence

- Feeds are updated on a **regular rolling basis**
- Update frequency varies by feed type and source reliability
- Each feed includes metadata indicating:
  - Last updated timestamp
  - Source type
  - Confidence or severity (when applicable)

---

## Formats

Feeds may be published in one or more of the following formats:

- `CSV`
- `JSON`
- `STIX 2.x`
- Plain text (`.txt`)

Each feed directory includes format-specific notes where applicable.

---

## Intended Use Cases

- SIEM ingestion
- SOAR workflows
- EDR enrichment
- Firewall / DNS blocklists
- Detection engineering
- Research and analysis

---

## Disclaimer

All data is provided **“as-is” without warranty of any kind**.

SOClogix makes no guarantees regarding:
- Completeness
- Accuracy
- Timeliness
- Fitness for a particular purpose

Consumers of this data are responsible for **validating and testing** feeds before production use.

---

## 📜 License

Unless otherwise stated, content in this repository is released under the **Apache License 2.0**.

See the [LICENSE](LICENSE) file for full details.

---

## Contributions

At this time, this repository is **read-only**.

Community feedback is welcome via:
- GitHub Issues
- Pull Requests (by request only)

Contact us if you believe a feed requires correction or removal.

---

## About SOClogix

**SOClogix** is a managed security services provider (MSSP) delivering 24/7 SOC operations, detection engineering, and incident response for organizations worldwide.

🔗 https://www.soclogix.com

---

## 📫 Contact

For questions, concerns, or responsible disclosure:

📧 security@soclogix.com
