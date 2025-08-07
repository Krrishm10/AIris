# 🧠 AIris – AI-Based Safe Search Monitoring System

**AIris** (Artificial Intelligence + Iris) is a system-level, AI-powered safe search and monitoring system for **Windows**. It silently runs in the background from system startup, using a **custom local VPN** to monitor and block unsafe, harmful, or fraudulent links — whether they come from browsers, WhatsApp, PDFs, or other applications.

---

## 🔒 Features

- ✅ **System-level monitoring**
- 🧠 **AI-powered URL & query classification**
- 🔗 **Blocks harmful links from all sources** (browser, chats, documents, etc.)
- 🔁 **Auto-start on system boot**
- 🔐 **Tamper-proof protection**
- 🚀 **Ultra low-latency with local AI inference**
- 🧱 **Uses Wintun for VPN tunneling**
- 🌐 **Offline-capable with no external dependencies**

---

## 🛠️ Tech Stack

- **Python**
- **Wintun.dll** (via `pywin32`)
- **Local VPN tunnel**
- **Lightweight AI Model** (for URL and text classification)

---

## 🚀 How It Works

1. AIris sets up a **local VPN tunnel** using `wintun.dll` to intercept all outgoing traffic.
2. Every **URL or search query** is passed through a **custom AI model** for classification.
3. If unsafe content is detected, the request is blocked.
4. AIris starts automatically on system boot and is **non-bypassable** by standard means.

---

## 📁 Installation

Coming soon — one-click installer with:

- Automatic Wintun setup
- DLL handling based on system architecture (x86, x64, ARM)
- Background service installation

---

## 🧪 Status

🟡 **In Development**  
The project is under active development. Expect regular updates and improvements.

---

## 📄 License

MIT License

---

## 🙋‍♂️ Author

**Knight Riders**

> *Feel free to fork, contribute, or reach out if you're interested in collaborating!*

