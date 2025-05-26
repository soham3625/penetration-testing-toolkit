# 🛠️ Penetration Testing Toolkit

A simple modular **Python-based penetration testing toolkit** that includes:

- 🔍 Port Scanner – Scan a target for open TCP ports.
- 🔐 Brute-Force Tool – Try a password list against a login form.

> ⚠️ **For educational and authorized security testing only.**

---

## 📦 Features

| Module           | Description                                       |
|------------------|---------------------------------------------------|
| Port Scanner     | Scan common ports (1–1024) on a target IP/domain. |
| Brute Forcer     | Try login credentials using a password list.      |

---

## 🚀 Getting Started

### 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/penetration-testing-toolkit.git
cd penetration-testing-toolkit

2. Install requirements
pip install requests

4. Run the tool
python pentest_toolkit.py

🖥️ Usage
When you run the script, you'll see this menu:
1. Port Scanner
2. Brute Force Login
🔍 Port Scanner
Input: Target IP or domain

Output: List of open ports between 1–1024

🔐 Brute Forcer
Input: Login URL, username, field names, and password list

Output: First successful login (if any)

📁 Files
File	Description
pentest_toolkit.py	Main script combining all functionality
requirements.txt	Required Python packages (requests)
README.md	You're reading it!

⚠️ Legal Notice
This tool is intended for educational purposes only.
Do not use it on any system or network without explicit authorization.
