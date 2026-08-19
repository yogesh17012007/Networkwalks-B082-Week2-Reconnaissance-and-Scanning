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

👉 [SCREENSHOTS]
<img width="1400" height="835" alt="WK2-PM1-TASK 1 My result of whois png" src="https://github.com/user-attachments/assets/036b8412-535c-44ff-802e-ecfcccb92480" />
<img width="1600" height="819" alt="WK2-PM1-TASK 2 My result of whatweb PNG" src="https://github.com/user-attachments/assets/ba9e4261-6660-416b-89a8-893883c5f261" />
<img width="1600" height="819" alt="WK2-PM1-TASK 3 my result of nslookup png" src="https://github.com/user-attachments/assets/9bf2263e-dfea-4452-99bc-7d6d20d9d2f1" />
<img width="1600" height="819" alt="WK2-PM1-TASK 4 my result of curl png" src="https://github.com/user-attachments/assets/cf715ed7-96ad-40f3-942d-803ca7e2c5f3" />
<img width="1600" height="819" alt="WK2-PM1-TASK 5 my result of wafw00f png" src="https://github.com/user-attachments/assets/ebf07cf7-f319-424e-a011-2a24747bc084" />
<img width="1600" height="819" alt="WK2-PM1-TASK 6 My result of  dnsrecon png" src="https://github.com/user-attachments/assets/1f016f3c-5b66-4e43-ad32-9e9facfd7ada" />





- whois
- nslookup
- WhatWeb
- curl
- wafw00f
- DNSRecon

### 🌐 W2-PM2 — Google Dorking

**Focus:** Search-engine-based OSINT.

👉 [Open Module 2]([https://github.com/user-attachments/files/31234657/W2-PM2.-.Week2.-.Project.Module2.-.Footp.with.GHDB.v1.-.TABLES.to.fill.docx)
/README.md)](https://github.com/yogesh17012007/Networkwalks-B082-Week2-Reconnaissance-and-Scanning/tree/main/WK2-PM2-FOOTPRINTING%20%26%20RECONNAISSANCE%20%20ATTACKS%20WITH%20GHDB)

### 🕸️ W2-PM3 — Infrastructure Mapping

*Focus:* Graph-based OSINT and relationship mapping.

👉 [Open Module 3]([WK2-PM3-FOOTPRINTING WITH MALTEGO.docx](https://github.com/user-attachments/files/31234822/WK2-PM3-FOOTPRINTING.WITH.MALTEGO.docx)
)

### 🕵️ W2-PM4 — OSINT Aggregation

**Focus:** Passive information gathering using theHarvester.

👉 [Open Module 4](<img width="1600" height="818" alt="WK2-PM4-TASK2(theHarvester) png" src="https://github.com/user-attachments/assets/ac483b6a-3589-42b5-9cda-fc34155f7dba" />
<img width="1600" height="818" alt="WK2-PM4-TASK 1(theHarvester) find email ID   sub-domain png" src="https://github.com/user-attachments/assets/51d6beec-ca6e-42fc-b088-5d3ac7b98804" />
)
### 🖥️ W2-PM5 — Local Network Scanning

*Focus:* Host discovery and network mapping.

👉 [Open Module 5](<img width="1919" height="1080" alt="Screenshot 2026-08-19 194445" src="https://github.com/user-attachments/assets/6194b90e-6aea-4c34-9ce7-7f7327b1667e" />
<img width="1919" height="1080" alt="Screenshot 2026-08-19 194534" src="https://github.com/user-attachments/assets/1a203668-c1d2-4373-b83a-6271f122bb8b" />
)

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
