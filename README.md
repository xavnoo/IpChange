<div align="center">

# 🔄 NOBITA IP CHANGER

### ⚡ Termux IP Rotator | Tor Based | Auto Proxy

[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@owov_bot)
[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/nobi4t111)
[![Termux](https://img.shields.io/badge/Termux-000000?style=for-the-badge&logo=termux&logoColor=white)](https://termux.com)

</div>

---

## 🎯 **What is this?**

A powerful **Tor-based IP changer** for Termux that automatically rotates your public IP address at custom intervals using **5 parallel Tor circuits**.

> **Created by:** [@nobi4t111](https://t.me/nobi4t111)

---

## ✨ **Features**

| Feature | Description |
|---------|-------------|
| 🔄 **Auto Rotation** | Changes IP at your specified time |
| 🧅 **5 Tor Instances** | Multiple circuits (Ports 9050-9090) |
| 🛡️ **Privoxy Proxy** | HTTP proxy on `127.0.0.1:8118` |
| 🌐 **Live IP Display** | Shows new IP after each rotation |
| ⚡ **Lightweight** | Minimal resource usage |
| 🎮 **Easy to Use** | One command setup |

---

## 📦 **Requirements**

- ✅ Android with **Termux** installed
- ✅ Internet Connection (WiFi/Mobile Data)
- ✅ ~50MB Free Storage

---

## 🚀 **Installation**

Open Termux and paste these commands:

```bash
# Step 1: Install git
pkg install git -y

# Step 2: Clone repository
git clone https://github.com/YOUR_USERNAME/termux-ip-changer.git

# Step 3: Go to folder
cd termux-ip-changer

# Step 4: Make executable
chmod +x IpChange.sh

# Step 5: Run script
bash IpChange.sh
