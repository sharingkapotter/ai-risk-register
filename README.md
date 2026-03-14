# AI Risk Register Template
### A Comprehensive AI Governance Tool mapped to NIST AI RMF and EU AI Act

---

## Overview

This repository contains a professional AI Risk Register template designed for organizations to identify, categorize, score, and track risks associated with their AI systems. The template is pre-populated with 15 real-world risks for an AI-powered hiring screening tool — classified as **high-risk** under the EU AI Act (Annex III).

Built by a QA/SDET professional with 15+ years of experience in systematic risk identification, applying the same rigorous approach to AI governance.

---

## Repository Contents

| File | Description |
|------|-------------|
| `AI_Risk_Register.xlsx` | Main risk register spreadsheet with all features |
| `README.md` | This documentation file |

---

## Risk Register Features

- **13 columns** covering full risk lifecycle management
- **15 pre-populated risks** across 8 categories for an AI hiring screening tool
- **Automated Risk Score** calculated as Likelihood x Impact
- **Heat map color coding** — Red (15-25), Yellow (6-14), Green (1-5)
- **Dropdown menus** for Risk Category, Residual Risk, and Status
- **Data validation** on Likelihood and Impact (1-5 only)
- **3 tabs** — Risk Register, Scoring Guide, Risk Categories reference

---

## Risk Categories Covered

| Category | Description |
|----------|-------------|
| Bias/Fairness | Discriminatory outputs affecting protected groups |
| Security/Adversarial | Attacks, data poisoning, adversarial inputs |
| Privacy/Data Protection | GDPR/CCPA violations, consent failures |
| Reliability/Performance | Model drift, outages, accuracy degradation |
| Transparency/Explainability | Black-box decisions, lack of auditability |
| Legal/Regulatory | EU AI Act, EEOC, sector-specific compliance |
| Operational | Human oversight gaps, incident response failures |
| Reputational | Brand damage from AI failures |

---

## Risk Scoring Methodology

Risk Score = **Likelihood (1-5) x Impact (1-5)**

| Score Range | Risk Level | Action Required |
|-------------|------------|-----------------|
| 1 - 5 | Low | Monitor annually |
| 6 - 14 | Medium | Review quarterly |
| 15 - 25 | High | Immediate action required |

---

## Framework Alignment

### NIST AI RMF Mapping

This risk register directly supports the following NIST AI RMF functions:

| NIST Function | How This Register Supports It |
|---------------|-------------------------------|
| GOVERN | Establishes risk ownership, review cadence, and accountability |
| MAP | Identifies and categorizes AI risks across 8 dimensions |
| MEASURE | Quantifies risks using Likelihood x Impact scoring matrix |
| MANAGE | Documents mitigation plans, controls, and residual risk |

### EU AI Act Alignment

The AI hiring screening tool used as the example in this register is classified as **High-Risk** under **EU AI Act Annex III** (Employment and workers management category) because it:

- Automates candidate screening decisions
- Can produce discriminatory outcomes affecting protected groups
- Directly influences employment opportunities

High-risk AI systems under the EU AI Act require:

- Risk management system (this register)
- Data governance measures
- Transparency and human oversight
- Conformity assessment before deployment

---

## How To Use This Template

1. **Download** the `AI_Risk_Register.xlsx` file
2. **Review** the Scoring Guide tab to understand the methodology
3. **Review** the Risk Categories tab for definitions
4. **Replace** the example risks with risks specific to your AI system
5. **Assign owners** for each risk in your organization
6. **Schedule reviews** using the Review Date column
7. **Track progress** by updating the Status column

---

## About the Author

**Sunil** | SDET/QA Professional transitioning into AI Governance

- 15+ years of enterprise QA experience across large organizations
- CEH v12 certified
- Building expertise in AI governance, risk management, and compliance
- Actively pursuing IAPP AIGP certification

"As a QA professional, I have spent 15 years identifying risks in software systems before they become defects. This risk register applies that same systematic thinking to AI-specific risks, incorporating frameworks like NIST AI RMF and the EU AI Act."

---

## References

- [NIST AI Risk Management Framework (AI RMF 1.0)](https://nvlpubs.nist.gov/nistpubs/ai/nist.ai.100-1.pdf)
- [NIST AI RMF Interactive Playbook](https://airc.nist.gov/airmf-resources/playbook/)
- [EU AI Act Full Text](https://artificialintelligenceact.eu)
- [EU AI Act Annex III — High Risk Use Cases](https://artificialintelligenceact.eu/annex/3/)
