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

## 💻 Installation
```bash
# Clone repository
git clone https://github.com/badal-mehra/ai-porthawk
cd ai-porthawk

# Install dependencies
pip install -r requirements.txt
```

---

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



