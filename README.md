# Task 1 – Web Application Security Testing

## Overview
This project involves conducting a security assessment of the **Damn Vulnerable Web Application (DVWA)** using automated and manual tools. The goal is to identify real-world vulnerabilities in alignment with the **OWASP Top 10 (2021)**.

## Tools Used
-  [OWASP ZAP]– for automated vulnerability scanning
-  [Burp Suite]– for manual testing & interception
-  [SQLMap]– for SQL injection exploitation
-  DVWA (Damn Vulnerable Web App) – testing environment

##  Deliverables
-  Final report with vulnerabilities, risk ratings, evidence, and remediation steps
-  OWASP Top 10 mapping checklist
-  Screenshots of vulnerabilities and scanner output
-  Logs from OWASP ZAP & Burp Suite


## Vulnerabilities Identified

| Vulnerability                         | Risk   | OWASP Category          |
|--------------------------------------|--------|--------------------------|
| SQL Injection (Login Form)           | High   | A03:2021 – Injection     |
| Missing CSP Header                   | Medium | A05:2021 – Misconfig     |
| Directory Browsing Enabled           | Medium | A05:2021 – Misconfig     |
| Hidden File Found                    | Medium | A05:2021 – Misconfig     |
| Clickjacking Protection Missing      | Medium | A05:2021 – Misconfig     |
| Insecure Cookies                     | Low    | A01:2021 – Access Control|
| Server Info Leakage (Headers)        | Low    | A06:2021 – Components    |
| X-Content-Type-Options Missing       | Low    | A05:2021 – Misconfig     |

## OWASP Top 10 (2021) Coverage

- A01: Broken Access Control
- A03: Injection
- A05: Security Misconfiguration
- A06: Vulnerable and Outdated Components
- A07: Identification & Authentication Failures

##Learning Outcomes
- Conducted end-to-end vulnerability testing on a live application
- Identified real exploitable flaws using industry tools
- Gained hands-on experience with OWASP methodologies
- Prepared a formal security report suitable for real-world clients
