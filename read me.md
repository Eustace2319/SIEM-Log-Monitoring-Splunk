# SIEM Real-Time Monitoring & Attack Detection
**Project Goal:** Deploy a centralized logging pipeline using Splunk to detect unauthorized access attempts in a hybrid environment.

## 🛠️ Tech Stack
* **SIEM/Indexer:** Splunk Enterprise (Windows 11) - `192.168.1.229`
* **Security Sensor:** Kali Linux - `192.168.1.197`
* **Log Forwarder:** Splunk Universal Forwarder (Port 9997)

## 🛡️ Project Implementation
1. **Infrastructure:** Configured a Kali Linux sensor to monitor authentication logs.
2. **Data Pipeline:** Established a secure handshake between the Kali sensor and the Windows Indexer.
3. **Attack Simulation:** Performed a simulated SSH brute force attack to generate security telemetry.
4. **Analysis:** Identified a 5-hour timezone offset in logs, highlighting the critical need for NTP synchronization in a production SOC.

## 📊 Evidence & Documentation
For a full technical deep-dive, view the [Final Security Report](./SOC_Security_Report_Final.pdf).

> **Note:** This project demonstrates mastery of log ingestion, network troubleshooting, and security forensic analysis.