# 🖥️ **Active Directory / Domain Controller Exploitation**

Welcome to the **Active Directory / Domain Controller Exploitation** folder. Below, you'll find various challenges and write-ups demonstrating techniques for exploiting and escalating privileges in **Windows Domain environments** and **Active Directory** systems.

---

## 📄 **Available Write-Ups**

### 1. **Domain Controller Takeover**  
   🔑 **Techniques Covered**:
   - **Reconnaissance**: Initial scans using tools like `Nmap`, `RustScan`
   - **SMB Enumeration**: Identifying weaknesses with tools like `smbclient`, `smbmap`
   - **Exploiting Weak Authentication**: Brute force and weak credentials exploitation
   - **Privilege Escalation**: Using **Mimikatz** and **Evil-WinRM** to escalate to **Domain Admin**
   - **NTLM Hash Cracking**: Cracking captured NTLM hashes using **Hashcat** and **John the Ripper**
   - **Domain Controller Takeover**: Full control over the Domain Controller and ensuring persistence

   📄 [Domain Controller Takeover Write-Up (PDF)](https://github.com/Prashant-Bhatt-2000/CTF-Writeups/blob/main/tryhackme/Ra_(WindCorp).pdf)

---

## 📚 **Learning Resources**

- [BloodHound - Active Directory Enumeration and Privilege Escalation](https://github.com/BloodHoundAD/BloodHound)
- [Mimikatz - A tool for credential dumping and privilege escalation](https://github.com/gentilkiwi/mimikatz)
- [GTFOBins - A Practical Resource for PrivEscalation](https://gtfobins.github.io/)
- [Active Directory Privilege Escalation Book (HackTricks)](https://book.hacktricks.xyz/windows-hardening/windows-privilege-escalation)

---

## 🛠️ **Tools Used**

- **Nmap**: For network scanning and service enumeration.
- **Mimikatz**: For credential dumping and privilege escalation.
- **BloodHound**: For Active Directory enumeration and finding privilege escalation paths.
- **Evil-WinRM**: For remote Windows management and shell access.
- **Hashcat** & **John the Ripper**: For cracking NTLM hashes.

---

## ⚠️ **Important Note**
This repository contains write-ups and methodologies for educational purposes. The exploitation techniques demonstrated should only be used in legal environments such as Capture The Flag (CTF) challenges or penetration testing engagements with explicit permission.

---
