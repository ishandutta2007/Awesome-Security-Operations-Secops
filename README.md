# Awesome-Security-Operations-Secops

## Top Security Operations (SecOps) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on SIEM, SOAR, Threat Detection & Security Incident Response*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Security Operations (SecOps)**. These tools enable security teams to collect and correlate security telemetry, detect threats in real time, automate incident response, and orchestrate remediation workflows across on-premises, cloud, and hybrid environments.



**Examples** include ServiceNow Security Operations, Palo Alto Networks Cortex XSIAM, Splunk Enterprise Security, IBM QRadar SIEM, Microsoft Sentinel, Rapid7 InsightIDR, Exabeam, Sumo Logic Cloud SIEM, LogRhythm, and AlienVault USM (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosted SIEM, log analytics, intrusion detection, and security automation—ideal for SOC teams, security engineers, and organizations building sovereign security operations infrastructure without per-seat or per-GB licensing lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ServiceNow Security Operations](https://www.servicenow.com/)**  

  Enterprise SecOps suite on the Now Platform including Security Incident Response (SIR) with SOAR capabilities, Vulnerability Response, and Threat Intelligence; Yokohama release adds AI agents for automated incident close-out with close codes and resolution notes, plus Correlation Insights for cross-record pattern analysis to reduce SOC workload .



- **[Palo Alto Networks Cortex XSIAM](https://www.paloaltonetworks.com/)**  

  AI-driven SecOps platform converging SIEM, SOAR, UEBA, ASM, and XDR in a unified data layer; XSIAM 3.0 adds Cortex Exposure Management with up to 99% vulnerability noise reduction and automated remediation, plus Advanced Email Security; customers report 98% MTTR reduction and 75% less manual work .



- **[Splunk Enterprise Security](https://www.splunk.com/)**  

  Industry-leading SIEM with two editions: Essentials (unified SIEM, SOAR, threat intelligence, AI Assistant) and Premier (adds native UEBA and full-spectrum SOAR for every analyst); ES 8.2 unifies TDIR workflows with AI Agents and reports 64% faster threat identification and 55% faster incident resolution .



- **[IBM QRadar SIEM](https://www.ibm.com/products/qradar)**  

  Threat detection and response platform with User Behavior Analytics (UBA) for baseline behavior pattern detection; correlates data across cloud, endpoint, identity, and network environments for real-time threat prioritization and response .



- **[Microsoft Sentinel](https://learn.microsoft.com/azure/sentinel/)**  

  Cloud-native SIEM and SOAR with 350+ data connectors, AI-powered analytics, MITRE ATT&CK coverage mapping, and unified data lake for long-term retention; transitioning fully to the Microsoft Defender portal by March 2027 .



- **[Rapid7 InsightIDR](https://www.rapid7.com/)**  

  Cloud-based detection and response platform combining UEBA, Intruder Traps (network scans and password guessing detection), and machine learning; focuses on high-fidelity detection of credential compromise, malware, and phishing with user-centric investigation context .



- **[Exabeam New-Scale Fusion](https://www.exabeam.com/)**  

  Cloud-native security operations platform combining SIEM, behavioral analytics, and automation; features Agent Behavior Analytics for monitoring AI agents and non-human identities, Exabeam Nova AI agents for triage and case summarization, and 1,000+ tool integrations .



- **[Sumo Logic Cloud SIEM](https://www.sumologic.com/)**  

  Cloud-native SIEM with match, threshold, chain, aggregation, first-seen, and outlier rules for threat detection; provides centralized log management and security analytics for cloud and hybrid environments .



- **[LogRhythm](https://www.logrhythm.com/)**  

  SIEM platform with AI Engine for automated detection, case management, and log source virtualization; recent releases focus on HA/DR deployment reliability and expanded cloud service log parsing .



- **[AlienVault USM](https://www.alienvault.com/)**  

  Unified Security Management platform (now part of LevelBlue) combining asset discovery, vulnerability assessment, IDS, SIEM correlation, and threat intelligence from Open Threat Exchange (OTX); OSSIM provides the open-source foundation .



## Open-Source GitHub Projects



- **[Wazuh](https://github.com/wazuh/wazuh)**  

  Leading open-source security platform (GPL-2.0) combining SIEM and XDR capabilities; provides log analysis, intrusion detection, file integrity monitoring, vulnerability detection, and active response across endpoints and cloud workloads; includes a REST API, web dashboard, and agent-based architecture with active community development.



- **[Elastic Security (ELK Stack)](https://github.com/elastic/elasticsearch)**  

  Open-source search and analytics platform (Elasticsearch, Logstash, Kibana, Beats) that can be assembled into a SIEM; Elastic relicensed core components under AGPL-3.0 in 2024; Elastic Security adds prebuilt detection rules, malware prevention, and case management, though some production features require a subscription .



- **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**  

  AWS-led open-source fork of Elasticsearch and Kibana (Apache 2.0); provides log storage, search, and visualization for building custom SIEM pipelines; the OpenSearch Security Analytics plugin adds detection capabilities without licensing restrictions .



- **[Suricata](https://github.com/OISF/suricata)**  

  High-performance open-source network IDS/IPS/NSM engine (GPL-2.0); provides deep packet inspection, protocol analysis, and real-time alerting for network threats; commonly integrated with ELK/OpenSearch for SIEM use cases .



- **[OSSIM (AlienVault OSSIM)](https://github.com/alienvault/ossim)**  

  Open-source SIEM foundation from AlienVault (now LevelBlue); integrates OpenVAS vulnerability scanning, Snort/Suricata IDS correlation, and threat intelligence from OTX; the open-source edition lacks commercial features like built-in reporting and real-time response consoles .



- **[TheHive](https://github.com/TheHive-Project/TheHive)**  

  Open-source security incident response platform (AGPL-3.0) for SOC teams; provides case management, observable analysis, task tracking, and integration with MISP for threat intelligence enrichment and Cortex for automated analyzers.



- **[MISP](https://github.com/MISP/MISP)**  

  Open-source threat intelligence sharing platform (AGPL-3.0) with IOC storage, correlation, and STIX/TAXII support; integrates with SIEM tools and TheHive to operationalize threat intelligence in detection and response workflows.



- **[Velociraptor](https://github.com/Velocidex/velociraptor)**  

  Open-source endpoint visibility and digital forensics platform (Apache 2.0) for hunting threats and investigating incidents at scale; uses VQL (Velociraptor Query Language) for collecting endpoint telemetry and detecting malicious activity.



- **[Sigma](https://github.com/SigmaHQ/sigma)**  

  Open standard and rule repository for writing SIEM-agnostic detection rules; rules are written in YAML and converted to queries for Splunk, Elastic, QRadar, and other platforms, enabling portable detection engineering across SIEM backends.



- **[Shuffle](https://github.com/Shuffle/Shuffle)**  

  Open-source SOAR platform (AGPL-3.0) for automating security workflows; provides a visual workflow editor, 1,000+ app integrations, and the ability to orchestrate response actions across SIEM, EDR, and ticketing tools.



### Additional Strong Open-Source Options



- **Grafana + Loki** — Open-source observability stack for log aggregation and visualization; can be adapted for security monitoring with custom dashboards and alerting rules.

- **Fluentd / Fluent Bit** — Open-source log collectors and forwarders for building ingestion pipelines into SIEM backends .

- **Zeek** — Open-source network security monitor (BSD) providing rich connection logs and protocol analysis; complements Suricata for network visibility.

- **Cortex** — Open-source observable analysis and active response engine from TheHive Project; runs analyzers (VirusTotal, AbuseIPDB, etc.) and responders for automated enrichment.



**Frameworks for building custom systems**: Combine **Wazuh** for agent-based SIEM/XDR with integrated active response, **Elastic Security** or **OpenSearch** for log storage and detection rules, **Suricata** for network intrusion detection, **TheHive** with **MISP** for case management and threat intelligence, and **Shuffle** for SOAR automation in a fully self-hosted SecOps stack.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- SecOps platforms handling security telemetry and incident data must comply with applicable regulations and organizational security policies; log data may contain sensitive information requiring access controls.

- Self-hosted open-source solutions require significant operational investment in tuning, rule development, storage scaling, and 24/7 monitoring coverage.

- Verify license terms for commercial use; Wazuh uses GPL-2.0, Elastic core uses AGPL-3.0/Elastic License, OpenSearch uses Apache-2.0, and TheHive uses AGPL-3.0.



---



**Made for SOC analysts, security engineers, incident responders, and security operations managers.**  

Let's make security operations more open, automated, and threat-aware.
