# VisonX
# 🩺 NetMedic AI – Intelligent Network Diagnosis & Health Monitoring Dashboard

> An AI-powered network monitoring dashboard that analyzes Wi-Fi performance, diagnoses network issues, and provides intelligent troubleshooting recommendations in real time.

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black?style=for-the-badge&logo=flask)
![Networking](https://img.shields.io/badge/Networking-WiFi-green?style=for-the-badge)
![AI](https://img.shields.io/badge/AI-Rule%20Based-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In%20Development-red?style=for-the-badge)

---

## 📖 Overview

**NetMedic AI** is an intelligent web dashboard designed to monitor Wi-Fi network performance and automatically diagnose common networking issues.

Instead of displaying only technical metrics, the dashboard analyzes network parameters such as signal strength, latency, packet loss, DNS response, and connected devices to identify the root cause of connectivity problems.

Using a rule-based AI expert system, NetMedic AI provides simple, human-readable recommendations that help users troubleshoot their network without requiring advanced networking knowledge.

---

## 🎯 Problem Statement

Many users experience slow or unstable internet connections but cannot determine the actual cause.

Existing tools display raw networking statistics, requiring technical expertise to interpret.

**NetMedic AI** bridges this gap by automatically analyzing network health and providing intelligent diagnostics along with practical solutions.

---

## ✨ Features

- 📶 Live Wi-Fi Network Monitoring
- 📊 Real-Time Network Health Dashboard
- 🤖 AI-Based Network Diagnosis
- 📡 Signal Strength Analysis
- ⚡ Latency, Jitter & Packet Loss Monitoring
- 🌐 DNS & Gateway Status Check
- 📱 Connected Device Monitoring
- 📈 Historical Performance Analytics
- 🔒 Network Security Overview
- 📄 PDF Report Generation
- 💡 Intelligent Troubleshooting Recommendations

---

## 🧠 AI Diagnosis Engine

The core of NetMedic AI is a **Rule-Based Expert System**.

Instead of using machine learning, predefined networking rules are applied to diagnose common network problems.

### Example Rules

| Condition | Diagnosis |
|-----------|-----------|
| Signal Strength < -80 dBm | Weak Wi-Fi Coverage |
| Packet Loss > 8% | Network Congestion |
| High Ping + Low Signal | Poor Router Placement |
| Strong Signal + Low Speed | ISP Performance Issue |
| Many Connected Devices | Router Overload |

The dashboard converts complex networking statistics into simple explanations and actionable recommendations.

---

## 📊 Dashboard Modules

### 🛜 Network Information
- SSID
- IP Address
- Gateway
- DNS Server
- Wi-Fi Channel
- Frequency Band
- Security Type

### 📈 Live Performance
- Download Speed
- Upload Speed
- Latency
- Jitter
- Packet Loss
- Signal Strength

### ❤️ Network Health Score
Generates an overall network health score based on:

- Signal Strength
- Internet Speed
- Latency
- Packet Loss
- Security
- Connected Devices

### 🤖 AI Diagnosis
Automatically identifies issues such as:

- Weak Signal
- DNS Failure
- High Latency
- Packet Loss
- Router Overload
- ISP Issues
- Channel Congestion

### 📱 Connected Devices
Displays:

- Device Name
- IP Address
- MAC Address
- Status

### 📊 Historical Analytics
Visualizes:

- Signal Strength Trends
- Ping Trends
- Packet Loss History
- Health Score Timeline

---

## 🛠️ Tech Stack

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap
- Chart.js

### Backend
- Python
- Flask

### Libraries
- psutil
- speedtest-cli
- socket
- ping3
- matplotlib
- reportlab

### Database
- SQLite

---

## 📂 Project Structure

```
NetMedic-AI/
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   └── index.html
│
├── reports/
│
├── database/
│
├── app.py
├── ai_engine.py
├── network_monitor.py
├── report_generator.py
├── requirements.txt
└── README.md
```

---

## 🚀 Future Enhancements

- Wi-Fi Dead Zone Heat Map
- Live Router Placement Suggestions
- Automatic Wi-Fi Channel Recommendation
- Real-Time Network Alerts
- AI Chat Assistant
- Multi-Router Monitoring
- Mobile Responsive Dashboard

---

## 🎓 Academic Relevance

This project demonstrates practical implementation of:

- Computer Networks
- Network Monitoring
- Network Troubleshooting
- Rule-Based Artificial Intelligence
- Data Visualization
- Dashboard Design
- Web Development

---

## 📸 Dashboard Preview

> Dashboard screenshots will be added after development.

```
Network Health : 92%

Wi-Fi : Home_Network

Signal Strength : Excellent

Latency : 18 ms

Packet Loss : 0%

Connected Devices : 7

AI Diagnosis

✔ Network Healthy

Recommendations

• No major issues detected.
```

---

## 🎯 Project Goals

- Simplify network troubleshooting
- Provide intelligent diagnostics
- Improve Wi-Fi monitoring
- Visualize network performance
- Deliver actionable recommendations
- Make networking understandable for everyone

---

## 🤝 Contributions

Contributions, feature requests, and suggestions are welcome.

If you have ideas to improve **NetMedic AI**, feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.

**Built with ❤️ to make network troubleshooting smarter and simpler.**
