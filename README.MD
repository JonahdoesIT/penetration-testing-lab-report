# 🛡️ Penetration Testing Lab Report

## 🧾 Project Overview

This project documents a hands-on penetration test against a simulated internal network environment using Kali Linux. The assessment targeted Ubuntu and Windows systems to uncover real-world exploitable vulnerabilities.

## 🎯 Objectives
- Exploit command injection on a web server
- Crack password hashes and use them to pivot
- Exploit unpatched Windows services using Metasploit
- Perform privilege escalation and extract sensitive data

## 🧰 Tools Used
- Nmap
- Command Injection
- Crackstation
- Metasploit + Meterpreter
- SSH Key Exploitation

## 🔍 Key Findings

| # | Severity | Description |
|--|----------|-------------|
| 1 | Medium | All systems visible via network scan |
| 2 | High | Windows machines outdated |
| 3 | High | Command-line injection vulnerable web server |
| 5 | High | Cracked SSH key used for remote access |
| 7 | High | Successful Meterpreter session w/ privilege escalation |

## 📂 Report
Read the full walkthrough here:
➡️ [View Report](report.pdf)
