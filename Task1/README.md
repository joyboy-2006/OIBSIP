# 📄 Nmap Scan Report - Task 1
## 🎯 Objective
Perform a network scan using **Nmap** to identify open ports, running services, and operating system information on a target machine (`192.168.153.1`).


---
## 🧰 Tools Used
- **Tool**: Nmap 7.99 
- **Platform**: Kali Linux

---
## 🎬 Demo Video
please download nmap practical.mp4 as raw video.

---
## Open Ports found
(`3306/tcp`) - this means port 3306 is open and accessible over the network

---
## 🧪 Command Executed
```bash
nmap -sS -sV -O -oN nmap_results.txt 192.168.153.1

