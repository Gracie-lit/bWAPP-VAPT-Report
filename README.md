# BWAPP VAPT Report

## Overview
This project presents a Vulnerability Assessment and Penetration Testing (VAPT) conducted on the bWAPP (Buggy Web Application) in a controlled lab environment.

The objective was to identify and exploit common web application vulnerabilities and understand their impact.

---

## Environment
- Target: bWAPP v2.2
- OS: Kali Linux
- Tools: Burp Suite, Docker
- Access: http://127.0.0.1:8080

---

## Vulnerabilities Identified

### SQL Injection (Critical)
- Bypassed authentication using `' OR 1=1#`
- Retrieved all database records
- Logged in without valid credentials

### Cross-Site Scripting (XSS)
- Reflected XSS
- Stored XSS
- Executed malicious scripts in browser

### OS Command Injection (Critical)
- Executed system commands (`ls`, `whoami`)
- Retrieved server file structure

### CSRF
- Changed user password without verification
- Performed unauthorized actions

### Broken Authentication
- Extracted credentials from page source
- Logged in using exposed credentials

### HTML Injection
- Injected HTML into application interface

---

## Key Learnings
- Practical exploitation of OWASP Top 10 vulnerabilities
- Hands-on use of Burp Suite for request interception
- Understanding of real-world attack techniques

---

## Screenshots
See `/screenshots` folder for proof of exploitation.

---

## Full Report
(Upload your PDF here)
