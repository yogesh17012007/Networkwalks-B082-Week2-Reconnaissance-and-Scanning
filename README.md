# Networkwalks-B082-Week2-Reconnaissance-and-Scanning

# 🛡️ Cybersecurity Reconnaissance & Network Scanning

## NetworkWalks Cybersecurity Internship – Week 2

*Phase 1:* Reconnaissance & Footprinting  
*Phase 2:* Scanning & Network Discovery

---

## 📌 Project Overview

This repository documents my Week 2 cybersecurity internship activities
covering reconnaissance, OSINT, footprinting and authorized network scanning.

The project focuses on:

- 🔎 Reconnaissance & Footprinting
- 🌐 Open-Source Intelligence (OSINT)
- 🕵️ Web Technology Fingerprinting
- 🔍 Search Engine Reconnaissance
- 🕸️ Infrastructure Mapping
- 🖥️ Internal Network Discovery
- 🗺️ Network Topology Mapping

All activities were performed only within an authorized
educational environment and against systems/networks for which
permission was available.

## 🧰 Tools & Technologies

| Category | Tools |
|---|---|
| Security OS | Kali Linux |
| Operating System | Windows |
| Domain Reconnaissance | whois, nslookup |
| Web Fingerprinting | WhatWeb |
| HTTP Analysis | curl |
| WAF Detection | wafw00f |
| DNS Enumeration | DNSRecon |
| Search Engine Recon | Google Dorking |
| OSINT & Entity Mapping | Maltego |
| OSINT Aggregation | theHarvester |
| Network Discovery | Nmap |
| Network Visualization | Zenmap |

## 📂 Repository Structure

```text
├── W2-PM1-Kali-Linux-Footprinting/
├── W2-PM2-GHDB-Google-Dorking/
├── W2-PM3-Infrastructure-Mapping-Maltego/
├── W2-PM4-OSINT-theHarvester/
├── W2-PM5-Local-Network-Scanning/
│
└── W2-FINAL-REPORT/
    ├── Penetration-Testing-Report.pdf
    └── Authorization.pdf
```
---
## 🧭 Module Navigation

### 🔎 W2-PM1 — Kali Linux Footprinting

**Focus:** Reconnaissance and footprinting in an authorized environment.

👉 [Open Module 1](./W2-PM1-Kali-Linux-Footprinting/R)

**Tools Used:**

- whois
- nslookup
- WhatWeb
- curl
- wafw00f
- DNSRecon

### 🌐 W2-PM2 — Google Dorking

**Focus:** Search-engine-based OSINT.

👉 [Open Module 2](./W2-PM2-GHDB-Google-Dorking/README.md)

### 🕸️ W2-PM3 — Infrastructure Mapping

*Focus:* Graph-based OSINT and relationship mapping.

👉 [Open Module 3](./W2-PM3-Infrastructure-Mapping-Maltego/README.md)

### 🕵️ W2-PM4 — OSINT Aggregation

**Focus:** Passive information gathering using theHarvester.

👉 [Open Module 4](./W2-PM4-OSINT-theHarvester/README.md)
### 🖥️ W2-PM5 — Local Network Scanning

*Focus:* Host discovery and network mapping.

👉 [Open Module 5](./W2-PM5-Local-Network-Scanning/README.md)

## 🔎 Key Findings

- Identified domain information.
- Performed DNS enumeration.
- Fingerprinted web technologies.
- Analyzed HTTP response headers.
- Performed authorized network discovery.
- Identified active hosts in the lab network.
- Created a basic network topology.

## 🎯 Target Network

```text
10.0.0.0/24

🔎 Host Discovery
The authorized lab network was scanned to identify active hosts.
nmap -sn 10.0.0.0/24
Results
IP Address
Status
10.0.0.1
Active
```

**Only scan your own/authorized lab network.**

---

# workflow


