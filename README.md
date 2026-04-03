# BWAPP Vulnerability Assessment & Penetration Testing (VAPT) Report 🛡️


This project presents a Vulnerability Assessment and Penetration Testing (VAPT) conducted on the bWAPP (Buggy Web Application) in a controlled lab environment.
The purpose of this assessment is to identify, exploit, and document security vulnerabilities across all DVWA modules and difficulty levels, and provide actionable remediation steps.

---

## ⚙️Environment Setup
- Target: bWAPP v2.2
- OS: Kali Linux
- Tools: Burp Suite, Docker
- Access: http://127.0.0.1:8080

---

## 🛠️ Vulnerabilities Covered

| # | Vulnerability | CWE ID | CVSS | Risk Level |
|---|--------------|--------|------|-----------|
| 1 | SQL Injection | CWE-89 | 9.8 | Critical |
| 2 | Cross-Site Scripting (XSS) | CWE-79 | 7.4 | High |
| 3 | OS Command Injection | CWE-77 | 9.8 | Critical |
| 4 | Cross-Site Request Forgery (CSRF) | CWE-352 | 6.5 | Medium |
| 5 | Broken Authentication | CWE-287 | 8.0 | High |
| 6 | HTML Injection | CWE-79 | 6.1 | Medium |

---
## Methodology

1. **Reconnaissance**  
   Explored application features and identified input points.

2. **Exploitation**  
   Used Burp Suite and manual payloads to exploit vulnerabilities.

3. **Documentation**  
   - Detailed proof of concept
   - Mitigation recommendations 
   - Screenshots of each step
---
## Evidence
Detailed screenshots and proof of exploitation are included in the full report PDF.

---
## 📄 Documentation
📥 [Download Full Technical Report(PDF)](./Gracious_Akalonu_Pentest_Report.pdf)

---

Submitted by: Gracious Chioma Akalonu.
