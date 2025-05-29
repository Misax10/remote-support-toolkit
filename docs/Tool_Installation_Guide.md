# 🧰 Tool Installation Guide

This guide provides step-by-step instructions for setting up and using the core tools included in the Remote Support Toolkit. These tools allow IT support specialists to securely access, troubleshoot, and resolve user issues remotely.

---

## 🔹 1. AnyDesk Setup (Windows/macOS)

**Website**: [https://anydesk.com/en/downloads](https://anydesk.com/en/downloads)

### Installation Steps:
1. Download the installer from the official website.
2. Open the `.exe` (Windows) or `.dmg` (macOS) file.
3. Run the installer and launch AnyDesk.

### How to Use:
- The user will see a **9-digit address** (e.g., `123 456 789`) on the main screen.
- Ask the user to share this code with you.
- Enter the code into your AnyDesk app and click **Connect**.
- The user will be prompted to **Accept** the connection.
- Once accepted, request **control permissions** (keyboard/mouse access if needed).

### After the Session:
- Advise the user to close AnyDesk.
- For one-time support, they may uninstall the app after the session.

---

## 🔹 2. Chrome Remote Desktop Setup

**Website**: [https://remotedesktop.google.com](https://remotedesktop.google.com)  
**Requirements**: Google Chrome browser and a Google account

### Setup Steps:
1. Visit the [Chrome Remote Desktop support page](https://remotedesktop.google.com/support).
2. Under **Remote Support**, click **Download** to install the Chrome extension.
3. Click **Generate Code** to create a one-time 12-digit access code.
4. Share the access code with the IT support agent (you).
5. The agent enters the code on their end and connects to the session.

### After the Session:
- The session automatically expires after a few minutes of inactivity.
- No persistent software is installed unless set up under “Remote Access.”

---

## 🔹 3. Microsoft Remote Desktop (Windows Pro)

**Note**: This is only available on Windows **Professional**, **Enterprise**, or **Education** editions.

### How to Enable:
1. Go to `Settings → System → Remote Desktop`.
2. Toggle **Enable Remote Desktop** to ON.
3. Note the **PC name** and **IP address** for connection.

### How to Connect:
- Use the built-in Remote Desktop client (`mstsc`) on the support machine.
- Enter the IP address or PC name of the target machine.
- Provide user credentials to connect (must have permissions set).

### Security Best Practices:
- Use a VPN or private network when using RDP.
- Limit access to specific users in `Remote Desktop Users`.

---

## 🔹 4. File Sharing Tools

### 📁 Google Drive
**Steps**:
1. Go to [https://drive.google.com](https://drive.google.com).
2. Upload the file you want to share.
3. Right-click the file → click **Get Link**.
4. Set link access to:
   - **Viewer** – if the user only needs to see/download
   - **Editor** – if you need the user to make changes
5. Share the link with the user securely (email or chat).

### 📁 OneDrive (Microsoft)
**Steps**:
1. Visit [https://onedrive.live.com](https://onedrive.live.com).
2. Upload the file or request a file via **File Request** (business users).
3. Share the file link with proper permissions.

---

## 🔒 5. Security and Cleanup Guidelines

- Always obtain **explicit consent** before accessing a user’s device.
- After the session:
  - Recommend removing AnyDesk or Chrome Remote Desktop if not regularly used.
  - Ensure file links (Google Drive/OneDrive) are set to expire or are deleted.
- **Do not store passwords or personal data**.
- Close all sessions and logout of any shared accounts immediately.

---

## ✅ Recommended Tools Summary

| Tool                     | Purpose                         | Platform        | Notes                                |
|--------------------------|----------------------------------|------------------|---------------------------------------|
| AnyDesk                  | Remote desktop control           | Windows/macOS    | Lightweight, quick setup             |
| Chrome Remote Desktop    | Browser-based remote access      | Cross-platform   | Easy one-time sessions               |
| Microsoft RDP            | Internal remote access           | Windows Pro+     | Best for LAN/VPN environments        |
| Google Drive / OneDrive  | File sharing                     | Cross-platform   | Secure sharing with permission control |

---

📬 **For issues during setup**, refer to the vendor support pages or contact your internal IT documentation resources.