```markdown
## 🔄 Penetration Testing Workflow
START
  │
  ▼
Reconnaissance & Footprinting
  │
  ▼
Kali Linux Recon Tools
  │
  ▼
OSINT / Google Dorking
  │
  ▼
Maltego Infrastructure Mapping
  │
  ▼
theHarvester OSINT
  │
  ▼
Nmap / Zenmap Network Discovery
  │
  ▼
Host Identification & Topology Mapping
  │
  ▼
END
```
---
```
# 10. Add Key Learning Outcomes
markdown
## 🧠 Key Learning Outcomes

```
Through these modules, I developed practical understanding of:

- Active and passive reconnaissance
- Domain and DNS enumeration
- Web technology fingerprinting
- WAF identification
- Search-engine reconnaissance
- Graph-based OSINT
- Metadata and OSINT aggregation
- Email and subdomain enumeration
- Network host discovery
- Network topology mapping
- Security finding documentation
- Risk identification
- Ethical and authorized security testing
```
```
## ⚠️ Risk Observations

### 🟠 Information Exposure

Publicly available information can help an attacker understand
the organization's technology and infrastructure.

### 🟠 DNS Information Exposure

DNS records may reveal information about infrastructure and services.

### 🔴 Publicly Indexed Resources

Sensitive resources should not be unintentionally exposed
through search engines.

### 🟢 Internal Host Visibility

Unauthorized devices on internal networks should be investigated
and monitored.

## 🛡️ Recommendations

Organizations should consider:

- Regularly reviewing publicly exposed information.
- Keeping software and plugins updated.
- Properly configuring Web Application Firewalls.
- Reviewing DNS records.
- Removing unnecessary public services.
- Monitoring exposed email addresses and subdomains.
- Maintaining an accurate internal asset inventory.
- Investigating unknown devices on internal networks.
## ⚖️ Legal & Ethical Disclaimer

All reconnaissance, OSINT, footprinting and network-scanning
activities documented in this repository were performed only
within an authorized educational environment or against systems
owned and controlled by the tester.

This repository is intended for:

- 🎓 Cybersecurity education
- 🔬 Security research
- 🛡️ Authorized penetration testing
- 🔐 Defensive security learning

⚠️ Never use the tools, commands or techniques documented here
against systems or networks without explicit authorization.

Unauthorized security testing may violate laws, regulations,
organizational policies and terms of service.

## 📚 Project Information

| Field | Details |
|---|---|
| Program | NetworkWalks Cybersecurity Internship |
| Batch | Your Batch |
| Week | 02 |
| Project | Cybersecurity Reconnaissance & Network Scanning |
| Phase 1 | Reconnaissance & Footprinting |
| Phase 2 | Scanning & Network Discovery |
| Author | Yogesh V |
| Assessment Date | 19 August 2026 |


## 👤 Author

**Yogesh V**

BE  Cybersecurity Student

### Interests

- Cybersecurity
- Ethical Hacking
- Network Security
- Penetration Testing
- Digital Forensics

---

## ⭐ Acknowledgement

This project was completed as part of my cybersecurity learning
journey and helped me develop practical knowledge of reconnaissance,
OSINT and network discovery.

**Learn responsibly. Test ethically. Document professionally.**

🛡️ Cybersecurity Reconnaissance & Network Scanning
```
NetworkWalks Cybersecurity Internship – Week 2

├── 📌 Project Overview
├── 🎯 Project Objectives
├── 🧰 Tools & Technologies
├── 📂 Repository Structure
├── 🧭 Module Navigation
│
├── 🔎 PM1 – Kali Linux Footprinting
├── 🌐 PM2 – Google Dorking
├── 🕸️ PM3 – Maltego
├── 🕵️ PM4 – theHarvester
├── 🖥️ PM5 – Nmap / Zenmap
│
├── 🔄 Penetration Testing Workflow
├── 📊 Key Findings
├── ⚠️ Risk Observations
├── 🧠 Key Learning Outcomes
├── 📸 Evidence & Screenshots
├── 📄 Final Deliverable
├── 🛡️ Recommendations
├── ⚖️ Legal & Ethical Disclaimer
├── 📚 Project Information
└── 👤 Author
```
