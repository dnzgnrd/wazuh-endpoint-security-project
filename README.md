# wazuh-endpoint-security-project
Endpoint security monitoring and threat detection using Wazuh SIEM

🔐 Wazuh SIEM – Endpoint Security Project
📌 Project Overview

This project demonstrates endpoint security monitoring using Wazuh SIEM.
Malware activity and privilege escalation attempts are detected and analyzed in real time.

🏗️ Architecture

Wazuh Server: Ubuntu 22.04

Monitored Endpoint: Kali Linux

Agent Communication: Wazuh Agent

Security Tools: ClamAV, Linux audit logs

🚨 Implemented Security Scenarios
🔹 Scenario 1 – Malware Detection (EICAR Test File)

ClamAV antivirus installed on Kali Linux

EICAR test file created and scanned

Malware detection alert generated in Wazuh dashboard

MITRE ATT&CK mapping applied

🔹 Scenario 2 – Privilege Escalation Detection

.Sudo command used to gain root privileges

.Wazuh detected privilege escalation via system logs

.Alerts generated for:
  .Successful sudo to root

  .Root session opened

📊 Results
.Real-time security alerts successfully generated

.Endpoint activity monitored and logged

.Malware and privilege escalation events clearly detected

🧠 Key Learnings

.SIEM-based endpoint monitoring

.Malware detection integration

.Privilege escalation analysis

.Log-based threat detection

🛠️ Tools & Technologies

.Wazuh SIEM

.ClamAV

.Linux (Ubuntu & Kali)

.MITRE ATT&CK Framework

📌 Status

✅ Project completed and validated with real alerts

Successful sudo to root

Root session opened
