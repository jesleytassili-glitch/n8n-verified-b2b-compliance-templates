# Official n8n B2B Compliance & DevSecOps Workflow Templates (`v1.0.0`)

![Release](https://img.shields.io/github/v/release/jesleytassili-glitch/n8n-verified-b2b-compliance-templates?label=release&color=brightgreen)
![Templates](https://img.shields.io/badge/n8n_Verified_Ready-4_Workflows-FF6D5A)
![APIs](https://img.shields.io/badge/RapidAPI_Hub-@b2bquantapis-0055DA)

Production-grade **n8n automation workflows** with on-canvas Sticky Notes, standard `Header Auth` (`X-RapidAPI-Key`) credentials, JavaScript risk scoring, and conditional escalation gates.

## Included Templates

| # | Workflow Template | Live Public APIs Used | File |
| :---: | :--- | :--- | :--- |
| `01` | **Automated Supplier KYB, OFAC Sanctions & GLEIF Corporate Ownership Gate** | `global-sanctions-pep-interpol-watchlist-screener` + `global-gleif-lei-corporate-ownership-kyb` | [`01_automated_supplier_kyb_ofac_sanctions_gleif_gate.json`](./workflows/01_automated_supplier_kyb_ofac_sanctions_gleif_gate.json) |
| `02` | **Daily DevSecOps CISA KEV Ransomware CVE & SSL Attack-Surface Monitor** | `cisa-kev-ransomware-vulnerability-auditor` + `b2b-ssl-tls-ct-log-subdomain-attack-surface-auditor` | [`02_devsecops_cisa_kev_ransomware_cve_ssl_monitor.json`](./workflows/02_devsecops_cisa_kev_ransomware_cve_ssl_monitor.json) |
| `03` | **Cross-Border EU VIES VAT Reverse-Charge & Anti-BEC Billing Domain Auditor** | `eu-vies-vat-tax-compliance-auditor` + `global-b2b-email-domain-security-auditor` | [`03_cross_border_eu_vies_vat_email_domain_auditor.json`](./workflows/03_cross_border_eu_vies_vat_email_domain_auditor.json) |
| `04` | **Global Government Procurement Radar (EU TED & LATAM PNCP High-Value Tenders)** | `eu-ted-public-tenders-procurement-radar` + `b2b-gov-procurement-pncp-radar` | [`04_global_public_tenders_eu_ted_brazil_pncp_radar.json`](./workflows/04_global_public_tenders_eu_ted_brazil_pncp_radar.json) |

## Quick Import (< 2 Minutes)
1. Get a free API key (`15 free runs/month`, PRO `$19/mo`) at **[RapidAPI @b2bquantapis](https://rapidapi.com/user/b2bquantapis)** (or run via **[Apify Store @b2b-quant-apis](https://apify.com/b2b-quant-apis)**).
2. In **n8n** (Self-Hosted or **[n8n Cloud](https://n8n.io/cloud/?utm_source=github_b2bquantapis)**), click **Import from File / URL** and select any JSON inside [`workflows/`](./workflows/).
3. Create an `HTTP Header Auth` credential (`Name: X-RapidAPI-Key`, `Value: YOUR_RAPIDAPI_KEY`) and attach it to the two HTTP compliance nodes.
