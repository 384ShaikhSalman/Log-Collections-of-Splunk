# 🛡️ Exploring Security Operations Center (SOC): Log Collection in Cyber Defense

Welcome to this documentation repository focused on **Log Collection** — a fundamental capability within any **Security Operations Center (SOC)**. This guide reflects my learning journey and hands-on exploration in cybersecurity operations.

---

## 🚀 Why Log Collection Matters

Logs are the heartbeat of a SOC. They provide the **raw telemetry** needed for:

- 🔍 Threat Detection & Real-Time Monitoring  
- 🧪 Incident Investigation & Forensics  
- 📊 Compliance Auditing (PCI-DSS, HIPAA, ISO)  
- 🛡️ Infrastructure Visibility & Cyber Resilience  

---

## 🔍 Key Focus Areas

### 1️⃣ System Logs
Capture logs from:

- Linux/Unix servers (`/var/log/syslog`, `auth.log`)
- Network devices (routers, switches)
- Workstations and endpoints

### 2️⃣ Application Logs
Track:

- Web applications (access logs, error logs)
- Authentication systems (login attempts)
- Database queries and transactions
- API calls and responses

### 3️⃣ Security Devices
Collect alerts and detections from:

- Antivirus / EDR solutions
- Firewalls and UTM
- IDS/IPS systems (Snort, Suricata)

### 4️⃣ Log Normalization
Convert logs into a **standard format** to make them analyzable across platforms and tools like SIEM.

- Regex-based parsing
- Key-value pair normalization
- Timestamps standardization (ISO 8601)

### 5️⃣ Log Transport & Forwarding
Use agents and protocols to forward logs securely:

- **Splunk Universal Forwarder**
- **Syslog (rsyslog, syslog-ng)**
- **NXLog / Beats (Elastic Stack)**

### 6️⃣ Storage & Retention
Store logs efficiently and ensure they are available when needed:

- On-premise/local storage (short-term)
- Cloud-based storage (e.g., S3, Azure Blob)
- Retention policies for compliance (e.g., 1-year for PCI-DSS)

### 8️⃣ Real-Time Ingestion
Push logs immediately for:

- Alerting and correlation
- Live dashboards
- Threat hunting and behavioral analysis

---

## 🛠 Tools Used

| Tool/Technology        | Purpose                                |
|------------------------|----------------------------------------|
| 🟠 Splunk Enterprise    | Central log aggregation and analysis   |
| ⚙️ Syslog / Rsyslog      | Log forwarding from Unix-based systems |
| 🔵 NXLog                | Multi-platform log forwarding          |
| 📊 SIEM Platforms       | (Elastic Stack, QRadar, etc.)         |

Author :
Shaikh Salman 
384shaikhsalman@gmail.com

