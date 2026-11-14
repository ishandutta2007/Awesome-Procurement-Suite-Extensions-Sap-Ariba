# Awesome-Procurement-Suite-Extensions-Sap-Ariba

# Awesome Procurement Suite Extensions (SAP Ariba)

> A curated list of top Procurement Suite Extensions and integration platforms for SAP Ariba — both SaaS/Hosted commercial solution extensions and open-source alternatives for extending procurement workflows, contract intelligence, and source-to-pay connectivity.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Icertis Contract Intelligence for SAP Ariba](#icertis-contract-intelligence-for-sap-ariba)
  - [Coupa App Marketplace](#coupa-app-marketplace)
  - [JAGGAER Connect](#jaggaer-connect)
  - [Ivalua Integration Hub](#ivalua-integration-hub)
  - [Tipalti Connect](#tipalti-connect)
  - [Zycus Merlin Agentic Platform](#zycus-merlin-agentic-platform)
  - [Basware P2P](#basware-p2p)
- [Open-Source Software](#-open-source-software)
  - [ITK Lite 4 Procurement (SAP-samples)](#itk-lite-4-procurement-sap-samples)
  - [BTP Procurement Data Extractor (SAP-samples)](#btp-procurement-data-extractor-sap-samples)
  - [Tail Spend Management (SAP-samples)](#tail-spend-management-sap-samples)
  - [Ariba Extensibility Samples (SAP-samples)](#ariba-extensibility-samples-sap-samples)
  - [OpenProcurement](#openprocurement)
  - [Oxalis-NG](#oxalis-ng)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Procurement Suite Extensions for SAP Ariba. These are not open-source but are included as reference points for feature comparison.

### Icertis Contract Intelligence for SAP Ariba
**Type:** SAP Solution Extension for contract lifecycle management
Icertis is SAP's **only Solution Extension (SolEx) partner for CLM**, providing a strategically aligned, SAP premium-certified platform rather than just an integration [citation:25]. The joint solution is available in **Premium and Premium Plus editions** for contract visibility, automation, and AI-powered insights. Contract intelligence is natively embedded in the SAP UX, enabling authoring, redlining, insights, and obligation tracking across the contract lifecycle. The next step integrates contract intelligence into SAP's next-generation source-to-pay suite, unlocking agentic contracting within procurement workflows [citation:25].
**Best for:** SAP-centric enterprises wanting a certified, SAP-embedded CLM extension with AI-native contracting capabilities and a roadmap aligned with SAP's source-to-pay evolution.

### Coupa App Marketplace
**Type:** Partner ecosystem for procurement and spend management
Coupa's App Marketplace provides certified integrations that extend Coupa's spend management capabilities. Listings include **Spendflo** for AI-powered SaaS negotiation, **Torii** for SaaS contract visibility, **Pactum AI** for autonomous purchase request negotiations, **Fairmarkit** for tail spend sourcing automation, and **CrossConnect** connectors for Sage Intacct, QuickBooks Online, and Workday [citation:18][citation:26]. The marketplace also includes **MuleSoft Connector by AcquisLink** for streamlined enterprise integration development [citation:26].
**Best for:** Coupa customers wanting pre-built, certified integrations that extend procurement workflows into finance, SaaS management, and supplier negotiation without custom development.

### JAGGAER Connect
**Type:** ERP integration and source-to-pay connectivity
JAGGAER Connect enables integration between JAGGAER's Source-to-Pay solutions and core systems like ERP, HCM, and finance platforms. It provides **prebuilt ERP connectors** for Oracle, SAP, NetSuite, and Ellucian via JAGGAER Link, reducing reliance on IT for custom integrations [citation:19]. The platform includes open, standards-based APIs for real-time data exchange and an **Infrastructure as a Service (IaaS)** offering for high availability and scalability. JAGGAER positions Connect as reducing the cost of maintaining point-to-point integrations while enabling a unified procurement data environment [citation:19].
**Best for:** Organizations using JAGGAER wanting standardized, prebuilt ERP connectors with reduced IT burden and a scalable integration framework.

### Ivalua Integration Hub
**Type:** Unified integration platform with multi-ERP and AI agent support
Ivalua's Integration Hub provides prebuilt connectors and templates for SAP S/4HANA, ECC, Oracle, Microsoft Dynamics, Workday, and more, alongside supplier intelligence from Dun & Bradstreet and e-signature via DocuSign [citation:30]. A key differentiator is **Model Context Protocol (MCP) support** in both directions: Ivalua's IVA agent can call external MCP servers, and external AI agents can call Ivalua through a hosted MCP server, governed by user permissions [citation:30]. The platform supports multi-ERP integration on a single Ivalua instance, keeping procurement running through S/4HANA migrations and acquisitions. EAI, ETL, and API flows are configured in the same platform without a second integration license [citation:30].
**Best for:** Enterprises with complex, multi-ERP landscapes wanting governed integration with bidirectional AI agent connectivity and no additional integration platform licensing.

### Tipalti Connect
**Type:** Global payables automation and supplier onboarding
Tipalti Connect streamlines supplier onboarding, invoice processing, mass payments, tax compliance, and financial reconciliation. The platform provides pre-built integrations and APIs that extend ERP workflows, with data automatically synced across payables, procurement, expenses, and corporate cards [citation:28]. Celigo's integrator.io documents a Tipalti connection using OAuth 2.0 with PKCE or client credentials, supporting both Production and Sandbox environments [citation:20].
**Best for:** Finance teams wanting to extend procurement into global payables automation with supplier tax compliance and payment reconciliation.

### Zycus Merlin Agentic Platform
**Type:** Source-to-pay suite with agentic AI
Zycus provides an organically built Source-to-Pay platform powered by **Agentic AI**, with modules spanning intake, procure-to-pay, source-to-contract, and procurement orchestration [citation:21]. **Merlin Intake** integrates with Microsoft Teams for guided procurement, claiming 70% faster request processing. The platform includes **Merlin Agentic Platform** with autonomous AI agents, and **Zycus AppXtend** for customized apps via Platform-as-a-Service [citation:21]. Zycus was recognized as a Customers' Choice in the 2025 Gartner Peer Insights Voice of the Customer for Source-to-Pay Suites [citation:29].
**Best for:** Organizations wanting a natively built S2P suite with agentic AI embedded across intake, sourcing, contracting, and payables.

### Basware P2P
**Type:** E-invoicing and purchase-to-pay network
Basware provides cloud-based e-invoicing and purchase-to-pay automation, with REST APIs for submitting and receiving electronic invoices across **70+ formats**, managing purchase orders, processing accounts payable, and accessing network transaction data [citation:23]. The Basware Network connects buyers and suppliers globally through a single integration point with automatic format conversion. APIs include P2P (accounts payable, procurement, master data), Network (e-invoice send/receive), Vault (document archiving), and SmartPDF (invoice capture) [citation:23].
**Best for:** Global enterprises needing e-invoicing compliance across 70+ formats with a single supplier network integration point.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Procurement Suite Extensions and integration tools for SAP Ariba. The open-source ecosystem is **anchored by SAP's own sample repositories** for Ariba extensibility, alongside public-sector procurement standards.

### ITK Lite 4 Procurement (SAP-samples)
**Stack:** SAP BTP CAP / JavaScript / PostgreSQL | **License:** Apache-2.0
ITK Lite 4 Procurement is an open-source SAP BTP CAP application developed as an **alternate solution to replace the SAP Ariba Integration Toolkit (ITK)**, which reached end of support on December 31, 2023 [citation:3]. It connects SAP Ariba solutions with third-party systems via **SAP File Transfer Protocol (SFTP)**, exchanging master, transactional, and spend data through CSV file upload and download. The application requires SAP Credential Store, SAP HANA Cloud DB (or PostgreSQL on BTP), Application Logging Service, Job Scheduling Service, and Cloud Foundry Runtime. Deployment uses `npm run mta:package:deploy` [citation:3].
**Best for:** Organizations needing a supported replacement for the deprecated Ariba ITK to integrate non-SAP ERP systems via SFTP, accepting the SAP BTP infrastructure requirements.

### BTP Procurement Data Extractor (SAP-samples)
**Stack:** SAP BTP CAP / JavaScript | **License:** Apache-2.0
The BTP Procurement Data Extractor retrieves **SAP Ariba Cloud Services data through standard APIs** and captures it into a BTP database for easy access in extensibility and integration scenarios [citation:16]. It is part of an SAP Discovery Center mission for extracting Ariba data through standard APIs, intended as a reference for customers building internal applications. The repository includes deployment instructions for BTP Cloud Foundry [citation:16].
**Best for:** Teams wanting a working reference for extracting Ariba data into BTP for custom analytics or integration, accepting that it is a sample mission component rather than a production product.

### Tail Spend Management (SAP-samples)
**Stack:** SAP BTP CAP / JavaScript | **License:** Apache-2.0
Tail Spend Management is an open-source BTP CAP application addressing tail spend challenges that are harder to control and less visible than core procurement [citation:11]. It provides **Preferred Supplier Management**, **Mapping Regions and Commodity Codes to Supplier**, and **Auto RFP Event Rule Management** for ERP demands. The project is positioned as an alternative to current quote automation using SAP Ariba for tail spend management, with the goal of consolidating suppliers, negotiating better prices, and reducing administrative burden [citation:11].
**Best for:** Procurement teams wanting a reference implementation for automating tail spend RFQ events and preferred supplier management within the SAP BTP ecosystem.

### Ariba Extensibility Samples (SAP-samples)
**Stack:** Jupyter Notebook / Various | **License:** Apache-2.0
The Ariba Extensibility Samples repository is a **one-stop source for SAP Ariba developers**, containing code samples, links to publicly available content, and a list of resources for extending Ariba capabilities [citation:24]. Topics include **APIs** (code samples for communicating with Ariba APIs), **Connectivity with SAP Cloud Connector**, and **Integration with other SAP Products** (SAP Cloud Platform Integration, Data Intelligence, Analytics Cloud, HANA Cloud). The repository is public and open to community contributions [citation:24].
**Best for:** SAP Ariba developers wanting a curated collection of code samples and learning resources for extending Ariba using various SAP products and programming languages.

### OpenProcurement
**Stack:** Python / (Check repository) | **License:** Open Source
OpenProcurement is an open-source procurement platform foundation for **transparent tendering, supplier trust, bid evaluation, contract awards, and auditable public-sector workflows** [citation:4]. It is listed among GitHub's procurement-system topic repositories, with a focus on public-sector procurement transparency. The platform supports e-procurement workflows aligned with open standards, making it relevant for organizations building Ariba-adjacent public procurement infrastructure.
**Best for:** Public-sector organizations and procurement platforms wanting an open-source foundation for transparent, auditable tendering workflows.

### Oxalis-NG
**Stack:** Java | **License:** Open Source
Oxalis-NG is an open-source implementation of the **OpenPeppol AS4 profile**, providing the interoperability layer for Peppol eDelivery [citation:12]. It is part of the broader e-procurement standards ecosystem, enabling secure document exchange between procurement systems. While not Ariba-specific, it is a foundational building block for European e-invoicing and e-procurement compliance.
**Best for:** Developers building Peppol-compliant e-procurement integrations who need a proven AS4 implementation, particularly for European public procurement.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Ariba-Specific | Integration Method | Self-Hosted | Best For |
|----------|---------|-------|----------------|---------------------|-------------|----------|
| **Icertis** | Proprietary | Cloud | ✅ SolEx | Embedded in SAP UX | ❌ | SAP-certified CLM extension |
| **Coupa Marketplace** | Proprietary | Cloud | ❌ (Coupa) | Certified partner apps | ❌ | Coupa ecosystem extensions |
| **JAGGAER Connect** | Proprietary | Cloud | ❌ (JAGGAER) | Prebuilt ERP connectors | ❌ | JAGGAER ERP integration |
| **Ivalua Hub** | Proprietary | Cloud | ❌ (Ivalua) | Multi-ERP + MCP | ❌ | Multi-ERP + AI agent integration |
| **ITK Lite 4** | Apache-2.0 | BTP CAP | ✅ ITK replacement | SFTP + CSV | ✅ (BTP) | Ariba ↔ non-SAP ERP |
| **BTP Data Extractor** | Apache-2.0 | BTP CAP | ✅ Data extraction | Standard Ariba APIs | ✅ (BTP) | Ariba data → BTP |
| **Tail Spend Mgmt** | Apache-2.0 | BTP CAP | ✅ Tail spend | Auto RFP rules | ✅ (BTP) | Tail spend automation |
| **Ariba Ext. Samples** | Apache-2.0 | Various | ✅ Developer samples | APIs, Cloud Connector | ✅ | Ariba developer learning |
| **OpenProcurement** | Open Source | Python | ❌ | Public tendering | ✅ | Public-sector transparency |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Procurement Suite Extension or SAP Ariba integration tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem for **SAP Ariba extensions** is **anchored by SAP's own sample repositories**, which provide production-quality reference implementations for integration (ITK Lite 4), data extraction (BTP Procurement Data Extractor), and tail spend automation [citation:3][citation:11][citation:16]. These are samples rather than products, but they are maintained by SAP and Apache-2.0 licensed, making them viable starting points for custom Ariba-adjacent development. Commercial solution extensions like Icertis and Ivalua remain far more capable for production-grade contract intelligence and multi-ERP integration [citation:25][citation:30].

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
