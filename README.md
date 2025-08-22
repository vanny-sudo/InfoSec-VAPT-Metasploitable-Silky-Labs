# 🔐 InfoSec-VAPT-Metasploitable-Silky-Labs

## 📌 Project Overview  

This repository documents penetration testing exercises conducted on:  
- **Metasploitable 2** (intentionally vulnerable VM)  
- **Silky-CTF 0x02** (Capture-the-Flag challenge VM)  

The tests were performed in a **Linux environment (Kali OS)** with the aim of identifying vulnerabilities, exploiting them, gaining privileged access, and documenting findings.  
This project is strictly for **educational and research purposes**.  

---

## 🎯 Objectives  

- Perform reconnaissance and scanning on target systems.  
- Identify services and vulnerabilities.  
- Exploit vulnerabilities to gain access.  
- Practice privilege escalation techniques.  
- Capture CTF flags and document results.  
- Provide recommendations to mitigate discovered vulnerabilities.  

---

## 🛠️ Tools & Technologies  

- **Operating System**: Kali Linux / Parrot Security OS  
- **Targets**: Metasploitable 2, Silky-CTF 0x02  
- **Penetration Testing Tools**:  
  - `nmap` – Port scanning & service detection  
  - `hydra` / `john` – Password cracking  
  - `msfconsole` – Metasploit Framework  
  - `ssh`, `netcat` – Remote access & reverse shells  
  - `gobuster`, `enum4linux` – Enumeration  
  - Other Linux utilities  

---

## 🖥️ Lab Setup  

1. Install **VirtualBox** or **VMware**.  
2. Import Metasploitable 2 and Silky-CTF VMs.  
3. Configure them in **Host-Only** or **NAT Network** mode.  
4. Verify network connectivity:  
   ```bash
   ping <target-ip>
   ```  

---

## 🚀 Exploitation Walkthrough  

### 🔹 Metasploitable 2  

1. **Scanning:**  
   ```bash
   nmap -sV <target-ip>
   ```  
2. **Vulnerability Identified:** Example – VSFTPD backdoor, weak MySQL credentials, outdated Tomcat, etc.  
3. **Exploitation:** Document steps, commands, and results.  
4. **Privilege Escalation:** Gained root access.  

### 🔹 Silky-CTF 0x02  

1. **Enumeration:** Directory brute-forcing, service discovery.  
2. **Vulnerability Discovered:** Example – Weak login credentials, misconfigured service.  
3. **Exploitation:** Access gained through discovered vulnerability.  
4. **Flag Capture:** Captured final flag and documented proof.  
---

## 📊 Results & Findings  

- **Metasploitable 2**: Multiple critical vulnerabilities exploited (FTP, MySQL, Tomcat, etc.).  
- **Silky CTF 0x02**: Successfully enumerated services, exploited weaknesses, and captured final flag.  
- **Recommendations**:  
  - Patch outdated services.  
  - Enforce strong password policies.  
  - Restrict unnecessary ports.  
  - Regular vulnerability assessments.  

---

## ⚠️ Disclaimer

This project is for **educational use only** in a controlled lab environment.  
Unauthorized hacking of systems is illegal. 

---

## 👤 Author  
**Irakoze Grace Vanny** 

📌 Information Security Final Project

📧 Contact 
**Email:** vannygrace2020@gmail.com
