# DHT-BGMI-PHISH

![DHT-HACKERS](https://img.shields.io/badge/DHT-HACKERS-magenta?style=for-the-badge)

The ultimate **BGMI Phishing Tool** using a live PHP server, terminal UI, and **Cloudflare tunnel** for victim capture — built for **educational purposes only**.

---

# 🎯 DHT-BGMI-PHISH – Phish with Style!

Welcome to **DHT-BGMI-PHISH** — a lightweight yet powerful phishing tool designed to demonstrate how BGMI scam pages are deployed in the wild. This tool uses a **PHP server**, **Cloudflare tunnel**, and live victim **data monitoring** — all inside **Termux** or Linux.

---

# ⚠️ Disclaimer

> This tool is made strictly for **educational** and **ethical hacking** purposes.  
> Never use this tool without **explicit permission**.  
> The creators are not responsible for any misuse or illegal activity.

---

# 🚀 Installation Guide

Install in Termux or Linux:

```bash
apt update && apt upgrade -y
pkg install python php git -y
pip install pyfiglet rich
git clone https://github.com/DHThackers-10/DHT-BGMI-PHISH.git
cd DHT-BGMI-PHISH
chmod +x *
bash setup.sh
```

---

# 🖥️ Screenshots

> **Tool Startup Interface**

[DHT BGMI]![Screenshot_20250629-132033](https://github.com/user-attachments/assets/b058a56c-ed39-423b-8a1b-e1e433175050)

---

# ⚙️ Features

✅ **Real-Time Victim Monitoring**  
✅ **PHP Server for Landing Page**  
✅ **Cloudflare Tunnel (manual)**  
✅ **Terminal UI with Rich + Pyfiglet**  
✅ **BGMI-style phishing page**  
✅ **Live Logs of Email, Password, UC & IP**  
✅ **Logs saved in** `data.log`

---

# 📂 Victim Output Example

```bash
💀 Victim Captured!

📧 Email: johnbgmi@example.com
🔑 Password: bgmi123456
💎 UC Requested: 670
🌐 IP Address: 103.88.222.45
```

---

# 🔧 How It Works

1. User opens tool in Termux  
2. PHP server is launched locally  
3. Tool shows instruction to start Cloudflare tunnel  
4. Victim enters fake UC claim info  
5. Tool logs:
   - Email
   - Password
   - UC requested
   - IP address

---

# 🔐 File Structure

```bash
📁 DHT-BGMI-PHISH/
├── dht_bgmi_phish.py
├── data.log
└── (phishing HTML in local server)
```

---

# 🌐 Educational Use Only

**DHT-BGMI-PHISH** is built for **learning and awareness** about phishing and social engineering attacks. This is a **simulation** tool and should never be used on real targets without permission.

---

# 👨‍💻 Credits

**Author:** Ali Sabri – DHT Hackers  
**GitHub:** [DHThackers-10](https://github.com/DHThackers-10)  
**YouTube:** [DHT Hackers](https://youtube.com/@dht-hackers_10)  
**WhatsApp Community:** [Join Group](https://chat.whatsapp.com/G2hCkCzylra2OENEfhH8Os)

---

# 💡 More DHT Tools

Check out our other tools:

- `DHT-IGBRUTE` — Instagram BruteForcer  
- `DHT-PHISHER` — All-in-one Phishing Engine  
- `DHT-BRUTXGMAIL` — Gmail BruteForce  
- `DHT-CRASHER` — WhatsApp Crash Sender  
- `DHT-SOCIALKIT` — Multi-platform brute + phish toolkit

Explore more: [github.com/DHThackers-10](https://github.com/DHThackers-10)
