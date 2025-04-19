# 🔍 Nmap Scan on DVWA

## 📝 Description
Performed a network scan on a vulnerable target (Metasploitable 2 running DVWA) using Nmap to identify open ports, running services, and OS information.

## 🛠 Tools Used
- [Nmap](https://nmap.org/)
- Netdiscover (for initial network reconnaissance)

## 🧪 Steps Performed
1. Discovered the target IP address [192.168.254.131]using `netdiscover`
2. Conducted a basic port scan using:
   ```bash
   nmap -sS 192.168.254.131 
