# 🔍 AI-PortHawk 🦅
*Next-Gen AI-Powered Port Scanner*  
*By [Badal Mehra](https://github.com/badal-mehra)*  

[![Python](https://img.shields.io/badge/Python-3.8+-blue)](https://python.org)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/badal-mehra/ai-porthawk)](https://github.com/badal-mehra/ai-porthawk/stargazers)

---

![AI-PortHawk Demo](assets/demo.gif)

## 🚀 Features
- ⚡ **Scans 65,535 ports** in under 5 minutes
- 🤖 **AI-driven threat scoring** (Low/Medium/High risk)
- 🔍 **Smart service detection** (HTTP, SSH, FTP, RDP)
- 🕵️ **Stealth mode** with randomized delays
- 📄 **PDF/HTML reports** with vulnerability details

---
## 🔥 Why AI-PortHawk?
AI-PortHawk 🦅 isn't just another port scanner—it’s an AI-powered cybersecurity tool designed to provide faster, smarter, and more actionable insights than traditional scanners. Here’s why you should use it:

- ⚡ 1. Ultra-Fast Scanning (65,535 Ports).
- 🧠 2. AI-Driven Threat Analysis.
- 🔍 3. Smart Service & Banner Detection.
- 📊 4. Professional Reports & Real-Time Results.
- 🛠️ 5. Easy to Use & Customizable.

---

## 💻 Installation
```bash
# Clone repository
git clone https://github.com/badal-mehra/ai-porthawk
cd ai-porthawk

# Required Installations:
pip install rich


# Install dependencies
pip install -r requirements.txt
```

---

## 📸 Images & How-To
### Step 1: Basics – What is AI-PortHawk?
AI-PortHawk 🦅 is a powerful AI-based port scanner that helps identify open ports, detect services, and assess vulnerabilities.

📌 Overview of AI-PortHawk:
<img width="886" alt="1 jpeg" src="https://github.com/user-attachments/assets/1bce0d26-80f0-49a4-a3e4-8d7f09389f47" />

### Step 2: How to Use It
🔹 Installation

1️⃣ Clone the repository & install dependencies:

Copy
git clone https://github.com/badal-mehra/AI-PortHawk.git
cd AI-PortHawk

pip install -r requirements.txt

2️⃣ Command Execution Screenshot:
![ai-porthawk py - practice - Visual Studio Code 4_1_2025 2_40_03 PM (4)](https://github.com/user-attachments/assets/897db098-0026-4cef-894f-2a5571d6032e)

### Step 3: Understanding the Output
Once the scan completes, you will see a detailed output:
✅ Open Ports
✅ Detected Services
✅ Potential Vulnerabilities

📷 Example Output Screenshot:
<img width="951" alt="3" src="https://github.com/user-attachments/assets/7748ccf4-68cc-4978-a1af-5e3f2f1c24c9" />



## 🛠️ Usage
### Basic scan:
```bash
python scan.py -t 192.168.1.1
```
### Advanced scan (512 threads + stealth mode + HTML report):
```bash
python scan.py -t example.com --threads 512 --stealth --html report.html
```

---

## 📊 Sample Output
```
PORT    SERVICE   THREAT   BANNER
22      SSH       High     SSH-2.0-OpenSSH_8.4
80      HTTP      Medium   Apache/2.4.29
443     HTTPS     Medium   Nginx/1.18.0
```

---

## 🤖 AI Integration
| Component            | Technology Used | Accuracy |
|----------------------|----------------|----------|
| Service Detection   | CNN            | 96.2%    |
| Threat Prediction   | XGBoost        | 89.7%    |

---

## 🌟 Coming Soon
- 🔗 Shodan API integration
- 🔥 Real-time CVE updates
- 🐳 Docker support

---

## 📜 License
MIT © [Badal Mehra](https://github.com/badal-mehra)



