# AFKzona Group

Open-source tools for EU compliance, built to be used in real products and checked against the official texts.

| Project | What it does | Law | Licence |
|---|---|---|---|
| [Telltale](https://github.com/afkzonagroup/telltale) | AI Act Article 50: disclosure notices and labels as web components, machine-readable marking of AI-generated images, disclosure log | [Regulation (EU) 2024/1689](https://eur-lex.europa.eu/eli/reg/2024/1689/oj), Art. 50 | Apache-2.0 |
| [Cooloff](https://github.com/afkzonagroup/cooloff) | The EU withdrawal button for online shops: component, server handlers, acknowledgement of receipt, WooCommerce and Medusa plugins | [Directive (EU) 2023/2673](https://eur-lex.europa.eu/eli/dir/2023/2673/oj), Art. 11a CRD | Apache-2.0 |
| [Groundwork](https://github.com/afkzonagroup/groundwork) | AI literacy for staff: open course (CC BY 4.0), offline course site, SCORM and xAPI export for any LMS, tamper-evident training records | [Regulation (EU) 2024/1689](https://eur-lex.europa.eu/eli/reg/2024/1689/oj), Art. 4 | AGPL-3.0 + commercial |
| [Kerbcut](https://github.com/afkzonagroup/kerbcut) | European Accessibility Act scanner (WCAG 2.1 / EN 301 549) with Annex V service information and accessibility statements in every EU language | [Directive (EU) 2019/882](https://eur-lex.europa.eu/eli/dir/2019/882/oj) | AGPL-3.0 + commercial |
| [Tocsin](https://github.com/afkzonagroup/tocsin) | Incident register for NIS2 reporting: 24 h / 72 h / one-month deadlines, significance thresholds, report content, encrypted local store | [Directive (EU) 2022/2555](https://eur-lex.europa.eu/eli/dir/2022/2555/oj), Art. 23; [Implementing Regulation (EU) 2024/2690](https://eur-lex.europa.eu/eli/reg_impl/2024/2690/oj) | AGPL-3.0 + commercial |
| [Evenkeel](https://github.com/afkzonagroup/evenkeel) | Pay-gap indicators and the joint pay assessment test from a payroll export, computed locally (TypeScript, Python, offline app) | [Directive (EU) 2023/970](https://eur-lex.europa.eu/eli/dir/2023/970/oj), Art. 9–10 | AGPL-3.0 + commercial |
| [Brightline](https://github.com/afkzonagroup/brightline) | Scanner for likely manipulative design (dark patterns), each finding mapped to the consumer-law or GDPR rule it may breach | [UCPD](https://eur-lex.europa.eu/eli/dir/2005/29/oj), [CRD](https://eur-lex.europa.eu/eli/dir/2011/83/oj), [DSA](https://eur-lex.europa.eu/eli/reg/2022/2065/oj) Art. 25 | AGPL-3.0 + commercial |
| [Rationale](https://github.com/afkzonagroup/rationale) | SDK for submitting statements of reasons to the Commission's DSA Transparency Database: typed builder, validation mirroring the server rules, batch submission with retries, durable queue (TypeScript and Python) | [Regulation (EU) 2022/2065](https://eur-lex.europa.eu/eli/reg/2022/2065/oj), Art. 17 and 24(5) | Apache-2.0 |
| [Roster](https://github.com/afkzonagroup/roster) | DORA register of information: builds and validates the templates and writes the EBA xBRL-CSV report package, offline (TypeScript, Python, CLI, Docker) | [Regulation (EU) 2022/2554](https://eur-lex.europa.eu/eli/reg/2022/2554/oj), Art. 28(3); [Implementing Regulation (EU) 2024/2956](https://eur-lex.europa.eu/eli/reg_impl/2024/2956/oj) | AGPL-3.0 + commercial |
| [Fixform](https://github.com/afkzonagroup/fixform) | The European Repair Information Form in all 24 EU languages: validation, period of validity, document and e-mail rendering, web component, React and Vue, CLI, server handler | [Directive (EU) 2024/1799](https://eur-lex.europa.eu/eli/dir/2024/1799/oj), Art. 4 and Annex I | Apache-2.0 |
| [Plotline](https://github.com/afkzonagroup/plotline) | EUDR plot geolocation: validates and safely repairs GeoJSON, KML and CSV against the EU Information System rules, area, split, producer data for due-diligence statements (TypeScript, Python, CLI, offline page) | [Regulation (EU) 2023/1115](https://eur-lex.europa.eu/eli/reg/2023/1115/oj), Art. 9(1)(d) | AGPL-3.0 + commercial |
| [Sourcebook](https://github.com/afkzonagroup/sourcebook) | The public summary of training content for general-purpose AI models on the Commission's template: collectors for Hugging Face cards, dataset manifests and crawl logs, domain ranking, validation, document and model-card output (TypeScript, Python) | [Regulation (EU) 2024/1689](https://eur-lex.europa.eu/eli/reg/2024/1689/oj), Art. 53(1)(d) | AGPL-3.0 + commercial |

Every tool cites the article it implements and links the official text on EUR-Lex. None of them is legal advice.

**Licences.** Libraries meant to be embedded in your product are Apache-2.0. Applications and scanners are AGPL-3.0, with a commercial licence for organisations that cannot accept AGPL terms or want the enterprise features (hosted dashboard, continuous monitoring, SSO, audit evidence packs, legal-update feed, support). Contact info@afkzonagroup.lt.

**Security.** Report vulnerabilities privately through each repository's Security tab ("Report a vulnerability").

Maintained by [MB AFKzona Group](https://afkzonagroup.lt), Lithuania.
