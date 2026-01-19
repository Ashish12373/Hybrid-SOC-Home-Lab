# Hybrid SOC Home Lab (Splunk + Zeek + Sysmon + Beats)

## Overview
This project documents the design and implementation of a hybrid Security Operations Center (SOC) home lab to develop hands-on defensive security and threat-hunting skills.

The lab integrates:
- Host-based telemetry (Sysmon, Winlogbeat, Auditbeat)
- Network-based telemetry (Zeek)
- SIEM platforms (Splunk, Elasticsearch + Kibana – secondary pipeline)

This project is part of an independent study (ECE 697) focused on real-world SOC workflows.

## Lab Architecture
- SIEM VM (Ubuntu): Splunk, Elasticsearch, Kibana
- Windows VM: Sysmon + Winlogbeat
- Linux VM: Zeek + Auditbeat
- Static IP configuration for all hosts

## Week 1–2 Objectives (Completed)
- Installed and configured Splunk SIEM
- Deployed Sysmon on Windows host
- Installed Zeek on Linux for network telemetry
- Configured Winlogbeat and Auditbeat agents
- Validated log generation and forwarding pipelines
- Established baseline host and network telemetry

## Current Status
✔ Lab environment operational  
✔ Logs generated from Windows and Linux hosts  
✔ Network telemetry captured via Zeek  
⏳ Elasticsearch + Kibana integration (rebuilding cleanly)

## Tools & Technologies
- Splunk Enterprise
- Zeek
- Sysmon
- Winlogbeat
- Auditbeat
- Elasticsearch
- Kibana
- Ubuntu, Windows

## Roadmap
- Week 3–4: Baseline behavior analysis
- Week 5–6: Attack simulation & detection engineering
- Week 7–8: Threat hunting & MITRE ATT&CK mapping
- Week 9–10: Incident analysis & final report
