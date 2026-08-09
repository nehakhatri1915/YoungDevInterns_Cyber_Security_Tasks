# 🌐 Task 3 – Analyze Network Traffic

📌 **Category:** Intermediate Tasks
🏢 **Internship Program:** YoungDevInterns – Cyber Security Internship

---

## 📋 Task Overview

**Objective:** Capture and analyze live network traffic using Wireshark to understand common network protocols and identify traffic patterns.

Packet analysis is a core skill in network security. It allows defenders to detect anomalies, understand normal traffic behavior, and identify unencrypted or suspicious communication.

---

## ⚙️ Steps Performed

### ✅ 1. Installed Wireshark
- Installed Wireshark along with Npcap (https://www.wireshark.org/download.html) 
<img width="971" height="401" alt="image" src="https://github.com/user-attachments/assets/80787b74-c06d-406b-baf2-3469d3050811" />


### ✅ 2. Captured Live Network Traffic
- Selected the active network interface (Wi-Fi)
- Started a live packet capture
<img width="1464" height="594" alt="image" src="https://github.com/user-attachments/assets/e670240e-e9fa-4071-9a01-9455efe6b9a5" />


### ✅ 3. Generated Traffic for Analysis
- Visited an HTTP (unencrypted) website
- Visited an HTTPS (encrypted) website
- Ran a `ping` command to generate ICMP traffic

### ✅ 4. Filtered and Analyzed Protocols
- `http` — reviewed unencrypted request/response data
- `tls` — reviewed encrypted HTTPS handshake traffic
- `dns` — reviewed domain name resolution queries
- `icmp` — reviewed ping request/reply packets

### ✅ 5. Reviewed Packet Structure
- Expanded individual packets to examine Ethernet, IP, TCP, and application-layer headers

---

## 🔍 Key Learnings

- ✅ How to capture and filter live network traffic using Wireshark
- ✅ Difference between HTTP (plaintext, readable) and HTTPS (encrypted) traffic
- ✅ How DNS resolution and ICMP (ping) traffic appear at the packet level
- ✅ Understanding of how data is structured and layered as it moves across a network (Ethernet → IP → TCP/UDP → Application)
- ✅ Why unencrypted protocols (like HTTP) pose a security risk when sensitive data is transmitted

---

## 🔗 Task Reference (Instructions)

> Use a tool like Wireshark to capture and analyze network packets.
> Identify common network protocols and traffic patterns.

---

## 🎯 Outcome

Completing this task gave me hands-on experience with network traffic analysis, a foundational skill for both defensive monitoring and penetration testing. I learned how to capture live traffic, filter by protocol, and interpret packet-level data including recognizing the security implications of unencrypted HTTP traffic compared to encrypted HTTPS communication.
