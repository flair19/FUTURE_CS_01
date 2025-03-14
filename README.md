# FUTURE_CS_01
Vulnerability assessment for OWASP Juice Shop web app

This project assessed the OWASP Juice Shop web application (http://localhost:3000) to identify and mitigate security vulnerabilities. Using Nmap (v7.94) for port scanning and OWASP ZAP (v2.14.0) for web vulnerability scanning, I conducted the assessment on Parrot OS as of March 14, 2025. The process involved reconnaissance, active scanning, and manual verification, resulting in 16 vulnerabilities: 2 High (Open Redirect, SQL Injection), 5 Medium (e.g., weak CSP, missing headers), 5 Low (e.g., error disclosure), and 4 Informational. Recommendations include input validation, parameterized queries, and security headers to enhance protection. 
