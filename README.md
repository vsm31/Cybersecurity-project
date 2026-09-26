# 🔐 Organisation Network Security – Wireless LAN Hardening

A Cisco Packet Tracer project simulating a secure corporate wireless network.

## 📋 Problem Statement
Configure a wireless network to protect against unauthorized access and interception, as a network administrator would for a real organization.

## 🎯 What Was Done
- Configured WAN settings on the router
- Secured WiFi with **WPA2-Personal (AES)** encryption
- Enabled **MAC Filtering** to allow only authorized devices
- Changed default router admin password
- Verified that authorized PCs connect and browse the internet, while an unauthorized device (Intruder laptop) is blocked

## 🖧 Network Setup
- ISR Router + Switch → DNS/Web Server & internet access
- WiFi Router (SSID: `IT_Dept`) → 3 authorized employee laptops
- 1 unauthorized "Intruder" laptop used to test security
 <img width="1047" height="695" alt="image" src="https://github.com/user-attachments/assets/7fa5c870-96cb-4cbe-b9b1-b45ca3c5abf2" />


## 🛡️ Key Config

| Setting | Value |
|---|---|
| SSID | IT_Dept |
| Security | WPA2-Personal (AES) |
| Password | cisco123 |
| MAC Filtering | Enabled (Permit list only) |
| Admin Password | cisconet123 |

## ✅ Result
Authorized employees connected to WiFi and reached `www.cisco.com` successfully. The intruder's device, not on the MAC whitelist, was blocked from joining the network — confirming the security setup works.

## 🧰 Tools Used
Cisco Packet Tracer

## 📁 Files
- `Vivek_Mohite_NIIT.pka` – Packet Tracer project file (open with [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer))
