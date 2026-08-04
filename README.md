# Uzhiyekachi Alan Ezekwem-Cybersecurity-Portfolio
Cybersecurity Engineer | SOC Analyst | Detection Engineering | Wazuh SIEM | Sysmon Telemetry | Threat Emulation | Blue-Team Research

A personal cybersecurity portfolio showcasing SOC labs, SIEM deployments, Sysmon telemetry, threat detection, and hands-on security engineering projects.

I am a cybersecurity engineer focused on SOC operations, SIEM deployment, endpoint
telemetry and adversarial simulation. My work centers on building real-world
detection pipelines using Wazuh SIEM/XDR, Sysmon, Windows event telemetry, and
controlled brute-force attack simulations.

This GitHub portfolio contains my personal cybersecurity projects, SOC labs, SIEM
deployments, and hands-on detection engineering work.

---
## 📑 Table of Contents
- [Summary](#summary)
- [About Me](#about-me)
- [Technical Skills](#technical-skills)
  - [SOC & SIEM](#soc--siem)
  - [Threat Emulation](#threat-emulation)
  - [Endpoint Telemetry](#endpoint-telemetry)
  - [Tools & Platforms](#tools--platforms)
- [Featured Project: Wazuh SOC SIEM Lab](#featured-project-wazuh-soc-siem-lab)
  - [Detection Highlights](#detection-highlights)
  - [Troubleshooting Achievements](#troubleshooting-achievements)
- [Current Focus](#current-focus)
- [Contact](#contact)
- [Purpose of This Portfolio](#purpose-of-this-portfolio)
- [Screenshot Documentation](#screenshot-documentation)
  - [Advanced Wazuh SIEM Threat‑Hunting Lab Environment](#advanced-wazuh-siem-threathunting-lab-environment)
  - [Hydra Attack Output — July 16, 2026](#hydra-attack-output--attacker-vm-july-16-2026png)
  - [Hydra Attack Output — July 19, 2026](#hydra-attack-output--attacker-vm-july-19-2026png)
  - [Sysmon Detection — Rule 92217](#sysmon-detection--rule-92217-executable-dropped-non-service-account-logged-off--local-service-log-onpng)
  - [Full SOC Lab Environment Running](#ubuntu-siem-server-running-win-10vm-running-attcker--vm-wazuh-dashboard--threat-huntingpng)
  - [Wazuh Threat Hunting — Rule 60204 (July 16)](#wazuh-threat-hunting--rule-60204-july-16-2026-severity-10png)
  - [Wazuh Threat Hunting — Rule 60204 (July 19)](#wazuh-threat-hunting--rule-60204-july-19-2026-severity-10png)
  - [Windows Endpoint Telemetry Validation](#windows-endpoint-telemetry-validation-using-sysmon--powershellpng)

## About Me
- SOC Analyst (Beginner–Intermediate)
- Cybersecurity student at LaGuardia Community College
- Full‑Stack Software Engineering Micro‑Credential (Queensborough Community College)
- Lead engineer for NexaShield Group LLC research labs
- Experienced with Wazuh SIEM/XDR deployment and tuning
- Skilled in Windows endpoint telemetry (Sysmon + Event Logs)
- Comfortable with threat emulation using Hydra and PowerShell
- Strong troubleshooting background in Filebeat, certificates, and log ingestion
- Focused on blue-team operations, detection engineering, and SIEM architecture

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
**Email:** alancybershield@gmail.com
**Location:** Brooklyn, NY  
**GitHub:** https://github.com/alancybershield-spec/Alan-Cybersecurity-Portfolio
**Company:** NexaShield Group LLC  

## 📄 Resume
You can view or download my full cybersecurity resume here:
👉 [Resume.pdf](https://github.com/alancybershield-spec/UE cyberresume.pdf)
👉 [Resume.md](https://github.com/alancybershield-spec/Uzhiyekachi-Alan-Ezekwem-Resume/blob/main/resume.md)

## Purpose of This Portfolio

This repository serves as my personal cybersecurity portfolio, documenting my
hands-on SOC labs, SIEM deployments, detection engineering work, and continuous
learning in blue-team operations.

All projects are built, tested, broken, repaired, and validated inside live
multi-VM environments to reflect real-world SOC workflows.

##  Screenshot Documentation

### Advanced Wazuh SIEM Threat‑Hunting Lab Environment.png 
This setup demonstrates a fully operational cybersecurity lab built with VirtualBox, featuring an Ubuntu‑based Wazuh SIEM server, a Windows 10 endpoint, and an attacker VM. The screenshot highlights active threat‑hunting within Wazuh, showing real‑time Windows event logs such as non‑service account logoffs and privilege‑assignment events. Together, the environment validates agent deployment, log ingestion, rule triggering, and SOC analysis workflows.

### Hydra Attack Output — Attacker VM July 16 2026.png
This screenshot shows Hydra performing a brute‑force attack against the Windows RDP
service at 192.168.56.4:3389. Hydra attempted thousands of login combinations using
the rockyou.txt wordlist. Although no valid password was found, the attack generated
high‑volume failed authentication events that were successfully detected by Wazuh.

### Hydra Attack Output — Attacker VM July 19 2026.png
This screenshot also shows Hydra performing a brute‑force attack against the Windows RDP
service at 192.168.56.4:3389 on a different date and time. Hydra attempted thousands of login combinations using
the rockyou.txt wordlist. Although no valid password was found, the attack generated
high‑volume failed authentication events that were successfully detected also by Wazuh.

### Sysmon Detection — Rule 92217 (Executable Dropped) non service account logged off , local service log on.png
This screenshot shows Sysmon detecting a file creation event triggered by PowerShell.
Rule 92217 (Executable dropped in Windows root folder) confirms that Sysmon is
installed correctly, Wazuh is ingesting Sysmon logs, and file creation events are
being monitored. Additional logon/logoff events demonstrate endpoint telemetry flow.

### Ubuntu siem server running, win-10vm running, attcker- vm, wazuh dashboard , threat hunting.png
This screenshot shows the full SOC lab environment running simultaneously:
- Ubuntu SIEM server (Wazuh Manager)
- Windows 10 endpoint with Wazuh agent and Sysmon
- Attacker VM running Hydra
- Wazuh Dashboard displaying Threat Hunting alerts
This validates the multi‑VM architecture and confirms all components were active
during the attack and detection workflow.

### Wazuh Threat Hunting — Rule 60204 July 16 2026 (Severity 10).png
This screenshot shows Wazuh detecting a high‑severity brute‑force attack. Rule 60204
(Multiple Windows Logon Failures) is triggered when Wazuh correlates a rapid sequence
of failed login attempts within a short time window. This confirms that the SIEM
correctly aggregated individual 4625 events into a single brute‑force alert.

### Wazuh Threat Hunting — Rule 60204 July 19 2026 (Severity 10).png
This screenshot also shows Wazuh detecting a high‑severity brute‑force attack on a different date and time. Rule 60204
(Multiple Windows Logon Failures) is triggered when Wazuh correlates a rapid sequence
of failed login attempts within a short time window. This confirms that again, the SIEM
correctly aggregated individual 4625 events into a single brute‑force alert.

### Windows Endpoint Telemetry Validation Using Sysmon & PowerShell.png
This screenshot captures part of my cybersecurity home lab where I validate Windows telemetry before forwarding it to Wazuh SIEM. Using PowerShell, I queried the Sysmon Operational log to inspect recent security‑relevant events such as process creation, DNS queries, registry modifications, file creation, and network connections. This step ensures Sysmon is correctly installed, configured, and generating high‑fidelity data needed for threat detection and SOC analysis.
