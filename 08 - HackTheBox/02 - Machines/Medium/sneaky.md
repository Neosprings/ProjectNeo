


# Sneaky

**ID:** 19
**OS:** Linux
**Difficulty:** Medium
**Points:** 30
**Stars:** 4.9
**Release Date:** 2017-05-14
**User Owns:** 2,407
**Root Owns:** 1,969

**Tags:**
- Medium
- Linux
- Web


# HTB MACHINE - # HTB MACHINE - `= this.machine_name` (`= this.difficulty`)

### *Sunday, March 2nd, 2025*

| 📌 **INFO**<br><br><br><br>                                                                                                            | 🛠 **Methodology Progress**                                                                                                     |
| -------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| **Machine Name:** `= this.machine_name`<br>**IP Address:** `= this.ip_address`<br>- [ ] Complete<br>- [ ] User Flag<br>- [ ] Root Flag | - [ ] **Recon**<br>- [ ] **Enumeration**<br>- [ ] **Foothold**<br>- [ ] **Privilege Escalation**<br>- [ ] **Post-Exploitation** |

---

## 🔎 **Enumeration**

### **Basic Scans**
```bash
nmap -p- --min-rate=5000 -T4 -sC -sV -oN nmap/{{machine_name}}_allports.txt {{ip_address}}
```

| ~                                   | ~                             |
| ----------------------------------- | ----------------------------- |
| ![[02 Ffuf - Fuzz Faster You Fool]] | ![[01 Information Gathering]] |








## ⚡ **Foothold**





- **Exploit / Attack Vector:**
- **Vulnerability:**
- **Exploit Code:**




## 🔄 **Lateral Movement (if applicable)**

- **Access to another user or privilege level?**
- **Docker Escape, SSH, RDP, etc.**

## 🔺 **Privilege Escalation**

- **Low Privilege User:**
- **Method Used (Kernel Exploit, Sudo, SUID, etc.):**


## 📝 **Post-Exploitation**

- **User Flag:** `cat /home/user*/flag.txt`
- **Root Flag:** `cat /root/root.txt`
- **Any sensitive files discovered?**

### 🔑 **Credentials & Hashes**

| Service | Username | Password/Hash | Cracked? |
| ------- | -------- | ------------- | -------- |
| SSH     | user     | hash_here     |          |
| MySQL   | root     | hash_here     |          |

## 📖 **References & Notes**

- **Exploit DB / CVE Link:**
- **Tools Used:**
- **Any extra notes?**



