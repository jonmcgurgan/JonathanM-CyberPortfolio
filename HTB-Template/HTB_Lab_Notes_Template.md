# 💻 HTB Lab Notes – [LAB NAME]

---

## 📋 General Information

- **Lab Name**: [e.g., Nibbles]  
- **Difficulty**: [Easy / Medium / Hard]  
- **IP Address**: [10.10.11.X]  
- **Operating System**: [Linux / Windows]  
- **Date Started**: [DD/MM/YYYY]  
- **Date Completed**: [DD/MM/YYYY]  

---

## 🔍 1. Enumeration

### 🔎 Port Scanning
nmap -sC -sV -oN scans/nmap-initial.txt 10.10.11.X

### 🧪 Version Detection
nmap -sV -p- -oN scans/nmap-full.txt 10.10.11.X

### 🌐 Web Enumeration
gobuster dir -u http://10.10.11.X -w /usr/share/wordlists/dirbuster/directory-list-2.3-medium.txt -o scans/gobuster.txt

### 🔌 HTTP Service Check
curl -I http://10.10.11.X

---

## 🎯 2. Exploitation

- **Vulnerability Identified**: [e.g., unauthenticated file upload]  
- **Exploit Used**: [custom / Metasploit / public PoC]  
- **Shell Access Achieved?**: [Yes / No]  
- **Payload Info**:  
  - Reverse Shell Type: [bash / php / etc.]  
  - IP & Port: [10.10.14.X:4444]  

---

## 🧗 3. Privilege Escalation

- **Method**: [e.g., SUID binary / kernel exploit]  
- **Tool(s) Used**: [linpeas / pspy / etc.]  
- **Root Shell Gained?**: [Yes / No]  
- **Notes**:  
  - [Add detailed steps taken to escalate privileges]

---

## 📝 4. Post Exploitation

- **Flags Captured**:  
  - User: [✔️ / ❌]  
  - Root: [✔️ / ❌]  
- **Files of Interest**:  
  - [Add any interesting config files, creds, etc.]  
- **Cracked Hashes / Passwords**:  
  - [user:password]

---

## 🧠 5. Lessons Learned

- [Summarise key takeaways, tools used, new techniques learned, etc.]

---

## 📎 Appendices

- Output Logs (Nmap, Gobuster, LinPEAS, etc.)  
- Screenshots (if using images folder)