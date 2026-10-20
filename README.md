# A Systematic Feasibility Analysis of Smart Contract-Based B2B Services
### Lessons from an Adversarial Evaluation of 53 Market Hypotheses and a Future Research Agenda

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Technical Report](https://img.shields.io/badge/PDF-Technical_Report_v1.1-blue.svg)](pdf/Technical_Report_Smart_Contracts_B2B_Viability.pdf)
[![Hypotheses Dataset](https://img.shields.io/badge/Dataset-53_Hypotheses_(CSV%2FJSON)-green.svg)](data/)

**Author:** **Jose Luis Costumero Burgos** (*Independent Researcher*)  
**Version:** 1.1.0 · October 2026  
**Permanent Repository:** [https://github.com/jlcostumero/b2b-smart-contracts-feasibility](https://github.com/jlcostumero/b2b-smart-contracts-feasibility)

---

## 📌 Executive Summary

Academic and industrial literature on Distributed Ledger Technology (DLT) has consistently argued that smart contracts constitute the foundational architecture for a new generation of B2B digital services characterized by disintermediation, tamper-proof evidentiary auditability, and autonomous machine-to-machine (M2M) programmatic settlement. Nevertheless, enterprise adoption of public and Layer-2 (L2) networks remains negligible when compared to established centralized Web2 infrastructures.

This repository publishes the open evaluation corpus and findings of a structured adversarial evaluation of **53 commercial hypotheses for smart contract-based B2B services** across EVM Layer-2 networks (Base, Arbitrum One).

### 🔍 Key Findings & Rejection Funnel
* **100% Conventional Enterprise Attrition**: None of the 53 hypotheses established an economically defensible competitive moat against established, zero-marginal-cost Web2 alternatives.
* **Filter 1 (Regulatory & Tax Compliance, EU)**: Eliminated 14 hypotheses (MiFID II derivative licensing, statutory limits on unmoderated contractual penalties, and corporate invoicing incompatibilities).
* **Filter 2 (Technical Feasibility & Oracles)**: Eliminated 8 hypotheses (physical sensor oracle vulnerabilities, datacenter GPU latency).
* **Filter 3 (Unit Economics)**: Eliminated 7 hypotheses (sub-cent micro-margins eroded by RPC endpoints and network gas).
* **Filter 4 (Enterprise Procurement Friction)**: Eliminated 9 hypotheses (corporate treasury refusal to hold crypto-assets, absence of autonomous agent treasury mass).
* **Filter 5 (Adversarial Incumbent Benchmark)**: Eliminated 15 hypotheses (dominated by zero-marginal-cost Web2 cryptographic tools like Sigstore, GitHub Actions, Stripe, and Okta).
* **Stage 6 (Enterprise Testnet PoC Conversion Rate)**: **0.0% (0 / 53)**.

---

## 📂 Repository Structure

```text
├── pdf/
│   └── Technical_Report_Smart_Contracts_B2B_Viability.pdf   # 18-page publication-ready PDF (STIX Two typography)
├── data/
│   ├── hypotheses_master_matrix.csv                         # Flat dataset of all 53 hypotheses with L/T/E/R scores
│   └── hypotheses_master_matrix.json                        # Machine-readable JSON evaluation corpus
├── src/
│   ├── technical_report_web3_viability_en.md                # Full technical report source in English (v1.1)
│   ├── technical_report_web3_viability.md                   # Full technical report source in Spanish (v1.1)
│   └── technical_report_web3_viability.tex                  # Clean LaTeX source code
├── CITATION.cff                                             # Citation metadata for academic indexing
└── LICENSE                                                  # CC-BY-4.0 open license
```

---

## 📊 Summary of Evaluated Hypotheses by Cluster

| Cluster | Count | Proportion | Primary Rejection Factor |
| :--- | :---: | :---: | :--- |
| **Cluster A: Software Integrity, Provenance & SBOM** | 7 | 13.2% | Bundling of free cryptographic logs (Sigstore, GitHub Actions, SLSA). |
| **Cluster B: M2M Settlement & Autonomous Agents** | 16 | 30.2% | Incipient agent market; corporate B2B prefer SEPA Instant and Wise Business. |
| **Cluster C: Legal Evidentiary & Notarization** | 11 | 20.8% | EU eIDAS 2.0 qualified presumptions; free tools (FreeTSA, BaseStamp). |
| **Cluster D: Supply Chain & Physical Asset Operations** | 19 | 35.8% | Physical Sensor Oracle Fallacy; sovereign monopolies (OMIE, EU ETS). |
| **Total** | **53** | **100.0%** | **Stage 6 Conversion: 0.0%** |

---

## 📖 Citation

If you use this dataset, methodology, or report in your research or consulting work, please cite:

```bibtex
@techreport{costumero2026smartcontracts,
  author = {Costumero Burgos, Jose Luis},
  title = {A Systematic Feasibility Analysis of Smart Contract-Based B2B Services: Lessons from an Adversarial Evaluation of 53 Market Hypotheses and a Future Research Agenda},
  institution = {Independent Research / Open Science Corpus},
  year = {2026},
  month = {October},
  version = {1.1.0},
  url = {https://github.com/jlcostumero/b2b-smart-contracts-feasibility}
}
```

---

## 📄 License

This research and dataset are licensed under the [Creative Commons Attribution 4.0 International License (CC-BY-4.0)](LICENSE).
