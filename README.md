
# Cyber Range Vulnerability Assessment using Tenable

## 🔍 Overview
This project documents a vulnerability assessment conducted on a virtual Windows machine using Tenable.io with both authenticated and unauthenticated scans in a controlled cyber range environment.

## 🛠️ Environment Setup
- **Platform**: Virtual Windows 10 Pro
- **Instance Specs**: Standard DS1_v2, 1 vCPU, 3.5 GiB memory, Standard HDD, Locally Redundant Storage (LRS)
- **Network**: Cyber Range VNet with subnet 10.0.0.0/21

- ## 🎯 Objectives
- Identify and analyze vulnerabilities in a virtual Windows system
- Compare scan results from authenticated vs. unauthenticated scans
- Perform a risk assessment based on NIST SP 800-30 and CVSS scores
- Provide actionable recommendations for mitigation and continuous monitoring

## 🧰 Tools & Technologies
- **Tenable.io / Tenable.sc**
- **Internal Scanner**
- **Windows 10/11 Virtual Machine**
- **National Vulnerability Database (NVD)**
- **NIST Cybersecurity Framework (CSF)**


## 🔍 Scan Methodology
- **Authenticated Scan**: Performed with valid credentials to simulate insider access
- **Unauthenticated Scan**: Simulated external attacker with no credentials
- **Scan Targets**: Virtual Windows machine configured with common services



## 📊 Scan Results Summary
- Total Vulnerabilities: XX
- Critical: X | High: X | Medium: X | Low: X
- Top 3 CVEs:
  - CVE-XXXX-XXXX
  - CVE-YYYY-YYYY
  - CVE-ZZZZ-ZZZZ

## 🧠 Risk Assessment
- Based on NIST SP 800-30 and NVD CVSS scores
- Risk levels assigned using Risk Management Hierarchy Tiers
### Network Architecture Diagram
![Network Architecture Diagram](network_architecture_diagram.png)



## 🛡️ Recommendations
- Patch critical vulnerabilities immediately
- Apply secure configuration baselines
- Implement continuous monitoring (SIEM, endpoint detection)

## 📄 Full Report
See `Management_Report.pdf` for the full threat analysis, risk assessment, and recommendations.
