# 🛡️ Adult Content Monitoring and Blocking System with Phishing Detection
## ❤️ Mission

Many people struggle to avoid explicit content online.  
**SecureBrowse** helps users regain control — not by spying or judging — but by simply removing temptation before it appears.

This project is built with the goal of *digital purity* and *mental focus* for everyone.

> “If you can’t control what you see, you can’t control what you think.”

> **“Protect your focus. Protect your faith.”**  
> SecureBrowse is a smart, rule-based desktop filter that automatically detects and blocks adult or NSFW websites at the browser level — before they can even load.

---

## 🔍 Overview
Software combines an intelligent background service with a lightweight **browser extension**.  

If adult content is detected, the page is immediately blocked and replaced with a motivational reminder.

---

A **hybrid security system** designed to handle **offline and online adult content threats** along with **online phishing detection**, providing real-time blocking, remote allow/block control, and automated deployment through a Windows installer.

---


This project presents a **unified offline–online security framework** that protects users from:

- **Offline adult content** accessed via locally stored videos
- **Online adult content** during active internet usage
- **Online phishing attacks** originating from malicious websites and links

Unlike traditional solutions that rely only on internet connectivity or browser extensions, this system operates at both **offline system level and online network level**, ensuring continuous protection.

---

## 🎯 Problem Statement

Most existing security systems fail in one or more of the following scenarios:

- They cannot detect adult content when the system is **offline**
- They focus only on browser-based protection and ignore **locally played media**
- They lack centralized control for **online allow/block decisions**
- They require manual configuration and technical setup

---

## 💡 Proposed Solution

The proposed system adopts a **hybrid offline–online approach**:

- **Offline Mode**
  - AI-based video frame analysis detects explicit adult content from locally played videos
  - Real-time blocking is enforced at the operating system level

- **Online Mode**
  - Online adult content and phishing threats are identified during internet usage
  - Remote allow/block decisions are managed through cloud APIs

Both modes are tightly integrated to provide **continuous and consistent security coverage**.

---

## 🏗️ System Architecture
[ Offline Media Playback ] [ Online Browsing Activity ]
↓ ↓
[ Offline AI Content Detection ] [ Online Threat & Phishing Detection ]
↓ ↓
[ Unified Decision Engine ]
↓
[ Allow / Block Required ]
↓
[ Cloud APIs (Vercel) + Firebase ]
↓
[ Email / SMS Approval Links ]
↓
[ Real-Time Enforcement on Device ]



---

## ✨ Core Features

- Offline adult content detection using AI-based video analysis
- Online adult content monitoring and phishing-aware detection
- Real-time blocking and enforcement mechanisms
- Cloud-synchronized allow/block decision control
- Email and SMS-based approval workflow
- Single-click Windows installer with background execution

---

## 🧩 Functional Modules

### 🔹 Offline Adult Content Detection
- Frame sampling from locally played videos
- Deep learning–based explicit content classification
- OS-level interception and blocking

### 🔹 Online Adult Content & Phishing Detection
- Detection of unsafe online content during browsing
- Phishing-aware analysis of web resources
- Cloud-assisted threat handling

### 🔹 Remote Allow / Block Control
- Secure approval links sent via email
- Firebase-based decision synchronization
- Immediate enforcement across offline and online contexts

### 🔹 Installer & Deployment
- Packaged as a standalone executable
- Automatic startup configuration
- Zero user intervention post-installation

---

## 🛠️ Tech Stack

### 🧠 AI & Computer Vision
- Python
- OpenCV
- NudeNet (Deep Learning Model)
- Frame Sampling Techniques

### ☁️ Cloud & Backend
- Firebase Firestore
- Serverless APIs (Vercel)
- RESTful APIs

### 🔐 Communication
- SMTP / Email Services
- Twilio SMS API

### 🖥️ System & Deployment
- Windows Internals
- psutil
- PyInstaller
- Inno Setup (Installer Script)

---

## 📦 Installation & Usage

1. Download and run the Windows installer
2. Application installs and configures itself automatically
3. Offline and online monitoring starts in the background
4. Allow/block decisions can be made remotely when required

---

## 🔐 Security & Privacy

- Offline video data never leaves the local machine
- Only decision metadata is stored in the cloud
- Hybrid design ensures privacy-preserving protection
- Secure APIs prevent unauthorized decision access

---

---

## 🔮 Future Enhancements

- Enhanced online phishing classification models
- Cross-platform support (Linux / macOS)

---

## 👤 Author

**Mohd Afzal Ali**

---

## ⚠️ Disclaimer

This system is developed strictly for **educational and research purposes**.  
It is intended to demonstrate hybrid offline–online security concepts and should not be misused.


## ⚙️ Features

✅ **100% Local Processing** — Runs entirely on your device. No cloud dependency.    
✅ **Auto-Start Background Service** — Starts automatically when Windows boots.  
✅ **Browser Integration** — Real-time blocking via Chrome/Edge extension.  
✅ **Privacy Friendly** — No data logging, no tracking, no remote servers.  
✅ **Lightweight** -runs under 40MB memory.

---

2. **Run the installer**  
   - It will automatically install, set up auto-start, and launch the protection service.


---

## 🤝 Contributing
Feel free to submit ideas, suggestions, or pull requests to make SecureBrowse better and more powerful.

---

## 🧑‍💻 Author
**Mohd Afzal Ali**  
*Developer · MTech in Software Engineering AMU*  


⭐ **Star this repo** if you support clean and focused internet habits!
