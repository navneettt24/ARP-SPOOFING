 ARP Spoofing (ARP Poisoning)

## 📌 Overview
ARP Spoofing (also known as ARP Poisoning) is a *Man-in-the-Middle (MITM)* attack technique used in local area networks (LAN).  
In this attack, an attacker sends fake ARP replies to associate their MAC address with the IP address of another device (usually the gateway).

![Image](https://github.com/user-attachments/assets/fde96f37-2103-41e5-870b-635165441565)

---

## 🧠 What is ARP?
*ARP (Address Resolution Protocol)* maps an IP address to a MAC address in a local network.

Example:
- IP: 192.168.56.102
-  MAC: 8:0:27:1f:b7:23
  
 ![Image](https://github.com/user-attachments/assets/2f207c85-fed4-40ba-99f2-80d0435faba0) 


ARP has *no authentication*, which makes it vulnerable.

---

## ⚔️ How ARP Spoofing Works
1. Attacker scans the local network
2. Attacker sends forged ARP replies
3. Victim believes attacker is the router
4. Traffic passes through attacker
5. Attacker can sniff, modify, or block data
   
![Image](https://github.com/user-attachments/assets/5aa039cc-3fcf-45f6-b2f6-e208f93f5f13)
---

## 🎯 Impact of ARP Spoofing
- Packet sniffing
- Session hijacking
- Credential theft
- DNS spoofing
- MITM attacks
  
![Image](https://github.com/user-attachments/assets/73a6fe68-1206-45d1-ab09-8c1dc8e5c267)
---

## 🛡️ Prevention Techniques
- Use *Static ARP entries*
- Enable *Dynamic ARP Inspection (DAI)*
- Use *HTTPS / TLS*
- Monitor ARP tables
- Use IDS/IPS systems

---
![Image](https://github.com/user-attachments/assets/8ece751a-4b6f-4f03-b4e0-72e0a40b1ae5)
## 🧪 Learning Environment
This concept should be practiced only in:
- Virtual labs
- Test networks
- CTF challenges
- Authorized environments

---
![Image](https://github.com/user-attachments/assets/7ab7ded4-153a-49e9-ae05-591c0c6fe38a)
## ⚠️ Disclaimer
This repository is created *strictly for educational and ethical purposes only*.  
Any misuse of this knowledge is the sole responsibility of the user.

---

## 📚 References
- RFC 826 – Address Resolution Protocol
- OWASP Network Attacks
- MITRE ATT&CK Framework
