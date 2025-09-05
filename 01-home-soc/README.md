# Home SOC: Threat Hunting and Detection Lab
# 🏠 Home SOC: Threat Hunting & Detection Lab

## 🎯 Objective
Build a mini SOC by ingesting Sysmon & Zeek logs into Splunk, authoring detections, and performing hunts mapped to MITRE ATT&CK.

---

## 🏗️ Architecture
- Host: Windows 10 Home running Splunk Enterprise Free
- VM1: Windows 10 Pro (Sysmon + Universal Forwarder)
- VM2: Ubuntu Server (Zeek + Universal Forwarder)

📌 [Insert architecture diagram or screenshot here]

---

## ⚙️ Setup Highlights
- Installed **Sysmon** with modular config
- Forwarded logs from Windows & Ubuntu into Splunk
- Indexed into Splunk (`sysmon`, `zeek`)

---

## 🔍 Detections
- PSExec lateral movement → [`detections/psexec_sigma.yml`](detections/)
- Encoded PowerShell commands → [`detections/powershell_encoded.spl`](detections/)
- UAC bypass attempts → [`detections/uac_bypass.spl`](detections/)
- DNS tunneling (Zeek) → [`detections/dns_tunnel.spl`](detections/)
- Suspicious parent/child process (`winword.exe → cmd.exe`)

---

## 🕵️ Threat Hunts
- Credential dumping via LSASS access  
- Suspicious outbound data exfiltration (Zeek `conn.log`)

📄 Hunt notes are in [`hunts/`](hunts/).

---

## 📊 Results
- 5 custom detections firing in Splunk
- 2 successful hunts completed
- Coverage mapped to MITRE ATT&CK techniques: T1021, T1059

📸 [Insert detection screenshots here]

---

## 📹 Demo
A 5–7 min walkthrough video (attack → detection → hunt).  
🔗 [Demo link will go here]
