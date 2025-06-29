# SIEM-Deployment-Threat-Detection-Wazuh-ELK-Log-Analysis
A SIEM deployment project focused on log analysis, threat detection, and security monitoring using Wazuh, ELK Stack, and correlation rules.
# 🔥 SIEM Deployment & Threat Detection

This project demonstrates how to deploy and configure a Security Information and Event Management (SIEM) solution to monitor logs, detect threats, and respond to security incidents in real-time.

---

## 📜 Overview
A SIEM is a critical component for modern cybersecurity operations. This project covers setting up a SIEM (using Wazuh, ELK Stack, or Graylog) to collect logs from different sources, build detection rules, visualize threat activity, and generate alerts for suspicious behavior.

---

## 🛠️ Tools & Technologies
- Wazuh SIEM or ELK Stack (Elasticsearch, Logstash, Kibana)
- Graylog (Optional alternative)
- Splunk Free (for demonstration purposes)
- Log sources: Windows, Linux, Firewalls, VPNs
- Security Onion (optional for testing)

---

## 🔍 Process Workflow
1. Deploy SIEM server on-prem or cloud.
2. Configure log ingestion from endpoints, firewalls, servers, and cloud.
3. Develop correlation rules for:
   - Brute-force attacks
   - Login failures
   - Malware behavior
   - Suspicious connections
4. Build dashboards for SOC monitoring.
5. Simulate attacks for testing detections (using tools like Atomic Red Team or manual log generation).

---

## 📊 Results
- Successful detection of simulated attacks.
- Centralized logging for all key systems.
- Real-time alerts configured for high-risk activities.

---

## 📂 Project Files
- `siem-architecture.png` – Network architecture diagram.
- `sample-log-data.json` – Example logs for testing.
- `correlation-rules.yaml` – Custom SIEM detection rules.
- `dashboards-screenshot.png` – Sample dashboard view.
- `SIEM-deployment-guide.md` – Step-by-step deployment guide.

---

## ✍️ Author
**Stephen Tanimowo**  
Cybersecurity Engineer | SIEM | Threat Detection | Cloud Security  
🔗 LinkedIn: https://www.linkedin.com/in/stephen-tanimowo-295b5a214/ | 📧 nifemiadebowale58@gmail.com
