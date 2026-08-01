VisionX — Wi-Fi Monitoring & Network Security Analyzer
VisionX is a real-time dashboard that monitors Wi-Fi performance, evaluates network health, and flags basic security risks — then explains what's wrong in plain language instead of dumping raw metrics on the user.
I built it to solve a problem I kept running into: most Wi-Fi diagnostic tools show you numbers (signal strength, latency, packet loss) but don't tell you what to actually do about them. VisionX closes that gap with a rule-based diagnosis engine that translates network conditions into specific, actionable recommendations.
�
�
�
�
�
Load image
Load image
Load image
Load image
What it does
VisionX continuously monitors your network connection and surfaces three things:
Live performance metrics — signal strength, latency, jitter, packet loss, download/upload speed
A network health score — a single number that summarizes how well your network is actually performing
Plain-language diagnosis — instead of "packet loss: 9.2%", it tells you "Network Congestion — try reducing connected devices or switching channels"
It also does a basic pass on network security: checking encryption type (WPA2/WPA3 vs open), flagging unrecognized connected devices, and producing a security score with recommendations.
How the diagnosis engine works
There's no machine learning here yet, and I'd rather be upfront about that than oversell it. VisionX uses a rule-based expert system — a set of conditional rules built from real networking knowledge, not a trained model. It's simpler, but it's also transparent and predictable, which matters for something people are going to trust with troubleshooting decisions.
Some of the core rules:
Condition
Diagnosis
Signal strength < -80 dBm
Weak Wi-Fi coverage
Packet loss > 8%
Network congestion
High ping + weak signal
Poor router placement
Strong signal + low speed
Likely an ISP-side issue
Too many connected devices
Router overload
Weak encryption or open network
Security risk
I'm treating this as a foundation — moving to an actual ML-based anomaly detection model (trained on historical network behavior rather than fixed thresholds) is the next real milestone, not a "future enhancement" I'm just listing for show.
Dashboard breakdown
Network Information — SSID, IP address, gateway, DNS server, channel, frequency band, security type
Performance Monitoring — download/upload speed, signal strength, latency, jitter, packet loss, tracked live and over time
Health Score — a composite score built from signal quality, speed, latency, packet loss, security level, and device count
Security Analyzer — encryption check (WPA2/WPA3/open), unrecognized device detection, security score with specific recommendations
Analytics — historical trends for signal strength, ping, packet loss, and overall health, so you can see patterns rather than just a snapshot
Reports — exportable PDF summaries of network status
Tech stack
Layer
Tools
Frontend
HTML5, CSS3, Bootstrap, JavaScript, Chart.js
Backend
Python, Flask
Database
SQLite
Core libraries
psutil, ping3, speedtest-cli, matplotlib, reportlab
Project structure
Code
Getting started
Bash
Then open http://localhost:5000 in your browser.
Sample output
Code
(Dashboard screenshots coming soon — UI is still being polished.)
What's next
Wi-Fi heatmap visualization for coverage mapping
Automatic channel recommendation based on congestion
Real ML-based anomaly detection to replace/augment the rule engine
Real-time alerts and notifications
Multi-network monitoring
Mobile-responsive interface
What I learned building this
This project pushed me to actually understand — not just use — core networking concepts: signal quality, latency vs. jitter, DNS resolution, and how encryption type affects real security posture. It also forced me to think about a problem a lot of technical projects skip: how do you present complex data to someone who isn't technical, without dumbing it down to the point of being useless?
Contributing
Open to feedback, issues, and pull requests. If you spot a bug or have an idea for a better diagnostic rule, feel free to open an issue.
License
MIT License.
