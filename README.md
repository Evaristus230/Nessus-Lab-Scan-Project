# Nessus Lab Scan Project

> *“I build realistic lab environments and automation tools that mirror real-world attack flows — because you can’t defend what you haven’t seen.”*

## 🎯 Objective
To perform comprehensive vulnerability assessments on a simulated enterprise network containing:
- Kali Linux (Attacker)
- Metasploitable 2 & 3 (Vulnerable Targets)
- Windows 10 (Enterprise Endpoint)

Using Tenable Nessus, I identified 123 vulnerabilities across 5 hosts, ranging from Critical (CVE-2025-40602) to Medium severity.

## 📊 Key Findings
- Host `192.168.56.102` had 136 total vulnerabilities — highest risk.
- Auth failures indicate misconfigured services or weak credentials.
- Remediation plan includes patching, service hardening, and firewall rules.



## 🔍 Methodology
1. Configured Nessus policy: “Basic Network Scan”
2. Scanned all 5 hosts in lab subnet
3. Exported results and analyzed CVSS v3.0 scores
4. Documented remediation steps per host

## 🛠️ Tools Used
- Tenable Nessus (Local Scanner)
- Kali Linux (Attack Platform)
- Metasploitable 2 & 3 (Targets)
- Windows 10 (Endpoint)


