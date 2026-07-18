# 📡 VisionX – Intelligent Wi-Fi Monitoring & Network Security Analyzer

> An AI-powered dashboard that monitors Wi-Fi performance, analyzes network health, detects security risks, and provides intelligent troubleshooting recommendations in real time.

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black?style=for-the-badge&logo=flask)
![Networking](https://img.shields.io/badge/Networking-WiFi-green?style=for-the-badge)
![AI](https://img.shields.io/badge/AI-Rule%20Based-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In%20Development-red?style=for-the-badge)

---

# 📖 Overview

**VisionX** is an intelligent web dashboard designed to monitor Wi-Fi performance, analyze network health, and detect potential security threats in real time.

Instead of displaying only technical metrics, the dashboard collects and analyzes network parameters such as signal strength, latency, packet loss, DNS response, connected devices, and security configurations to identify the root cause of connectivity and security issues.

Powered by a **Rule-Based AI Expert System**, **VisionX** transforms complex networking data into simple, human-readable insights and actionable recommendations, making network troubleshooting accessible to everyone.

---

# 🎯 Problem Statement

Many users experience slow, unstable, or insecure Wi-Fi connections but struggle to identify the actual cause.

Most existing networking tools only display raw technical statistics, requiring networking knowledge to understand and troubleshoot issues.

**VisionX** bridges this gap by intelligently analyzing network performance and security, providing real-time diagnostics and practical recommendations through an interactive dashboard.

---

# ✨ Features

- 📶 Live Wi-Fi Network Monitoring
- 📊 Real-Time Network Health Dashboard
- 🤖 AI-Based Network Diagnosis
- 📡 Signal Strength Analysis
- ⚡ Latency, Jitter & Packet Loss Monitoring
- 🌐 DNS & Gateway Status Monitoring
- 📱 Connected Device Discovery
- 🔒 Network Security Analysis
- 📈 Historical Performance Analytics
- 📄 PDF Report Generation
- 💡 Intelligent Troubleshooting Recommendations

---

# 🧠 AI Diagnosis Engine

The core of **VisionX** is a **Rule-Based AI Expert System**.

Instead of using machine learning, predefined networking rules are applied to diagnose common Wi-Fi and network issues.

### Example Rules

| Condition | Diagnosis |
|-----------|-----------|
| Signal Strength < -80 dBm | Weak Wi-Fi Coverage |
| Packet Loss > 8% | Network Congestion |
| High Ping + Low Signal | Poor Router Placement |
| Strong Signal + Low Speed | Possible ISP Issue |
| Too Many Connected Devices | Router Overload |
| Open Wi-Fi or Weak Encryption | Security Risk |

The dashboard converts complex networking statistics into clear explanations and practical recommendations.

---

# 📊 Dashboard Modules

## 🛜 Network Information

- SSID
- IP Address
- Gateway
- DNS Server
- Wi-Fi Channel
- Frequency Band
- Security Type

---

## 📈 Live Performance

- Download Speed
- Upload Speed
- Latency
- Jitter
- Packet Loss
- Signal Strength

---

## ❤️ Network Health Score

Generates an overall health score based on:

- Signal Strength
- Internet Speed
- Latency
- Packet Loss
- Security Level
- Connected Devices

---

## 🤖 AI Diagnosis

Automatically detects:

- Weak Signal
- DNS Failure
- High Latency
- Packet Loss
- Router Overload
- ISP Performance Issues
- Channel Congestion
- Security Vulnerabilities

---

## 📱 Connected Devices

Displays:

- Device Name
- IP Address
- MAC Address
- Vendor
- Connection Status

---

## 🔒 Security Analyzer

Analyzes:

- Wi-Fi Encryption (WPA2/WPA3)
- Open Networks
- Unknown Connected Devices
- Network Security Score
- Basic Security Recommendations

---

## 📊 Historical Analytics

Visualizes:

- Signal Strength Trends
- Ping Trends
- Packet Loss History
- Network Health Timeline

---

# 🛠️ Tech Stack

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

# 📂 Project Structure

```text
VisionX/
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
├── security_analyzer.py
├── report_generator.py
├── requirements.txt
└── README.md
```

---

# 🚀 Future Enhancements

- 📶 Wi-Fi Dead Zone Heat Map
- 📡 Automatic Channel Recommendation
- 🏠 Smart Router Placement Suggestions
- 🔔 Real-Time Network Alerts
- 🤖 AI Chat Assistant
- 📊 Advanced Network Analytics
- 🌐 Multi-Network Monitoring
- ☁️ Cloud Dashboard Support

---

# 🎓 Academic Relevance

This project demonstrates practical implementation of:

- Computer Networks
- Wi-Fi Monitoring
- Network Security
- Network Troubleshooting
- Rule-Based Artificial Intelligence
- Data Visualization
- Dashboard Development
- Web Technologies

---

# 📸 Dashboard Preview

> Dashboard screenshots will be added after development.

```text
Network Health : 94%

Wi-Fi : Home_Network

Signal Strength : Excellent

Latency : 18 ms

Packet Loss : 0%

Security Score : 92%

Connected Devices : 7

AI Diagnosis

✔ Healthy & Secure Network

Recommendations

• No major issues detected.
• WPA3 encryption enabled.
• Network operating normally.
```

---

# 🎯 Project Goals

- Simplify Wi-Fi monitoring
- Improve network security awareness
- Provide intelligent diagnostics
- Visualize network performance
- Detect security vulnerabilities
- Deliver actionable recommendations
- Make networking understandable for everyone

---

# 🤝 Contributions

Contributions, feature requests, and suggestions are welcome.

If you have ideas to improve **VisionX**, feel free to fork the repository and submit a pull request.

---

# 📄 License

This project is licensed under the **MIT License**.

---

# ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub.

**Built with ❤️ to make Wi-Fi monitoring, network diagnostics, and security analysis smarter with AI.**
