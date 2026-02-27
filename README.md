# 🛡 Windows SOC Monitoring Dashboard (Splunk Project)

## 📌 Project Overview
This project demonstrates a Windows Security Monitoring Dashboard built using Splunk Enterprise.

The dashboard detects:
- Failed login attempts (Event ID 4625)
- Brute force attacks by IP
- Targeted user login attacks
- PowerShell process execution (Event ID 4688)

---

## 📊 Dashboard Panels

1. Total Failed Login Attempts
2. Failed Login Trend
3. Suspicious Source IP Detection
4. Targeted User Attack Detection
5. PowerShell Activity Monitoring

---

## 🚨 Alert Configuration
Configured alert:
- Trigger when failed login attempts > 10
- Runs once per hour

---

## 🛠 Tools Used
- Splunk Enterprise
- Windows Security Logs
- SPL (Search Processing Language)

---

## 🎯 Skills Demonstrated
- Log ingestion
- Index creation
- SPL query writing
- Dashboard creation
- Alert configuration
- Brute force detection

---

## 📂 Sample Log File
Included sample Windows Security log file for practice.

---

## 👩‍💻 Author
Jasmeen
