# VAPT Report — DVWA (Damn Vulnerable Web Application)

## Internship Details
- **Student:** Vinod
- **Institution:** CMR Institute of Technology
- **Program:** CampusPe: Cybersecurity and Ethical Hacking Internship
- **Assessment Date:** May 11, 2026

## Overview
This repository contains a comprehensive Vulnerability Assessment and Penetration Testing (VAPT) report conducted on DVWA (Damn Vulnerable Web Application) deployed via Docker in a controlled lab environment.

## Lab Environment
- **Attacker Machine:** Kali Linux — 192.168.1.9
- **Target Machine:** macOS Host (Docker) — 192.168.1.5:8081
- **Target Application:** DVWA (Damn Vulnerable Web Application)

## Tools Used
- Nmap — Network reconnaissance
- Burp Suite Community — Traffic interception
- curl — Security header analysis
- Firefox — Manual web testing
- Docker — DVWA container hosting on macOS

## Vulnerabilities Found

| # | Vulnerability | Severity |
|---|--------------|----------|
| 1 | Open Port Exposure | HIGH |
| 2 | SQL Injection — User Data Dump | CRITICAL |
| 3 | SQL Injection — Password Hash Extraction | CRITICAL |
| 4 | XSS Reflected | HIGH |
| 5 | Command Injection | CRITICAL |
| 6 | Missing Security Headers | MEDIUM |

## Files
- `VAPT_Report_Vinod.pdf` — Full professional VAPT report (PDF)
- `VAPT_Report_Vinod.docx` — Full professional VAPT report (Word)
- `0_metasploitable_ifconfig.png` — Target machine IP configuration
- `1_nmap_scan.png` — Nmap reconnaissance results
- `2_kali_ifconfig.png` — Attacker machine IP configuration
- `3_dvwa_security_low.png` — DVWA security level set to Low
- `4_sql_injection.png` — SQL Injection proof of concept
- `5_sql_passwords.png` — Password hash extraction
- `6_xss.png` — XSS reflected proof of concept
- `7_command_injection.png` — Command injection proof of concept
- `8_security_headers.png` — Missing security headers
- `9_burpsuite_open.png` — Burp Suite interception tool
- `10_burpsuite_intercept.png` — HTTP traffic intercepted
