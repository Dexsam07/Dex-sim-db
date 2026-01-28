# DEX SIM DATABASE TOOL 📱

A lightweight Termux-based tool to search for SIM registration details using the DEX SIM Database API. Built for speed and ease of use.

---

## ✨ Features
* **🚀 Redirect to WhatsApp:** Join the official channel for the latest updates with one click.
* **🔍 SIM Search:** Search registration details (Name, CNIC, Address) by phone number.
* **🌍 Multi-Format Support:** Works with Pakistani numbers (`03xxxxxxxxx`) and International formats.
* **🎨 Clean UI:** Simple and colorful terminal-based interface.
* **🇮🇳 India Search:** Integrated API for searching Indian mobile number details.

---

## 📥 Installation

Copy and paste these commands in your Termux one by one:

### 1. Update & Upgrade Packages
```bash
pkg update && pkg upgrade -y && pkg install python git -y && git clone https://github.com/Dexsam07/Dex-sim-db && cd pari-sim-db && pip install requests && python pari.py
