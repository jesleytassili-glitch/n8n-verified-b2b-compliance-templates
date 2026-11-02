# Guia Oficial Copy-Paste — `n8n Verified Creator` + Afiliado 30% Cloud (`RE-10`)

## 1. Como Ativar os 2 Fluxos de Receita Recorrente em USD (Wise `#890361113`)
1. **Programa de Afiliados n8n Cloud (30% de comissão recorrente por 12 meses):**
   - Cadastro gratuito em 2 minutos: https://n8n.io/affiliates/
   - Assim que receber seu link (`?ref=...`), defina `N8N_AFFILIATE_URL` no `.env` (atual: `https://n8n.io/cloud/?utm_source=n8n_creator_b2bquantapis`) e rode novamente este builder para atualizar os Sticky Notes.
2. **Selo `Verified Creator` + Venda de Templates Pagos (`creators.n8n.io`):**
   - Acesse https://creators.n8n.io e envie os **4 templates abaixo** (ter **3 aprovados** destrava o selo *Verified Creator* e habilita Templates Pagos dentro do catálogo nativo do n8n).

---

## 2. Textos Prontos em Inglês para Colar no Portal `creators.n8n.io`

### Template #1: `Automated Supplier KYB, OFAC Sanctions & GLEIF Corporate Ownership Gate`
- **JSON File:** `01_automated_supplier_kyb_ofac_sanctions_gleif_gate.json`
- **Category:** `SecOps & FinOps Compliance`
- **Primary / Secondary Public APIs:** `global-sanctions-pep-interpol-watchlist-screener` + `global-gleif-lei-corporate-ownership-kyb`
- **Description (Copy-Paste):**
  > Screens B2B suppliers against OFAC SDN, UN, EU and Interpol watchlists in parallel with GLEIF LEI parent-company ownership verification before approving onboarding or high-value payouts. Uses standard n8n Header Auth credentials (`X-RapidAPI-Key`), includes 3 on-canvas Sticky Notes for <2-minute setup, deduplicates multi-source findings in JavaScript, and splits high-priority alerts (`riskScore >= 60`) from clean audit trail records.

### Template #2: `Daily DevSecOps CISA KEV Ransomware CVE & SSL Attack-Surface Monitor`
- **JSON File:** `02_devsecops_cisa_kev_ransomware_cve_ssl_monitor.json`
- **Category:** `DevOps & Cybersecurity`
- **Primary / Secondary Public APIs:** `cisa-kev-ransomware-vulnerability-auditor` + `b2b-ssl-tls-ct-log-subdomain-attack-surface-auditor`
- **Description (Copy-Paste):**
  > Audits production domains and CVE inventories daily against the US CISA Known Exploited Vulnerabilities (KEV) catalog and Certificate Transparency (CT) logs to catch ransomware exposure and expiring TLS certificates before outages occur. Uses standard n8n Header Auth credentials (`X-RapidAPI-Key`), includes 3 on-canvas Sticky Notes for <2-minute setup, deduplicates multi-source findings in JavaScript, and splits high-priority alerts (`riskScore >= 60`) from clean audit trail records.

### Template #3: `Cross-Border EU VIES VAT Reverse-Charge & Anti-BEC Billing Domain Auditor`
- **JSON File:** `03_cross_border_eu_vies_vat_email_domain_auditor.json`
- **Category:** `Finance & Accounting Automation`
- **Primary / Secondary Public APIs:** `eu-vies-vat-tax-compliance-auditor` + `global-b2b-email-domain-security-auditor`
- **Description (Copy-Paste):**
  > Verifies European Union cross-border VAT registration numbers against official EU VIES for 0% Reverse-Charge compliance while auditing the vendor's billing email domain (SPF, DMARC, MX) to prevent Business Email Compromise (BEC) wire fraud. Uses standard n8n Header Auth credentials (`X-RapidAPI-Key`), includes 3 on-canvas Sticky Notes for <2-minute setup, deduplicates multi-source findings in JavaScript, and splits high-priority alerts (`riskScore >= 60`) from clean audit trail records.

### Template #4: `Global Government Procurement Radar (EU TED & LATAM PNCP High-Value Tenders)`
- **JSON File:** `04_global_public_tenders_eu_ted_brazil_pncp_radar.json`
- **Category:** `Sales & B2B Lead Generation`
- **Primary / Secondary Public APIs:** `eu-ted-public-tenders-procurement-radar` + `b2b-gov-procurement-pncp-radar`
- **Description (Copy-Paste):**
  > Monitors European Union TED and LATAM PNCP public procurement portals every morning, normalizing contract values, deduplicating tenders, and routing high-ticket B2G opportunities straight to your CRM or Sales Slack channel. Uses standard n8n Header Auth credentials (`X-RapidAPI-Key`), includes 3 on-canvas Sticky Notes for <2-minute setup, deduplicates multi-source findings in JavaScript, and splits high-priority alerts (`riskScore >= 60`) from clean audit trail records.

