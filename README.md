<div align="center">

# 🛡️ Cybersecurity Home Lab

### Building a Practical Cybersecurity Learning Environment on Kali Linux

**Created by Brian Machayo (CypherOT)**

[![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Professional-red?style=for-the-badge)]()
[![Kali Linux](https://img.shields.io/badge/Kali_Linux-Latest-blue?style=for-the-badge&logo=kalilinux)]()
[![Linux](https://img.shields.io/badge/Linux-Administration-black?style=for-the-badge&logo=linux)]()
[![Networking](https://img.shields.io/badge/Networking-Security-green?style=for-the-badge)]()
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-181717?style=for-the-badge&logo=github)]()

</div>

---

# 📌 Project Overview

This repository documents the creation and configuration of my personal Cybersecurity Home Lab built on Kali Linux.

The lab serves as a dedicated environment for learning, experimenting, and developing practical skills in:

- Cybersecurity
- Ethical Hacking
- Network Security
- Linux Administration
- Vulnerability Assessment
- Security Automation
- Digital Forensics
- Cloud Security Fundamentals

The objective is to gain hands-on experience with industry-standard cybersecurity tools while documenting my learning journey and building a professional portfolio.

---

# 🎯 Project Objectives

The goals of this project include:

✅ Install and configure Kali Linux

✅ Build a stable cybersecurity workstation

✅ Configure network connectivity

✅ Install and test security tools

✅ Learn Linux system administration

✅ Practice network reconnaissance

✅ Develop ethical hacking skills

✅ Document configurations and findings

✅ Build a cybersecurity portfolio

---

# 💻 System Specifications

| Component | Details |
|------------|---------|
| Laptop | HP EliteBook 840 G5 |
| Processor | Intel Core i5 8th Generation |
| RAM | 16 GB |
| Storage | 512 GB SSD |
| Operating System | Kali Linux |
| Desktop Environment | XFCE |
| Terminal | Bash |
| Version Control | Git & GitHub |

---

# 🏗️ Lab Architecture

```text
+-------------------------+
|      Kali Linux         |
|-------------------------|
| Nmap                    |
| Wireshark               |
| Burp Suite              |
| Metasploit              |
| Gobuster                |
| Hydra                   |
| John The Ripper         |
+-----------+-------------+
            |
            |
      Internet Network
            |
      Target Systems
```

---

# 📷 Project Screenshots

## Kali Linux Desktop

![Kali Desktop](screenshots/kali-desktop.jpg)

---

## System Information

![System Information](screenshots/system-info.jpg)

---

## Network Configuration

![Network Configuration](screenshots/network-config.jpg)

---

## Security Tools Verification

![Tools Installed](screenshots/tools-installed.jpg)

---

## System Update Process

![System Update](screenshots/system-update.jpg)

---

# 🔧 Installed Security Tools

The following tools were installed and tested during this setup:

| Tool | Purpose |
|--------|----------|
| Nmap | Network Discovery & Scanning |
| Wireshark | Packet Analysis |
| Burp Suite | Web Security Testing |
| Metasploit Framework | Penetration Testing |
| Hydra | Password Auditing |
| Gobuster | Directory Enumeration |
| Nikto | Web Vulnerability Scanning |
| John The Ripper | Password Cracking |
| Netcat | Network Troubleshooting |
| Git | Version Control |

---

# 🔍 Verification Tests

## Check IP Address

```bash
ip a
```

---

## Verify Internet Connectivity

```bash
ping google.com
```

---

## Verify DNS Resolution

```bash
nslookup kali.org
```

---

## Verify Nmap Installation

```bash
nmap --version
```

---

## Verify Network Routing

```bash
ip route
```

---

# 📚 Skills Developed

Through this project I gained practical experience in:

### Linux Administration

- File management
- User permissions
- Package management
- Terminal operations

### Networking

- IP addressing
- DNS configuration
- Network troubleshooting
- Connectivity testing

### Cybersecurity Fundamentals

- Reconnaissance
- Vulnerability assessment
- Security tool installation
- Network analysis

### Documentation

- Technical writing
- GitHub project documentation
- Screenshot management
- Project organization

---

# ⚠️ Challenges Encountered

## Package Installation Issues

Some packages failed during installation due to repository synchronization issues.

### Solution

```bash
sudo apt update
sudo apt upgrade -y
```

Repository sources were verified and package indexes refreshed.

---

## Network Connectivity Problems

Network connectivity was occasionally unavailable after configuration changes.

### Solution

Verified:

```bash
ip a
```

```bash
ip route
```

```bash
ping 8.8.8.8
```

Connectivity was restored after reviewing interface settings.

---

# 🚀 Future Improvements

This lab will continue evolving as I progress in cybersecurity.

Planned additions include:

- Security Onion
- Splunk SIEM
- Active Directory Lab
- Vulnerable Machines
- OWASP Web Testing Lab
- Cloud Security Projects
- Python Security Automation
- Threat Hunting Exercises
- Digital Forensics Projects

---

# 🧠 Key Lessons Learned

This project reinforced several important cybersecurity concepts:

- The importance of Linux in cybersecurity
- Practical networking fundamentals
- Security tool deployment
- Documentation best practices
- Building repeatable lab environments
- Troubleshooting system and network issues

Most importantly, it provided a strong foundation for future cybersecurity and cloud security projects.

---

# 🔐 Ethical Use Statement

This project was created strictly for educational and research purposes.

All security testing activities should only be performed on:

- Systems you own
- Authorized lab environments
- Systems where explicit permission has been granted

Unauthorized testing of third-party systems is unethical and may be illegal.

---

# 🌐 Connect With Me

## Brian Machayo (CypherOT)

Applied Computer Science Student

Cybersecurity | Cloud Security | AI & Machine Learning

### GitHub

https://github.com/YOUR_USERNAME

### LinkedIn

https://linkedin.com/in/YOUR_LINKEDIN

---

# ⭐ Repository Goals

This repository is part of my journey toward becoming a professional:

- Cybersecurity Analyst
- Cloud Security Engineer
- SOC Analyst
- Security Researcher

I will continue updating this repository as new skills, tools, and projects are added.

---

<div align="center">

### 🛡️ Learn • Build • Secure • Document

**CypherOT**

</div>
