# 📊 APT34 (OILRIG) Threat Intelligence Report

<div align="center">

![Classification](https://img.shields.io/badge/Classification-CONFIDENTIAL-red?style=for-the-badge)
![Threat Level](https://img.shields.io/badge/Threat%20Level-HIGH-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Report%20Status-FINAL-green?style=for-the-badge)

**Prepared for:** Client Leadership Team  
**Prepared by:** Bikash Raya, Cybersecurity Consultant  
**Date:** December 2023  

</div>

---

## 📑 Table of Contents
- Executive Summary  
- Threat Actor Profile  
- History & Timeline  
- Nation-State Attribution  
- Targeted Industries  
- Motives  
- Tactics, Techniques & Procedures (TTPs)  
- MITRE ATT&CK Mapping  
- Recommended Security Measures  
- Conclusion  

---

## 📋 Executive Summary

APT34 (also known as OILRIG) is a **state-sponsored cyber espionage group attributed to Iran**. The group has been active since 2014 and is primarily focused on intelligence collection targeting government, energy, telecommunications, and critical infrastructure sectors.

### Key Highlights
- State-sponsored Iranian threat actor  
- Active since 2014  
- Primary objective: cyber espionage  
- Techniques: spear-phishing, custom malware, credential theft  
- Risk Level: 🔴 HIGH  

---

## 👤 Threat Actor Profile

| Attribute | Details |
|----------|--------|
| Primary Name | APT34 |
| Aliases | OILRIG, Helix Kitten, Crambus, Hazel Sandstorm |
| Origin | Iran 🇮🇷 |
| Type | State-Sponsored |
| First Observed | 2014 |
| Sophistication | High |
| Motivation | Espionage |

---

## 📜 History & Timeline

APT34 has demonstrated long-term persistence and evolution in its operations.

### Activity Timeline

- **2014** → Initial discovery and early phishing campaigns  
- **2015–2016** → Expansion of spear-phishing operations across Middle East  
- **2017–2019** → Deployment of custom malware and improved persistence techniques  
- **2020–2022** → Enhanced stealth, credential harvesting, and lateral movement  
- **2023–Present** → Continued espionage operations with broader targeting scope  

---

## 🌍 Nation-State Attribution

### 🇮🇷 Iran

APT34 is widely attributed to Iranian state-sponsored cyber operations.

### Supporting Indicators
- Activity aligns with Iran timezone and working hours  
- Target selection aligns with Iranian geopolitical interests  
- Shared infrastructure with other Iranian APT groups  
- Consistent focus on Middle Eastern intelligence gathering  

---

## 🏭 Targeted Industries

| Industry | Priority | Objective |
|----------|----------|----------|
| Government | Critical | Political intelligence |
| Energy | High | Strategic infrastructure access |
| Telecommunications | High | Communications interception |
| Critical Infrastructure | High | National security insights |
| Financial Services | Medium | Economic intelligence |
| Technology | Medium | Intellectual property theft |

### 🌐 Geographic Focus
- **Primary:** Saudi Arabia, UAE, Qatar, Kuwait, Israel  
- **Secondary:** United States, Europe, Asia-Pacific regions  

---

## 🎯 Motives

APT34 operates primarily for **cyber espionage purposes**.

| Objective | Description |
|----------|------------|
| Intelligence Gathering | Political and military intelligence |
| Economic Espionage | Trade secrets and corporate data theft |
| Strategic Advantage | Supporting Iranian state objectives |
| Infrastructure Mapping | Reconnaissance of critical systems |

---

## ⚔️ Tactics, Techniques & Procedures (TTPs)

### Attack Lifecycle

Recon → Weaponization → Delivery → Exploitation → Installation → Command & Control → Exfiltration

### Core Techniques

| Tactic | Technique |
|--------|----------|
| Initial Access | Spear-phishing emails |
| Execution | PowerShell, malicious macros |
| Persistence | Scheduled tasks, registry keys |
| Defense Evasion | Obfuscation and encoding |
| Credential Access | Memory dumping, credential theft |
| Lateral Movement | RDP, SMB protocols |
| Exfiltration | C2 communication channels |

---

### Known Malware & Tools

| Tool | Type | Purpose |
|------|------|--------|
| POWRUNER | Backdoor | Remote system access |
| BONDUPDATER | Backdoor | Persistent access |
| QUADAGENT | C2 Tool | Command communication |
| VALUEVAULT | Credential Stealer | Password extraction |
| PICKPOCKET | Browser Stealer | Saved credential theft |

---

## 🗺️ MITRE ATT&CK Mapping

- T1566 → Spearphishing  
- T1059.001 → PowerShell Execution  
- T1078 → Valid Accounts  
- T1003 → Credential Dumping  
- T1027 → Obfuscated Files/Information  
- T1021 → Remote Services  
- T1041 → Exfiltration Over C2 Channel  
- T1053 → Scheduled Task Persistence  

---

## 🛡️ Recommended Security Measures

### 🔍 Detection & Monitoring
- Deploy EDR solutions across endpoints  
- Implement SIEM for centralized logging  
- Integrate threat intelligence feeds  

### 📧 Email Security
- Advanced phishing detection  
- Sandbox analysis for attachments  

### 🔒 Network Security
- Enforce network segmentation  
- Restrict lateral movement paths  

### 🔄 Patch Management
- Critical systems: 24–48 hours  
- Standard systems: within 7 days  

### 📋 Incident Response
- Maintain IR playbooks  
- Conduct regular simulations  
- Ensure rapid containment procedures  

### 🔐 Security Hardening
- Multi-Factor Authentication (MFA)  
- Zero Trust Architecture  
- Data Loss Prevention (DLP)  
- Privileged Access Management (PAM)  

---

## 📌 Conclusion

APT34 remains a **highly capable and persistent state-sponsored threat actor**. Their focus on long-term espionage campaigns makes them a significant risk to government and enterprise environments.

### Key Security Priorities
- Strengthen identity and email security  
- Deploy endpoint detection and response  
- Enforce strict network segmentation  
- Adopt Zero Trust principles  
- Maintain continuous threat intelligence monitoring  

---

## 📄 Report Metadata

**Prepared By:** Bikash Raya  
**Role:** Cybersecurity Consultant  
**Classification:** CONFIDENTIAL  
**Distribution:** Internal Use Only  
