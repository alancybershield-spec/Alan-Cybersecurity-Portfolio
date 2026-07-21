# Uzhiyekachi Alan Ezekwem-Cybersecurity-Portfolio
Cybersecurity Engineer | SOC Analyst | Detection Engineering | Wazuh SIEM | Sysmon Telemetry | Threat Emulation | Blue-Team Research

A Personal cybersecurity portfolio showcasing SOC labs, SIEM deployments, Sysmon telemetry, threat detection, and hands-on security engineering projects.

I am a cybersecurity engineer focused on SOC operations, SIEM deployment, endpoint
telemetry, and adversarial simulation. My work centers on building real-world
detection pipelines using Wazuh SIEM/XDR, Sysmon, Windows event telemetry, and
controlled brute-force attack simulations.

This GitHub portfolio contains my personal cybersecurity projects, SOC labs, SIEM
deployments, and hands-on detection engineering work.

---

## About Me

- SOC Analyst (Beginner–Intermediate)
- Cybersecurity student at LaGuardia Community College
- Lead engineer for NexaShield Group LLC research labs
- Experienced with Wazuh SIEM/XDR deployment and tuning
- Skilled in Windows endpoint telemetry (Sysmon + Event Logs)
- Comfortable with threat emulation using Hydra and PowerShell
- Strong troubleshooting background in Filebeat, certificates, and log ingestion
- Focused on blue-team operations, detection engineering, and SIEM architecture

---

## Technical Skills

### SOC & SIEM
- Wazuh SIEM/XDR deployment
- Log ingestion engineering (Filebeat, Sysmon, Windows logs)
- Threat hunting dashboards
- Correlation rule analysis (60204, 60122, 60115, 92217)
- Endpoint agent deployment and troubleshooting

### Threat Emulation
- Hydra brute-force simulation (RDP, SSH)
- PowerShell abuse and file creation tests
- Credential-stuffing detection
- Attack surface analysis (RDP, authentication logs)

### Endpoint Telemetry
- Sysmon configuration and event analysis
- Windows Security Event Log parsing
- Behavioral detection engineering

### Tools & Platforms
- Wazuh Manager, Wazuh Dashboard
- VirtualBox multi-VM lab environments
- Ubuntu Server, Windows 10
- PowerShell, Bash
- GitHub for documentation and portfolio building

---

## Featured Project: Wazuh SOC SIEM Lab

A complete SOC pipeline built from scratch:

- Attacker VM (Ubuntu) running Hydra
- Windows endpoint with Sysmon + Wazuh agent
- Wazuh Manager receiving and correlating logs
- Threat Hunting dashboard showing real-time alerts

### Detection Highlights
- Rule 60122 — Failed Password (Event ID 4625)
- Rule 60204 — Multiple Logon Failures (Severity 10)
- Rule 60115 — Account Locked Out (Event ID 4740)
- Rule 92217 — Executable Dropped (Sysmon FileCreate)

### Troubleshooting Achievements
- Fixed Filebeat certificate mismatches
- Repaired broken log ingestion pipeline
- Reinstalled and reconnected Wazuh agent
- Validated Sysmon telemetry ingestion
- Restored full SIEM functionality

This project demonstrates real-world SOC engineering, not just theory.

---

## Current Focus

- Detection engineering
- SIEM architecture and tuning
- Endpoint monitoring
- Threat emulation
- SOC analyst skill development
- Preparing for CompTIA Security+

---

## Contact

**Name:** Uzhiyekachi Alan Ezekwem
Email: alancybershield@gmail.com
**Location:** Brooklyn, NY  
**GitHub:** https://github.com/alancybershield-spec/Alan-Cybersecurity-Portfolio
**Company:** NexaShield Group LLC  

---

## Purpose of This Portfolio

This repository serves as my personal cybersecurity portfolio, documenting my
hands-on SOC labs, SIEM deployments, detection engineering work, and continuous
learning in blue-team operations.

All projects are built, tested, broken, repaired, and validated inside live
multi-VM environments to reflect real-world SOC workflows.
