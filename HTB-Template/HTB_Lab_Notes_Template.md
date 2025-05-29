# 🧪 HTB Lab Write-Up Template

## 📌 Target Information
- **Lab Name**: 
- **IP Address**: 
- **Operating System**: 
- **Difficulty**: 

---

## 🔍 Scanning
### Nmap
```
nmap -sC -sV -oA scans/nmap_initial <IP>
```

### Full Port Scan
```
nmap -p- -T4 -oA scans/nmap_full <IP>
```

---

## 🗂 Enumeration
### Web
- What services are running?
- Directory brute-forcing?

### Other Protocols
- SMB, FTP, SNMP, etc.

---

## 💥 Exploitation
- Exploit used:
- Steps to reproduce:

---

## 🔒 Privilege Escalation
- Method used:
- Credentials/reuse/escalation vector:

---

## 🧹 Post-Exploitation
- Flags:
- Cleanup:

---

## 🧠 Lessons Learned
- Summary of what worked, what didn’t.
