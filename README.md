# 🚨 SOC L1 Detection Notes – SIEM Queries & Detection Logic

This repository contains **SOC Level-1 detection notes and queries** created while actively practicing **SIEM-based threat detection** in a hands-on SOC lab.

The focus here is **how detections are built, tuned, and validated**, not just writing queries.

These notes reflect the **thinking process of an L1 SOC analyst** working with real logs and alerts.

---

## 👤 About This Repository

This repo documents:

- Detection logic used in **Microsoft Sentinel (KQL)** and **Splunk (SPL)**
- Why a detection exists (use case driven)
- What log sources are required
- How alerts are validated (TP vs FP)
- What an L1 analyst should check during triage

It complements my **Incident Reports repository**, where these detections are investigated end-to-end.

---

## 🎯 What You’ll Find Here

- SOC L1–focused detection use cases
- Detection notes mapped to real attack behaviors
- Query logic with explanations
- False positive considerations
- Analyst triage checklist ideas
- MITRE ATT&CK alignment (where applicable)

---

## 🧪 Detection Areas Covered

### 🔹 Endpoint Detection
- Suspicious PowerShell execution
- Credential access patterns
- Abnormal process spawning
- Authentication failures and brute-force behavior

### 🔹 Network Detection
- IDS alerts (Suricata)
- Suspicious inbound/outbound connections
- Reconnaissance indicators
- Malicious IP validation

### 🔹 Web & Server Detection
- Web shell upload attempts
- Command execution patterns
- Web server abuse
- Log-based anomaly detection

---

## 🛠️ Platforms & Tools Used

- **Microsoft Sentinel** (KQL detections)
- **Splunk Enterprise** (SPL searches)
- **Windows Event Logs**
- **Linux audit logs**
- **Web server logs (Apache)**
- **Suricata IDS**
- **Wazuh (HIDS / EDR)**

---

## 🧠 How to Use This Repo

Each detection note typically answers:

1. What behavior are we detecting?
2. Which logs are required?
3. Why this is suspicious
4. Example query (KQL / SPL)
5. How an L1 analyst should triage the alert
6. Common false positives
7. Next investigation steps

---

## 🎓 Learning Objective

This repository exists to:

- Strengthen **SOC L1 detection mindset**
- Practice **query-driven threat detection**
- Improve **alert triage confidence**
- Build a **real-world blue team portfolio**
- Prepare for **enterprise SOC environments**

This repo will grow as new detections are built and refined.

---

## 🔗 Related Repositories

- **SOC L1 Incident Reports