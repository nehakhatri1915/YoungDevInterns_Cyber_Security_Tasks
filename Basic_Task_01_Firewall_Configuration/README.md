# 🔐 Task 1 – Basic Firewall Configuration

### 📌 Category: Basic Tasks  
### 🏢 Internship Program: YoungDevInterns – Cyber Security Internship

---

## 🧾 Task Overview

> **Objective:** Enable and configure Windows Defender Firewall (or a similar firewall), and create custom rules to block or allow specific applications or ports on a personal computer.

Firewalls are a core component of defensive cybersecurity. In this task, I explored how to use built-in Windows firewall features to control both inbound and outbound traffic, ensuring only trusted communication is allowed.

---

## ⚙️ Steps Performed

### ✅ 1. Enabled Windows Defender Firewall
- Opened **Windows Security > Firewall & network protection**
- Ensured the firewall was enabled for all profiles: **Domain**, **Private**, and **Public**

### ✅ 2. Accessed Advanced Settings
- Opened **Windows Defender Firewall with Advanced Security**
- Navigated to **Inbound** and **Outbound Rules**

### ✅ 3. Created an Outbound Rule
- Blocked a specific application (e.g., Chrome) from accessing the internet
- Path used: `C:\Program Files\Google\Chrome\Application\chrome.exe`
- Action: Block the connection

### ✅ 4. Created an Inbound Rule
- Allowed incoming traffic on **port 80 (HTTP)** for web traffic
- Protocol: TCP
- Action: Allow the connection

### ✅ 5. Reviewed Rule Management
- Learned how to **enable, disable, edit, or delete** firewall rules
- Understood the difference between **per-application** and **per-port** rules

---

## 🔍 Key Learnings

- ✅ Understanding of **Windows Defender Firewall**
- ✅ Importance of **inbound vs outbound traffic**
- ✅ Concept of **ports** (e.g., port 80 for HTTP, port 443 for HTTPS)
- ✅ Practical hands-on with real-world firewall rule configuration

---

## 🖼️ Screenshots

1. ✅ **Firewall Enabled**
   ![Firewall Enabled](screenshots/Firewall-enabled)

2. ✅ **Blocked Chrome – Outbound Rule**
   ![Outbound Rule](screenshots/outbound-rule)

3. ✅ **Allowed Port 80 – Inbound Rule**
   ![Inbound Rule](screenshots/inbound-rule)

---

## 🔗 Task Reference (Instructions)

> Enable and configure Windows Defender Firewall or a similar firewall.  
> Set rules to block or allow specific applications or ports.

---

## 🎯 Outcome

Completing this task enhanced my understanding of system-level defensive security. I learned how firewalls act as a first line of defense by monitoring and controlling both incoming and outgoing traffic. This hands-on experience taught me how to configure custom firewall rules to block or allow specific applications and ports, which is essential for securing personal systems against unauthorized access and potential threats.
