# VulnBox 🛡️

A documentation and learning repository exploring common web vulnerabilities using DVWA and TryHackMe. This project combines hands-on exploitation, technical writeups, and custom-built scripts to demonstrate both my understanding of web security and ability to write practical tooling.

---

## 📘 What’s Inside

| Vulnerability      | Platform     | Status |
|--------------------|--------------|--------|
| SQL Injection      | DVWA         | 🔧 In Progress |
| Cross Site Scripting (XSS) | DVWA         | 🔧 In Progress|
| CSRF               | DVWA         | 🔧 In Progress |
| Command Injection  | TryHackMe    | 🕒 Planned |
| File Upload Bypass | TryHackMe    | 🕒 Planned |

---

## ⚙️ Tools Used

- DVWA (Damn Vulnerable Web App)
- TryHackMe Labs
- Burp Suite Community Edition
- OWASP ZAP
- Kali Linux
- Python 3

---
## 💻 Featured Tool: SQL Injection Exploit Script

### 🔧 Description:
This Python script demonstrates a basic SQL Injection attack on DVWA’s login form by submitting the classic `' OR '1'='1` payload and checking if the login was bypassed.

### 🧪 How It Works:
- Sends a POST request to the login form
- Injects malicious SQL payload in the username field
- Analyzes the server response for success indication

### 🔐 Disclaimer:
- Only use this tool on legal practice environments like DVWA.

### 📝 Writeup Format:
- Each vulnerability has its own folder and includes:

- Technical explanation

- Step-by-step exploitation

- Screenshots or GIFs

- Mitigation discussion

- Any supporting scripts or payloads



### 📌 Notes
- This project is strictly for educational use

- All tests are performed on legal platforms (DVWA, TryHackMe, localhost only)

