# VulnTrack

> End-to-end vulnerability management implementation aligned with PCI-DSS, ISO 27001, and NIST best practices.

## 🎯 Mission

This project demonstrates a complete vulnerability management lifecycle in a controlled home lab, simulating the work of a vulnerability analyst at a financial services organization. The goal is to find, prioritize, remediate, and report on vulnerabilities across a multi-platform environment including Linux, Windows, web applications, and cloud infrastructure.

## 📊 What's Inside

- **Lab Environment** — Vulnerable VMs and cloud assets including Metasploitable, OWASP Juice Shop, unpatched Windows 10, Ubuntu Server, and a deliberately misconfigured AWS Free Tier account
- **Scan Results** — Output from multiple scanners (Nessus Essentials, OpenVAS, Nuclei, Nmap NSE, Nikto) with comparison notes
- **Vulnerability Register** — Structured tracking of every finding with CVE, CVSS v3.1 score, EPSS score, business impact rating, remediation owner, SLA, and current status
- **Validation Notes** — Manual verification of findings, including confirmation of true positives via Metasploit and documentation of false positives
- **Remediation Evidence** — Before/after screenshots and rescan results for remediated vulnerabilities
- **External Attack Surface** — Documentation of internet-facing asset discovery using subfinder, amass, and certificate transparency
- **Dashboards & Reports** — Visualizations of vulnerability trends, risk posture, and SLA compliance

## 🛠️ Tools Used

- **Scanners:** Nessus Essentials, OpenVAS / Greenbone, Nuclei, Nmap (NSE), Nikto
- **Cloud Security:** Prowler, ScoutSuite, AWS Security Hub
- **External Recon:** subfinder, amass, crt.sh, Shodan
- **Validation:** Metasploit Framework
- **Reporting:** Google Sheets / Power BI Desktop

## 📋 Frameworks & Compliance

- PCI-DSS Requirement 11.3 (Vulnerability Scanning)
- ISO 27001 A.12.6.1 (Management of Technical Vulnerabilities)
- NIST SP 800-30 (Risk Assessment)
- NIST SP 800-40 (Patch Management)
- CVSS v3.1, EPSS

## Status

Active development.

## Contact

Built as part of an entry-level cybersecurity portfolio. Open to feedback and opportunities.
