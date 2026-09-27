<div align="center">

![Awesome Electronic Batch Records Banner](assets/banner.svg)

# 🧪 Awesome Electronic Batch Records (EBR) 🏭

[![Awesome](https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github)](https://github.com/ishandutta2007/Awesome-Awesome-Awesome)<a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
<a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>

**Curated List of Electronic Batch Record (EBR) SaaS Platforms, Open-Source Manufacturing Execution Systems (MES) & GxP Compliance Software**

*Focused on Paperless Manufacturing, Batch Traceability, FDA 21 CFR Part 11 / EU Annex 11 Compliance & Review-by-Exception*

**Last updated: September 2026**

</div>

---

## 📌 Overview & Market Context

This repository tracks notable **SaaS platforms** and **open-source projects** for **Electronic Batch Records (EBR)** and **Manufacturing Execution Systems (MES)** in pharmaceutical, biotechnology, and regulated life sciences manufacturing. These software solutions empower teams to replace paper-based master batch records (MBR) with digital workflows that enforce standard operating procedures (SOPs), capture shop-floor data in real time, ensure audit trails, and accelerate batch release.

### 📊 Electronic Batch Record (EBR) Market Dynamics

> **Market Size & Structure**: The global Electronic Batch Record (EBR) software market was valued at **$1.28 Billion in 2025** and is projected to reach **$4.83 Billion by 2035** (growing at a CAGR of **14.3%**). The market is **moderately fragmented**, featuring a mix of massive industrial automation conglomerates (Siemens, Emerson, Rockwell Automation) alongside specialized life-sciences SaaS leaders (Körber PAS-X, MasterControl, Tulip Interfaces). It is not a strict "winner-take-all" sector due to diverse site operational scales, regulatory tiers, and distinct integration needs with legacy ERP and SCADA infrastructure.

### 💡 Open-Source Reality in Regulated Manufacturing
This category is historically commercially consolidated. **No production-ready, turn-key open-source EBR platform exists** that satisfies FDA 21 CFR Part 11 or EU Annex 11 compliance out of the box. Building an open-source solution involves deploying an open-source ERP/MES foundation (such as **Odoo**, **ERPNext**, or **qcadoo MES**), coupled with document control engines (**Mayan EDMS**, **Alfresco**), process automation engines (**ProcessMaker**), and IoT gateways (**Node-RED**), followed by rigorous custom validation (IQ/OQ/PQ), electronic signatures, and audit trail enforcement.

---

## 📋 Table of Contents

- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source Repositories & Foundations](#-open-source-repositories--foundations)
- [🛠️ How to Contribute](#️-how-to-contribute)
- [⚠️ Disclaimer](#️-disclaimer)
- [📈 Star History](#-star-history)
- [💖 Support & Acknowledgments](#-support--acknowledgments)

---

## 🏢 SaaS & Commercial Platforms

| Platform 🚀 | Starting Pricing 💰 | Free Tier / Free Trial Limits 🎁 | Company Size (Revenue / Valuation) 🏛️ | Description & Key Features 📝 |
| :--- | :--- | :--- | :--- | :--- |
| **[Siemens Opcenter Execution Pharma](https://www.siemens.com/)** | ~$35,000 / year (Enterprise deployment) | 30-Day Free Trial (Opcenter X / Scheduling Standard) | **~$82.4 Billion / €80B+** (Siemens AG FY2025 Revenue) | Dedicated pharmaceutical MES offering paperless manufacturing, Master Batch Record (MBR) creation, and native DCS/SCADA integration. Reduces batch deviations and revision time by up to 75%. |
| **[Emerson Syncade](https://www.emerson.com/)** | ~$30,000 / year (Base module licensing) | 14-Day Guided Demo Access (No unguided free trial) | **~$18.0 Billion** (Emerson Electric FY2025 Net Sales) | Smart operations management suite for life sciences. Features forced sequencing, e-signatures, barcode lot verification, and immutable audit trail histories for 21 CFR Part 11 compliance. |
| **[FactoryTalk PharmaSuite](https://www.rockwellautomation.com/)** | ~$28,000 / year (Site license tier) | 14-Day Enterprise Sandbox Demo (No public free trial) | **~$8.3 Billion** (Rockwell Automation FY2025 Revenue) | Rockwell Automation’s premier MES designed for biopharma. Built on ISA-88/95 standards, featuring Kubernetes container support, review-by-exception dashboards, and NIST cybersecurity alignment. |
| **[Körber PAS-X](https://www.koerber-pharma.com/)** | ~$25,000 / year (PAS-X as a Service entry tier) | Free E-Learning & Training Modules (No software free trial) | **~$3.4 Billion / €3.1B** (Körber Group FY2025 Revenue) | Market-leading pharmaceutical MES spanning raw material receipt to final packaging. Deployed across 200+ workstations per facility with cloud PAS-X on AWS/Azure. |
| **[MasterControl Manufacturing Excellence](https://www.mastercontrol.com/)** | ~$25,000 / year (Annual subscription) | Free Resource Center & Virtual Demos (No free trial) | **~$200+ Million ARR** (Private SaaS Milestone 2025) | Cloud-native MES & eDHR software bringing paperless production control, real-time audit trails, and automated review-by-exception to over 1,100 global life sciences companies. |
| **[Tulip Frontline Operations](https://tulip.co/)** | $1,200 / interface / year (Minimum 10 interfaces) | 30-Day Sandbox Trial (On sales request; no perpetual free tier) | **~$1.2+ Billion Valuation** ($120M+ Raised, Unicorn status) | Composable, low-code frontline operations platform with pre-built EBR and digital logbook templates. Features AI Frontline Copilot, ISA-88 common data models, and CSA-aligned validation. |
| **[Parsec TrakSYS](https://www.parsec-corp.com/)** | $1,999 / month (Base starter package) | 14-Day Guided Demo (No self-serve free trial) | **~$50M - $100M** (Estimated Annual Revenue) | Flexible MES platform for automated weighing & dispensing, recipe management, and EBR tracking. Built around ISA-88 standards for seamless job execution and batch traceability. |

---

## 🔓 Open-Source Repositories & Foundations

Repositories below are sorted by GitHub Stars_Count (Descending) to reflect community traction and adoption.

| Repository 📦 | GitHub_Stars ⭐ | License 📜 | Tech Stack 💻 | Description & Manufacturing Focus 🎯 |
| :--- | :--- | :--- | :--- | :--- |
| **[Odoo](https://github.com/odoo/odoo)** | [![Stars](https://img.shields.io/github/stars/odoo/odoo?style=social&color=white)](https://github.com/odoo/odoo/stargazers) | LGPL-3.0 | Python, JavaScript, PostgreSQL | Full-featured enterprise suite with production MRP, work centers, inventory lot/serial control, and custom electronic signature modules suitable for modular EBR creation. |
| **[ERPNext](https://github.com/frappe/erpnext)** | [![Stars](https://img.shields.io/github/stars/frappe/erpnext?style=social&color=white)](https://github.com/frappe/erpnext/stargazers) | GPL-3.0 | Python (Frappe Framework), MariaDB | Comprehensive open-source ERP with built-in Bill of Materials (BOM), work orders, batch quality inspections, and detailed operational log tracking. |
| **[Node-RED](https://github.com/node-red/node-red)** | [![Stars](https://img.shields.io/github/stars/node-red/node-red?style=social&color=white)](https://github.com/node-red/node-red/stargazers) | Apache-2.0 | Node.js, JavaScript | Low-code flow-based programming environment essential for connecting shop-floor IoT sensors, scales, HMIs, and PLC devices to digital batch record systems. |
| **[Dolibarr ERP CRM](https://github.com/dolibarr/dolibarr)** | [![Stars](https://img.shields.io/github/stars/dolibarr/dolibarr?style=social&color=white)](https://github.com/dolibarr/dolibarr/stargazers) | GPL-3.0+ | PHP, MySQL | Modular ERP and CRM software equipped with manufacturing orders, product batch/lot tracking, and document attachment audit capabilities. |
| **[qcadoo MES](https://github.com/qcadoo/mes)** | [![Stars](https://img.shields.io/github/stars/qcadoo/mes?style=social&color=white)](https://github.com/qcadoo/mes/stargazers) | AGPL-3.0 | Java, Spring, PostgreSQL | Dedicated open-source Manufacturing Execution System tailored for small-to-medium manufacturers with shop-floor execution, material flows, and production schedules. |
| **[Mayan EDMS](https://github.com/mayan-edms/mayan-edms)** | [![Stars](https://img.shields.io/github/stars/mayan-edms/mayan-edms?style=social&color=white)](https://github.com/mayan-edms/mayan-edms/stargazers) | Apache-2.0 | Python, Django | Enterprise document management system providing document versioning, electronic sign-offs, and compliance logging for Master Batch Records (MBR). |
| **[Apache OFBiz](https://github.com/apache/ofbiz)** | [![Stars](https://img.shields.io/github/stars/apache/ofbiz?style=social&color=white)](https://github.com/apache/ofbiz/stargazers) | Apache-2.0 | Java, Gradle | Suite of enterprise applications for manufacturing automation, raw material routing, inventory management, and batch execution logic. |
| **[Joget Workflow](https://github.com/jogetworkflow/jw-community)** | [![Stars](https://img.shields.io/github/stars/jogetworkflow/jw-community?style=social&color=white)](https://github.com/jogetworkflow/jw-community/stargazers) | GPL-3.0 | Java, Low-Code Platform | Open-source low-code platform ideal for rapidly designing compliance-ready batch approval workflows, CAPA forms, and electronic sign-offs. |
| **[ProcessMaker](https://github.com/processmaker/processmaker)** | [![Stars](https://img.shields.io/github/stars/processmaker/processmaker?style=social&color=white)](https://github.com/processmaker/processmaker/stargazers) | AGPL-3.0 | PHP, Laravel, Vue.js | Business Process Management (BPM) suite widely utilized to orchestrate batch record approval routing, deviation reporting, and quality events. |
| **[Manufacturing Ontologies](https://github.com/digitaltwinconsortium/ManufacturingOntologies)** | [![Stars](https://img.shields.io/github/stars/digitaltwinconsortium/ManufacturingOntologies?style=social&color=white)](https://github.com/digitaltwinconsortium/ManufacturingOntologies/stargazers) | MIT | DTDL, W3C WoT, JSON-LD | Digital Twin Consortium reference models implementing ISA-95 (IEC 62264) and ISA-88 standards for digital batch execution and asset modeling. |
| **[openMES](https://github.com/ming-hai/openMES)** | [![Stars](https://img.shields.io/github/stars/ming-hai/openMES?style=social&color=white)](https://github.com/ming-hai/openMES/stargazers) | Open Source | C#, .NET | Reference MES implementation explicitly architected around ISA-88 master batch recipe models and ISA-95 shop floor integration standards. |
| **[iPlusMES](https://github.com/iplus-framework/iPlusMES)** | [![Stars](https://img.shields.io/github/stars/iplus-framework/iPlusMES?style=social&color=white)](https://github.com/iplus-framework/iPlusMES/stargazers) | MIT | Python, FastAPI, React | Modern, lightweight MES framework offering modular shop-floor data collection, process tracking, and RESTful API endpoints. |
| **[Open Source MES (osess)](https://github.com/osess/mes)** | [![Stars](https://img.shields.io/github/stars/osess/mes?style=social&color=white)](https://github.com/osess/mes/stargazers) | MIT | Python, Django | Lightweight Manufacturing Execution System providing core work order tracking, job assignment, and operational logging. |
| **[ERP-MES System](https://github.com/hangxigood/ERP-MES)** | [![Stars](https://img.shields.io/github/stars/hangxigood/ERP-MES?style=social&color=white)](https://github.com/hangxigood/ERP-MES/stargazers) | MIT | Next.js 14, React, MongoDB | Specialized Electronic Batch Records (EBR) system featuring dynamic MBR template builders, version control, role-based access, and action logging. |

---

## 🛠️ How to Contribute

We welcome contributions from manufacturing engineers, life sciences quality managers, and open-source developers!

1. **Fork** the repository.
2. **Add/Edit** entries in `README.md` following the table formats above.
3. Ensure description remains objective and accurate.
4. Create a **Pull Request** detailing your additions.

---

## ⚠️ Disclaimer

- This list is **community-curated** for educational and research purposes.
- Electronic Batch Record (EBR) systems used in commercial drug or device production must comply with strict GxP regulatory requirements including **FDA 21 CFR Part 11** and **EU Annex 11**.
- Open-source platforms require internal validation (IQ/OQ/PQ), custom audit logging, and electronic signature integration prior to production deployment.

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Electronic-Batch-Records&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Electronic-Batch-Records&type=date&legend=top-left)

---

## 💖 Support & Acknowledgments

If you found this repository useful for your pharma engineering, MES evaluation, or digital transformation project, please consider:
- ⭐ **Starring** the repository on GitHub
- 🔀 **Forking** and sharing with colleagues in quality assurance and manufacturing IT
- 📢 Sharing your feedback or opening an issue for missing tools

☕ **Sponsor & Support**: If you would like to support the ongoing maintenance of this awesome list, consider buying a coffee via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).
