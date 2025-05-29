# 🛠️ Remote Support Toolkit for IT Support Specialists

## Overview

This project provides a practical and secure toolkit for performing remote IT support. Designed for IT Support Specialists, it demonstrates how to assist users with technical issues remotely using tools like remote desktop software, file sharing platforms, communication apps, and system diagnostics.

> 📌 This toolkit simulates a real-world help desk scenario where support is delivered remotely while ensuring user privacy and data security.

---

## 🎯 Objectives

- Provide step-by-step guides for remote desktop access and support
- Use secure file transfer and communication tools
- Troubleshoot common technical issues remotely
- Document best practices for user support and data security

---

## 🧰 Tools Used

| Category            | Tool / Platform           | Description                                |
|---------------------|---------------------------|--------------------------------------------|
| Remote Access        | AnyDesk, Chrome Remote Desktop | For secure remote control of user devices |
| Communication        | Zoom, Microsoft Teams     | For real-time support and screen sharing   |
| File Transfer        | Google Drive, OneDrive    | To exchange drivers, logs, and updates     |
| Diagnostics          | Command Prompt, PowerShell| For network and system-level checks        |

---

## 📁 Toolkit Components

### 1. Remote Access Setup
- Installation and configuration of:
  - [AnyDesk](https://anydesk.com)
  - [Chrome Remote Desktop](https://remotedesktop.google.com)
  - Windows Remote Desktop (RDP)

### 2. Secure File Transfer
- Share files via:
  - Google Drive: With edit or view permissions
  - OneDrive: File request for user uploads

### 3. Communication Protocol
- Support session setup via Zoom/MS Teams:
  - Share screen
  - Guide users verbally or via chat
  - Record steps if needed for future reference

### 4. Troubleshooting Commands
- `ping` – test connectivity
- `ipconfig` / `ifconfig` – check IP configurations
- `netstat` – view active connections
- `sfc /scannow` – scan for system file corruption

---

## 🎥 Demo Scenario

**Issue**: User reports that their printer is not connecting.

**Steps**:
1. Initiate a Zoom call with the user.
2. User installs AnyDesk and shares code.
3. Remote into the system and check IP configuration using `ipconfig`.
4. Reinstall or update printer drivers.
5. Confirm printer is working by sending a test print.
6. End session and instruct user to uninstall remote access tool for security.

🖥️ *Demo video available in the [`demo/`](./demo/) folder.*

---

## 🔒 Security & Privacy Best Practices

- Always get explicit user permission before accessing their device
- End remote session and remove access tools after issue is resolved
- Use a VPN when connecting to internal systems
- Never store credentials or sensitive data on your local machine

---

## 📂 Project Structure
```
remote-support-toolkit/
├── README.md
├── checklist/
│   └── Remote_Support_Checklist.pdf
├── docs/
│   ├── Tool_Installation_Guide.md
│   └── Privacy_Security_Policy.md
├── demo/
│   └── remote_support_demo.mp4
└── screenshots/
    └── setup_example.png
```
---

## 🚀 How to Use

1. Download or clone the repository.
2. Follow the tool installation guides in `/docs/`.
3. Use the checklist to walk through your support session.
4. Share demo or walkthroughs with potential employers or clients.

---

## 📬 Contact

**Khoa Diep**  
Email: [khoadiep99@gmail.com](mailto:khoadiep99@gmail.com)  
LinkedIn: [linkedin.com/in/khoadiep](https://www.linkedin.com/in/khoadiep)

---

© 2025 Khoa Diep. All rights reserved.

