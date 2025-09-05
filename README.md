# 🛡️ Cybersecurity Portfolio

Hands-on projects demonstrating skills in SOC, DFIR, Cloud Security, Pentest, and GRC.  
Each project includes setup steps, detections, hunts, measurable results, and mappings to security frameworks (MITRE ATT&CK, ASD Essential Eight, ISO/IEC 27001).

---

## 📂 Projects

### 1. [Home SOC: Threat Hunting & Detection Lab](01-home-soc/README.md) ✅ (In Progress)
- Ingested Windows Sysmon & Linux Zeek logs into Splunk Enterprise Free  
- Authored **5 custom detections** (PSExec, UAC bypass, encoded PowerShell, DNS tunneling, suspicious parent/child process)  
- Completed **2 hunts** (credential dumping via LSASS access, suspicious outbound data exfiltration)  
- Coverage mapped to **MITRE ATT&CK techniques**: T1021, T1059  

### 2. Incident Response Playbook & Drill 🚧 (Planned)
- Create IR playbook aligned with **ACSC + NIST guidance**  
- Run simulated **phishing-to-ransomware drill** in a lab environment  
- Measure improvement in MTTD/MTTR between first and second run  

### 3. Cloud Security Baseline (AWS) 🚧 (Planned)
- Deploy 3-tier demo app in AWS using Terraform  
- Identify misconfigurations (S3, IAM) with **Prowler/Checkov**  
- Remediate issues and configure **GuardDuty + CloudTrail alerts**  

---

## 📊 Portfolio Structure

cyber-portfolio/
01-home-soc/
README.md
detections/ # Sigma rules, SPL queries
hunts/ # hunt notes & queries
dashboards/ # screenshots of Splunk dashboards/alerts
results/ # metrics tables, ATT&CK mappings
02-ir-playbook/ # (planned)
03-cloud-baseline/ # (planned)


---

## 🎯 Focus Areas
- **SOC / Threat Hunting**: detection engineering, adversary emulation, log analysis  
- **Incident Response (IR/DFIR)**: playbooks, timelines, drills  
- **Cloud Security**: AWS security baseline, misconfiguration detection, IaC hardening  
- **GRC / Risk**: mapping to frameworks (ASD Essential Eight, APRA CPS 234, ISO 27001)  

---

## 🔗 Links
- [LinkedIn](https://www.linkedin.com/)  
- [GitHub Portfolio](https://github.com/your-username/cyber-portfolio)  
- [Demo Videos (YouTube/Drive/loom)](#)  

---

📌 *This portfolio is updated weekly with new projects and improvements.*
