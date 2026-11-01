# Open-source GRC and SOC projects: index — Wassim Bizid

This repository is only the **index** of my 19 open-source GRC and SOC projects. The canonical portfolio, with case studies and live demos, is [bizidwassim-design.github.io/wassim-bizid-portfolio](https://bizidwassim-design.github.io/wassim-bizid-portfolio/).

Open-source GRC and SOC projects I build and maintain. Everything here is released under the MIT License, contains
no client data, and is meant to be reused as-is by small and mid-sized organisations that cannot afford commercial
toolkits.

> 🇫🇷 Résumé en français en bas de page.

## Projects

| # | Project | What it is | Stack |
|---|---------|------------|-------|
| 1 | [application-risk-assessment-template](https://github.com/bizidwassim-design/application-risk-assessment-template) | Excel workbook to assess application risks with a Likelihood × Impact (5×5) method: methodology, scales, inventory, risk register with automatic rating, dashboard and heat map. Aligned with ISO 27001, NIST CSF 2.0 and ISO 42001. | Excel · openpyxl |
| 2 | [grc-control-crosswalk](https://github.com/bizidwassim-design/grc-control-crosswalk) | Crosswalk of the 93 ISO 27001:2022 Annex A controls to NIST CSF 2.0, CIS Controls v8, ISO 42001 and SOC 2 TSC — Excel with per-framework views, plus CSV and YAML for automation. | Excel · CSV · YAML · Python |
| 3 | [soc-detection-playbooks](https://github.com/bizidwassim-design/soc-detection-playbooks) | 14 Sigma detection rules covering every tactic of a ransomware kill chain (phishing/BEC, credential access, discovery, lateral movement, persistence, C2, exfiltration, impact, Entra ID & AWS) validated by `sigma check` in CI, six analyst playbooks, MITRE ATT&CK mapping and a Navigator layer. | Sigma · Markdown · ATT&CK |
| 4 | [ciso-executive-dashboard](https://github.com/bizidwassim-design/ciso-executive-dashboard) | Single-page executive security dashboard: KPIs, NIST CSF 2.0 maturity radar, risk and incident trends, vulnerability SLA, compliance progress, top risks, roadmap and budget. Edit one data file; host on GitHub Pages. | HTML · CSS · Chart.js |
| 5 | [iso27001-iso42001-toolkit](https://github.com/bizidwassim-design/iso27001-iso42001-toolkit) | Checklists, six policy templates, Statement of Applicability (ISO 27001 + ISO 42001 Annex A), risk treatment plan, RACI, AI system impact assessment, audit evidence list and a four-phase getting-started guide. | Markdown · Excel · Python |
| 6 | [public-scripts](https://github.com/bizidwassim-design/public-scripts) | 121 sanitised PowerShell, KQL and Python scripts for identity and security operations: AD / Entra ID audits, Exchange Online and SharePoint reporting, Defender hunting queries, endpoint administration, network checks, recurring compliance jobs. Sanitised, documented, secret-scanned in CI. | PowerShell · KQL |
| 7 | [threat-modeling-toolkit](https://github.com/bizidwassim-design/threat-modeling-toolkit) | STRIDE, PASTA and LINDDUN templates and checklists, a worked fictional example, and a generator that turns a YAML data-flow model into a STRIDE-per-element threat table mapped to OWASP ASVS and ISO 27001. | Markdown · Mermaid · Python |
| 8 | [ai-risk-assessment-template](https://github.com/bizidwassim-design/ai-risk-assessment-template) | Excel workbook to assess AI system risks (bias, transparency, drift, privacy, security, safety, accountability) with inventory, 5×5 scoring, impact roll-up, dashboard, ISO/IEC 42001 mapping and an EU AI Act quick classifier. | Excel · openpyxl |
| 9 | [vendor-risk-assessment-template](https://github.com/bizidwassim-design/vendor-risk-assessment-template) | TPRM workbook: vendor tiering, 60-question weighted questionnaire, assessment summary, contract-clause checklist, dashboard, plus the questionnaire as Markdown and CSV. | Excel · Markdown |
| 10 | [security-metrics-library](https://github.com/bizidwassim-design/security-metrics-library) | 40+ security metrics with definitions, formulas, sources and framework references; generated catalogue, board pack, dashboard wireframes and a trend-report generator. | YAML · Markdown · Python |
| 11 | [incident-response-playbooks](https://github.com/bizidwassim-design/incident-response-playbooks) | Ten incident-manager level playbooks (data breach, insider threat, supply chain, DDoS, AI incident…) with severity matrix, communication templates, records and a tabletop exercise kit. | Markdown |
| 12 | [policy-as-code-starter](https://github.com/bizidwassim-design/policy-as-code-starter) | OPA/Rego policies with tests for Kubernetes and Terraform, Checkov custom policies, Sentinel examples, passing/failing IaC samples and a policy-to-control mapping. | Rego · YAML · Terraform |
| 13 | [soc-maturity-assessment](https://github.com/bizidwassim-design/soc-maturity-assessment) | Single-page SOC maturity self-assessment: 50 questions, six domains, radar chart, gap table and roadmap guidance; no build step, GitHub Pages. | HTML · CSS · JS |
| 14 | [control-evidence-collector](https://github.com/bizidwassim-design/control-evidence-collector) | Read-only collectors producing hashed, timestamped JSON evidence for ISO 27001 / CIS v8 controls on Windows, Linux, Microsoft 365 and cloud, with a verification manifest. | PowerShell · Bash · Python |
| 15 | [risk-treatment-plan-generator](https://github.com/bizidwassim-design/risk-treatment-plan-generator) | Python CLI that turns a risk register into a prioritised, wave-based treatment plan with quick wins, owner workload and Markdown / CSV / Excel / Mermaid outputs. | Python · Excel |
| 16 | [cybersecurity-raci-library](https://github.com/bizidwassim-design/cybersecurity-raci-library) | Twelve validated RACI matrices for core security processes with clause references, exported to Markdown and Excel. | CSV · Markdown · Excel |
| 17 | [uae-ia-compliance-matrix](https://github.com/bizidwassim-design/uae-ia-compliance-matrix) | Single-page compliance matrix for the UAE Information Assurance Standard: 15 control families with status, owner, evidence, score and gap list, mapped to ISO 27001:2022 and NIST CSF 2.0; CSV import of your own control list. | HTML · CSS · JS |
| 18 | [executive-risk-pack](https://github.com/bizidwassim-design/executive-risk-pack) | Quarterly board cyber-risk pack generated from CSV and YAML: summary, NIST CSF 2.0 posture, top risks, KRIs, regulatory calendar and board decisions, as Markdown, Excel and PNG. | Python · Excel · Markdown |
| 19 | [iso27001-isms-lab](https://github.com/bizidwassim-design/iso27001-isms-lab) | Complete fictional ISO/IEC 27001:2022 ISMS cycle (context, risk assessment, SoA, internal audit, management review) generated from data and validated for full Annex A coverage. | Python · Excel · Markdown |

### Build status

| Project | CI | Licence |
|---------|----|---------|
| application-risk-assessment-template | [![CI](https://github.com/bizidwassim-design/application-risk-assessment-template/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/application-risk-assessment-template/actions) | MIT |
| grc-control-crosswalk | [![CI](https://github.com/bizidwassim-design/grc-control-crosswalk/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/grc-control-crosswalk/actions) · [live demo](https://bizidwassim-design.github.io/grc-control-crosswalk/) | MIT |
| soc-detection-playbooks | [![Sigma check](https://github.com/bizidwassim-design/soc-detection-playbooks/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/soc-detection-playbooks/actions) | MIT |
| ciso-executive-dashboard | [![CI](https://github.com/bizidwassim-design/ciso-executive-dashboard/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/ciso-executive-dashboard/actions) · [live demo](https://bizidwassim-design.github.io/ciso-executive-dashboard/) | MIT |
| iso27001-iso42001-toolkit | [![CI](https://github.com/bizidwassim-design/iso27001-iso42001-toolkit/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/iso27001-iso42001-toolkit/actions) | MIT |
| public-scripts | [![CI](https://github.com/bizidwassim-design/public-scripts/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/public-scripts/actions) | MIT |
| threat-modeling-toolkit | [![CI](https://github.com/bizidwassim-design/threat-modeling-toolkit/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/threat-modeling-toolkit/actions) | MIT |
| ai-risk-assessment-template | [![CI](https://github.com/bizidwassim-design/ai-risk-assessment-template/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/ai-risk-assessment-template/actions) | MIT |
| vendor-risk-assessment-template | [![CI](https://github.com/bizidwassim-design/vendor-risk-assessment-template/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/vendor-risk-assessment-template/actions) · [live demo](https://bizidwassim-design.github.io/vendor-risk-assessment-template/) | MIT |
| security-metrics-library | [![CI](https://github.com/bizidwassim-design/security-metrics-library/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/security-metrics-library/actions) | MIT |
| incident-response-playbooks | [![CI](https://github.com/bizidwassim-design/incident-response-playbooks/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/incident-response-playbooks/actions) | MIT |
| policy-as-code-starter | [![CI](https://github.com/bizidwassim-design/policy-as-code-starter/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/policy-as-code-starter/actions) | MIT |
| soc-maturity-assessment | [![CI](https://github.com/bizidwassim-design/soc-maturity-assessment/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/soc-maturity-assessment/actions) · [live demo](https://bizidwassim-design.github.io/soc-maturity-assessment/) | MIT |
| control-evidence-collector | [![CI](https://github.com/bizidwassim-design/control-evidence-collector/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/control-evidence-collector/actions) | MIT |
| risk-treatment-plan-generator | [![CI](https://github.com/bizidwassim-design/risk-treatment-plan-generator/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/risk-treatment-plan-generator/actions) | MIT |
| cybersecurity-raci-library | [![CI](https://github.com/bizidwassim-design/cybersecurity-raci-library/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/cybersecurity-raci-library/actions) | MIT |
| uae-ia-compliance-matrix | [![CI](https://github.com/bizidwassim-design/uae-ia-compliance-matrix/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/uae-ia-compliance-matrix/actions) · [live demo](https://bizidwassim-design.github.io/uae-ia-compliance-matrix/) | MIT |
| executive-risk-pack | [![CI](https://github.com/bizidwassim-design/executive-risk-pack/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/executive-risk-pack/actions) | MIT |
| iso27001-isms-lab | [![CI](https://github.com/bizidwassim-design/iso27001-isms-lab/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/iso27001-isms-lab/actions) | MIT |

Every repository ships a `SECURITY.md` (private vulnerability reporting), a `CHANGELOG.md`, CI that rebuilds and
verifies the generated files, no macros in any office document, and fictional sample data only.

### How they fit together

```
                 ┌─────────────────────────────┐
                 │ 5 · ISO 27001/42001 toolkit │  policies, SoA, treatment plan, evidence
                 └──────────────┬──────────────┘
          uses the same scales  │  maps controls with
   ┌────────────────────────────┼────────────────────────────┐
   ▼                            ▼                            ▼
1 · Risk assessment     2 · Control crosswalk       3 · Detection & response
   (5×5 method)           (ISO ↔ CSF/CIS/42001/SOC2)   (Sigma + playbooks)
   └────────────────────────────┬────────────────────────────┘
                                ▼
                 4 · CISO executive dashboard (reports the KPIs to the board)
```

## Principles

* **Original work.** All sixteen projects were designed and written from scratch by Wassim Bizid.
* **Fictional data only.** Sample companies, risks and metrics are invented.
* **Reusable by default.** MIT licence, no build step where avoidable, CSV/YAML twins for anything in Excel.
* **Standards-aligned.** ISO/IEC 27001:2022, ISO/IEC 42001:2023, NIST CSF 2.0, CIS Controls v8, SOC 2 TSC, MITRE ATT&CK.

## Contact

Through the [portfolio contact section](https://bizidwassim-design.github.io/wassim-bizid-portfolio/#contact) or GitHub issues on the relevant project.

## AI assistance

Built with Claude Code as a coding and writing assistant, which is why it appears as a co-author on some commits.
**Editor and reviewer: Wassim Bizid**, who set the scope, the frameworks and the GRC approach, edited the content
and decided what was published. Automated tests in CI check the published outputs. This is a maintainer review,
not an independent one.

## License

This index: [MIT](LICENSE). Each project carries its own licence file.

---

## 🇫🇷 Résumé

Portfolio de projets open source GRC et SOC : modèle d'évaluation des risques applicatifs (Excel, méthode 5×5),
table de correspondance des mesures ISO 27001 ↔ NIST CSF 2.0 / CIS v8 / ISO 42001 / SOC 2, règles de détection Sigma
avec playbooks et cartographie MITRE ATT&CK, tableau de bord RSSI pour la direction, et boîte à outils ISO 27001 / ISO 42001
(politiques, déclaration d'applicabilité, plan de traitement, RACI, analyse d'impact IA). Licence MIT, données fictives,
aucune donnée client.
