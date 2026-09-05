# VisionX — AI-Powered Wi-Fi Monitoring & Network Security Analyzer

VisionX is an AI-powered, Windows-based desktop application designed to simplify Wi-Fi monitoring and network security for everyday users. By transforming raw, complex router data (IP tables, protocols, and logs) into plain-language insights, VisionX removes technical barriers and helps non-technical users protect their home and small-office networks in real time.

---

## 🚀 Key Features

* **Smart Router & Easy Admin Access:** Auto-detects gateway IPs, retrieves standard admin credentials, and provides direct, one-click access to the router admin page.
* **Zero-Device Visibility:** Displays a real-time inventory of all devices connected to the local network.
* **AI Behavioral Anomaly Detection:** Leverages an Isolation Forest model to learn network baselines and flag traffic spikes, unknown devices, or unexpected behavior.
* **Interactive Traffic Heat Maps:** Visualizes live network flow, protocol distribution, and bandwidth consumption in an intuitive dashboard.
* **Explainable AI (XAI) & Reports:** Translates security findings and threat scores (Low, Medium, High) into plain language and generates structured Wi-Fi health reports on demand.
* **Embedded AI Assistant:** Automates recurring diagnostic and monitoring tasks to keep network security proactive.

---

## 🛠️ Architecture & Tech Stack

* **Domain:** AI-based Networking & Cybersecurity
* **Frontend:** Vercel Edge Network Deployment (React/Modern Web Stack, sub-millisecond static asset delivery, SSL/TLS, automated DDoS mitigation)
* **ML Model:** Isolation Forest (Scikit-Learn) for anomaly detection and baseline behavior modeling
* **Target OS:** Windows Desktop / Laptop

---

## 📂 Project Methodology

1. **Network Data Acquisition:** Extracts gateway IP, connected device parameters, and live traffic metrics upon application launch.
2. **Feature Extraction:** Structures raw network packets into metrics such as packet rates, volume, and protocol distribution.
3. **AI Anomaly & Vulnerability Assessment:** Passes features to the Isolation Forest model while scanning configurations for weak parameters.
4. **Classification & Alerting:** Categorizes risks into Low, Medium, or High tiers and triggers real-time alerts.
5. **Visualization & Direct Admin Routing:** Renders interactive heat maps and provides direct router panel redirection.

---

## 🔬 VisionX vs. Academic Frameworks (e.g., SecIDS-CNN-WF)

| Feature / Dimension | SecIDS-CNN-WF (IEEE Base) | VisionX (This Project) |
| :--- | :--- | :--- |
| **Primary Target** | Researchers & Edge-IDS Operators | Everyday Users, Home/Office Networks |
| **Input Focus** | Raw IEEE 802.11 frames | Local network, device, and traffic metrics |
| **Primary Goal** | Deep Learning Intrusion Detection | Integrated Monitoring, Accessibility & Admin Direct Access |
| **Deployment Target**| Raspberry Pi / TFLite Edge Devices | Windows Desktop Application |

---

## 👥 Team & Acknowledgments

* **Institution:** Sri Shakthi Institute of Engineering and Technology (Autonomous), Coimbatore
* **Department:** Computer Science and Engineering (Cyber Security)
* **Course:** 25CYS311 - Engineering Exploration - III
* **Guide:** Sri Thejas N (Assistant Professor, CSE - Cyber Security)

### Project Contributors
* **Sreedev KS**
* **Santhosh SN**
* **Santhosh S**
* **Rithanyaa R**

---

## 📝 License & Repository

Maintained collaboratively via GitHub: [VisionX Repository](https://github.com/santhoshmaddy69-cell/VisonX)