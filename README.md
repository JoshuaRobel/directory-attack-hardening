# 🔒 Active Directory Attack and Hardening Lab

## 🧠 Overview
This project simulates real-world attacks against Active Directory and demonstrates defensive measures to secure an AD environment.

## 🎯 Objectives
- Enumerate users and permissions
- Perform a password spray attack
- Harden the domain against common attacks

## 🛠 Tools and Technologies Used
- BloodHound
- Mimikatz
- CrackMapExec
- Kali Linux
- Windows Server 2019 + Windows 10

## 🏗 Environment Setup
- Same AD lab environment as Lab 3
- Kali Linux attacker machine

## 🕵️‍♂️ Process
1. Conducted enumeration using BloodHound
2. Executed password spraying with CrackMapExec
3. Attempted credential dumping via Mimikatz
4. Applied hardening measures (e.g., disable LLMNR, deploy LAPS)

## 📷 Screenshots
- BloodHound graph
- Successful credential access

## 📄 Reports
- [Attack and Defense Report (PDF)](reports/ad-attack-hardening.pdf)

## 📚 Key Learnings
- Attack paths in corporate environments
- Credential theft techniques
- Implementing AD security best practices

## 🔗 References
- [BloodHound Docs](https://bloodhound.readthedocs.io/)
- [Microsoft LAPS](https://learn.microsoft.com/en-us/windows-server/identity/laps/laps-overview)
