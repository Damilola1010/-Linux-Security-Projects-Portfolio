# 🔐 Failed Login Detector

## 📌 Overview
This project detects multiple failed SSH login attempts on a Linux system to identify potential brute-force attacks.

## 🛠️ Tools Used
- Linux (Ubuntu)
- Bash scripting
- SSH logs (/var/log/auth.log)

## ⚙️ How It Works
- Scans system logs for failed login attempts
- Counts number of failures
- Alerts when suspicious activity is detected

## 🚀 How to Run
```bash
bash detector.sh
