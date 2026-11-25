# VulDB Cyber Threat Intelligence

[![VulDB](https://img.shields.io/badge/VulDB-Threat%20Intelligence-24476b)](https://vuldb.com/kb/cti)
[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](#license)
[![GitHub last commit](https://img.shields.io/github/last-commit/vuldb/cyber_threat_intelligence)](https://github.com/vuldb/cyber_threat_intelligence/commits/main/)

Public cyber threat intelligence (CTI) data and analysis provided by [VulDB](https://vuldb.com/).

This repository provides a selection of intelligence on threat actors and campaigns to support proactive cyber defense, threat hunting, incident response, and vulnerability prioritization. VulDB combines activity monitoring, geopolitical analysis, and AI-assisted forecasting to identify emerging threats and anticipate potential adversary activities.

## Table of Contents

- [Repository Structure](#repository-structure)
- [Intelligence Categories](#intelligence-categories)
- [Research Methodology](#research-methodology)
- [Getting Started](#getting-started)
- [Use Cases](#use-cases)
- [Data Handling and Limitations](#data-handling-and-limitations)
- [Updates and Integration](#updates-and-integration)
- [Feedback and Contributions](#feedback-and-contributions)
- [License](#license)
- [Resources and Contact](#resources-and-contact)

## Repository Structure

```text
cyber_threat_intelligence/
├── actors/          # Threat actor intelligence
├── campaigns/       # Threat campaign intelligence
├── .gitattributes   # Git text-file normalization settings
└── README.md        # Repository documentation
```

| Directory | Description |
| --- | --- |
| [`actors/`](actors/) | Intelligence organized around threat actors, including advanced persistent threat (APT) groups and other adversaries. |
| [`campaigns/`](campaigns/) | Intelligence organized around identified threat campaigns and related activities. |

The repository is a data collection rather than a standalone software application. No application installation is required to browse the published files.

## Intelligence Categories

VulDB CTI covers the following categories. Availability varies by actor, campaign, and dataset; not every category is necessarily present in every public file.

| Category | Description |
| --- | --- |
| Threat actors | Adversary groups and their associated activities, interests, and attribution context. |
| Campaigns | Related malicious activities grouped into an identifiable operation or campaign. |
| Country associations | Geographic or geopolitical context associated with actors and activities. |
| Indicators of Compromise (IOCs) | Observables that may be associated with malicious activity, such as IP addresses, domains, or file hashes. |
| Indicators of Attack (IOAs) | Behaviors or signals that may indicate an attempted or ongoing attack. |
| Tactics, Techniques, and Procedures (TTPs) | Adversary objectives, methods, and operational behavior. |
| Predictive indicators | Intelligence suggesting possible future adversary activity, rather than necessarily confirmed observations. |
| External references | Supporting sources used to provide additional context and facilitate independent verification. |

## Research Methodology

### Activity Monitoring

VulDB monitors discussions and activity across relevant internet sources, including vulnerability mailing lists, forums, social media, and underground marketplaces. These observations help identify shifts in adversary interest and potential preparation for malicious activity.

### Geopolitical Analysis

The CTI team examines relationships between countries, organizations, and threat groups to assess emerging tensions and possible attack scenarios. Political, economic, and diplomatic developments provide additional context for technical intelligence.

### Predictive Intelligence

AI-assisted analysis identifies patterns that may indicate future targeting or exploitation activity. Predictive intelligence supports early defensive preparation but must be distinguished from evidence of confirmed compromise or exploitation.

For details on VulDB's intelligence methodology and scoring systems, see the [Cyber Threat Intelligence knowledge base](https://vuldb.com/kb/cti).

## Getting Started

### Browse the Data

Explore the [`actors/`](actors/) and [`campaigns/`](campaigns/) directories directly on GitHub. Individual files can be viewed or retrieved using GitHub's raw file option.

### Clone the Repository

```bash
git clone https://github.com/vuldb/cyber_threat_intelligence.git
cd cyber_threat_intelligence
```

Alternatively, [download the repository as a ZIP archive](https://github.com/vuldb/cyber_threat_intelligence/archive/refs/heads/main.zip).

### Discover Available Files

```bash
git ls-files actors/ campaigns/
```

Inspect the relevant files to determine their format and available fields before importing them into an external system.

### Search the Data

Search tracked files for a threat actor name, campaign name, or indicator of interest. The following example uses a reserved documentation IP address as a placeholder:

```bash
git grep -n -i -F -- '192.0.2.10' -- actors/ campaigns/
```

Replace the example value with the observable or search term relevant to your investigation. A match is a starting point for analysis, not proof of malicious activity.

### Update the Local Copy

```bash
git pull --ff-only origin main
```

Review recent changes to the intelligence directories:

```bash
git log --oneline -10 -- actors/ campaigns/
```

## Use Cases

| Use case | Application |
| --- | --- |
| Threat hunting | Correlate published intelligence with endpoint, network, DNS, and authentication telemetry. |
| Incident response | Enrich investigative findings with information about potentially related actors or campaigns. |
| SOC operations | Provide context for security alerts and identify relevant investigation priorities. |
| Vulnerability management | Combine threat context with asset exposure, vulnerability severity, and exploitation evidence to prioritize remediation. |
| Detection engineering | Develop and validate detection logic using relevant adversary behaviors and indicators. |
| Strategic intelligence | Assess emerging threats and geopolitical developments relevant to an organization. |

## Data Handling and Limitations

Threat intelligence is time-sensitive and should always be interpreted in context.

- **Validate indicators:** Correlate intelligence with independent evidence and local telemetry before taking action.
- **Distinguish observed and predictive data:** Forecasts do not establish that an attack has occurred or will occur.
- **Consider indicator lifetime:** IP addresses, domains, and infrastructure ownership can change over time.
- **Treat attribution carefully:** Associations with actors or countries do not, by themselves, establish responsibility for an incident.
- **Avoid indiscriminate blocking:** Shared infrastructure and outdated indicators may cause false positives or service disruption.
- **Treat external content as untrusted:** Do not visit potentially malicious URLs or execute referenced files outside an appropriate analysis environment.
- **Preserve provenance:** Retain the original source, retrieval time, and available attribution or confidence information when processing intelligence.

The public repository should not be treated as an exhaustive or guaranteed real-time feed. For extended intelligence and current platform capabilities, refer to the VulDB CTI service.

## Updates and Integration

Changes are published through GitHub commits. Review the [commit history](https://github.com/vuldb/cyber_threat_intelligence/commits/main/) to track additions and revisions. For reproducible research or automated ingestion, retain the commit identifier associated with the retrieved dataset:

```bash
git rev-parse HEAD
```

### Integration Recommendations

The repository can serve as a source for custom intelligence workflows involving Security Information and Event Management (SIEM), Security Orchestration, Automation and Response (SOAR), Threat Intelligence Platforms (TIP), and security data pipelines.

A typical integration should:

1. Retrieve the latest repository revision.
2. Identify and validate the relevant file formats.
3. Normalize and deduplicate records while retaining their context.
4. Distinguish confirmed observations from predictive intelligence where indicated.
5. Correlate intelligence with internal telemetry and review findings.
6. Reassess previously imported records when the source data changes.

### VulDB API

For structured, programmatic access to additional vulnerability and cyber threat intelligence data, consult the [VulDB API documentation](https://vuldb.com/kb/api). The API is separate from this GitHub repository, and access to extended CTI features may require an eligible account or subscription.

- [API documentation](https://vuldb.com/kb/api)
- [Available data points](https://vuldb.com/kb/datapoints)
- [PHP API examples](https://github.com/vuldb/vuldb-api-php-examples)
- [Additional API client examples](https://github.com/vuldb)

## Feedback and Contributions

For suspected inaccuracies, outdated indicators, attribution corrections, or additional intelligence, please contact the VulDB support team at [support@vuldb.com](mailto:support@vuldb.com).

Where possible, include:

- The affected repository file or dataset.
- The relevant actor, campaign, or indicator.
- A description of the proposed correction or addition.
- Supporting evidence, source references, and relevant observation dates.

Do not submit confidential information, credentials, personal data, or sensitive incident details through public channels.

## License

The public repository is marked with the [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/) license badge.

When sharing or adapting material covered by this license, provide appropriate credit, link to the license, indicate modifications, and distribute adapted material under the same license or a compatible license as permitted by CC BY-SA 4.0. Third-party material may be subject to separate rights and restrictions.

Suggested attribution:

> Source: VulDB – Cyber Threat Intelligence, https://github.com/vuldb/cyber_threat_intelligence (CC BY-SA 4.0).

For licensing questions or requirements beyond the public repository, contact [support@vuldb.com](mailto:support@vuldb.com).

## Resources and Contact

| Resource | Link |
| --- | --- |
| VulDB platform | [vuldb.com](https://vuldb.com/) |
| Cyber Threat Intelligence | [CTI documentation](https://vuldb.com/kb/cti) |
| Threat actor analysis | [vuldb.com/actor](https://vuldb.com/actor) |
| Country analysis | [vuldb.com/country](https://vuldb.com/country) |
| API | [API documentation](https://vuldb.com/kb/api) |
| GitHub organization | [github.com/vuldb](https://github.com/vuldb) |
| Support | [support@vuldb.com](mailto:support@vuldb.com) |

---

Maintained by the VulDB team in Switzerland.
