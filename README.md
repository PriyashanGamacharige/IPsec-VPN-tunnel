# IPsec VPN Tunnel

This repository contains a **Cisco Packet Tracer lab** demonstrating the configuration of an **IPsec VPN Tunnel**.  
It shows how to securely connect two remote LANs over an untrusted IP backbone by using encryption and authentication.

---

## 📂 Files
- `IPsec_VPN_Tunnel.pkt` – Packet Tracer lab file  
- Any supporting notes or topology diagrams  

---

## 🚀 Features
- IPsec VPN tunnel between two routers  
- Data encryption and authentication for secure communication  
- Site-to-site connectivity between remote LANs  
- Verification of secure traffic flow  

---

## 🛠️ Requirements
- [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer) installed  

---

## ⚙️ How to Use
1. Download the `IPsec_VPN_Tunnel.pkt` file from the repo or **Releases** section.  
2. Open it with **Cisco Packet Tracer**.  
3. Check VPN configurations with commands like:  
   ```bash
   show crypto isakmp sa
   show crypto ipsec sa
   show running-config
