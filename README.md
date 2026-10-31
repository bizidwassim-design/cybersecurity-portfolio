# Cybersecurity portfolio — Wassim Bizid

Open-source GRC and SOC projects I build and maintain. Everything here is released under the MIT License, contains
no client data, and is meant to be reused as-is by small and mid-sized organisations that cannot afford commercial
toolkits. Website: [brainfortsecurity.com](https://www.brainfortsecurity.com/).

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

### Build status

| Project | CI | Licence |
|---------|----|---------|
| application-risk-assessment-template | [![CI](https://github.com/bizidwassim-design/application-risk-assessment-template/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/application-risk-assessment-template/actions) | MIT |
| grc-control-crosswalk | [![CI](https://github.com/bizidwassim-design/grc-control-crosswalk/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/grc-control-crosswalk/actions) | MIT |
| soc-detection-playbooks | [![Sigma check](https://github.com/bizidwassim-design/soc-detection-playbooks/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/soc-detection-playbooks/actions) | MIT |
| ciso-executive-dashboard | [![CI](https://github.com/bizidwassim-design/ciso-executive-dashboard/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/ciso-executive-dashboard/actions) · [live demo](https://bizidwassim-design.github.io/ciso-executive-dashboard/) | MIT |
| iso27001-iso42001-toolkit | [![CI](https://github.com/bizidwassim-design/iso27001-iso42001-toolkit/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/iso27001-iso42001-toolkit/actions) | MIT |
| public-scripts | [![CI](https://github.com/bizidwassim-design/public-scripts/actions/workflows/ci.yml/badge.svg)](https://github.com/bizidwassim-design/public-scripts/actions) | MIT |

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

## Reference tools I follow

Public forks of open-source projects I keep for study and comparison. Credit and licence belong to their authors.

| Project | Author | Licence | Fork |
|---------|--------|---------|------|
| [Cybether](https://github.com/jccyberx/Cybether) | jccyberx | No licence published | [fork](https://github.com/bizidwassim-design/Cybether) |
| [CISO-Dashboard](https://github.com/SiteQ8/CISO-Dashboard) | SiteQ8 | MIT | [fork](https://github.com/bizidwassim-design/CISO-Dashboard) |
| [security-leadership-panel](https://github.com/SiteQ8/security-leadership-panel) | SiteQ8 | MIT | [fork](https://github.com/bizidwassim-design/security-leadership-panel) |
| [ciso-maturity-tool](https://github.com/DYasmanovych/ciso-maturity-tool) | DYasmanovych | No licence published | [fork](https://github.com/bizidwassim-design/ciso-maturity-tool) |

## Principles

* **Original work.** The five projects are written from scratch; they are inspired by common practice, not copied from other repositories.
* **Fictional data only.** Sample companies, risks and metrics are invented.
* **Reusable by default.** MIT licence, no build step where avoidable, CSV/YAML twins for anything in Excel.
* **Standards-aligned.** ISO/IEC 27001:2022, ISO/IEC 42001:2023, NIST CSF 2.0, CIS Controls v8, SOC 2 TSC, MITRE ATT&CK.

## Contact

Through [brainfortsecurity.com](https://www.brainfortsecurity.com/) or GitHub issues on the relevant project.

## License

This index: [MIT](LICENSE). Each project carries its own licence file.

---

## 🇫🇷 Résumé

Portfolio de projets open source GRC et SOC : modèle d'évaluation des risques applicatifs (Excel, méthode 5×5),
table de correspondance des mesures ISO 27001 ↔ NIST CSF 2.0 / CIS v8 / ISO 42001 / SOC 2, règles de détection Sigma
avec playbooks et cartographie MITRE ATT&CK, tableau de bord RSSI pour la direction, et boîte à outils ISO 27001 / ISO 42001
(politiques, déclaration d'applicabilité, plan de traitement, RACI, analyse d'impact IA). Licence MIT, données fictives,
aucune donnée client.
