# OWASP Juice Shop Security Assessment
Security assessment of OWASP Juice Shop using Burp Suite. Demonstrates identification, exploitation, and documentation of common web application vulnerabilities.

OWASP Juice Shop Security Assessment
Overview

This project documents a web application security assessment performed against OWASP Juice Shop using Burp Suite and Firefox. The goal was to identify, analyze, and document common web application vulnerabilities in a controlled learning environment.

- Objectives
  - Intercept and analyze HTTP requests
  - Identify security vulnerabilities
  - Understand common web application attack vectors
  - Document findings and remediation recommendations
  - Practice web application security testing techniques

- Environment
  - OWASP Juice Shop
  - Burp Suite Community Edition
  - Firefox
  - exiftool
  - docker
  - Kali Linux

- Vulnerabilities Assessed:
  
  - Miscellaneous
 ![Misscellaneous](screenshots/score_board/beautifyer_scoreBoard_found.jpg)
 ![Misscellaneous](screenshots/score_board/juice_shop_scoreboard.jpg)

  - Security Misconfiguration
 ![Security Misconfiguration](screenshots/error_handling/error_handling_get_request.jpg)
 ![Security Misconfiguration](screenshots/error_handling/error_handling_solved.jpg)

  - Improper Input Validation
 ![Security Misconfiguration](screenshots/missing_encoding/missing_encoding_added.jpg)
 ![Security Misconfiguration](screenshots/missing_encoding/missing_encoding_cat_shown.jpg)
 ![Security Misconfiguration](screenshots/missing_encoding/unaccessible_photo.jpg)

 ![Security Misconfiguration](screenshots/repetitive_registration/repetitive_registration.jpg)
![Security Misconfiguration](screenshots/repetitive_registration/repetitive_registration_password_not_match.jpg)

  - SQL Injection
![SQL Injection](screenshots/admin_login/login_admin_sql_s.jpg)
![SQL Injection](screenshots/admin_login/login_admin_solved.jpg)
    
  - Cross-Site Scripting (XSS)
![Cross-Site Scripting](screenshots/bonus_payload/juice_shop_jscode.jpg)
![Cross-Site Scripting](screenshots/bonus_payload/juice_shop_xss_bonus.jpg)

  - Observability Failures
![Observability Failures](screenshots/exposed_metrics/exposed_metrics.jpg)
![Observability Failures](screenshots/exposed_metrics/juice_shop_metrics.jpg)

  - Broken Access Control
![Broken Access Control](screenshots/admin_section/admin_section_path.jpg)
![Broken Access Control](screenshots/admin_section/admin_section_solved.jpg)

  - Sensitive Data Exposure
![Sensitive Data Exposure](screenshots/confidential_documents/hidden_files_confidential.jpg)
![Sensitive Data Exposure](screenshots/confidential_documents/ftp_hidden_file.jpg)
![Sensitive Data Exposure](screenshots/confidential_documents/ftp_acquisitions_confid.jpg)


- Methodology
  - Install Foxy Proxy and certificates.
  - Configured browser proxy through Burp Suite.
  - Intercepted and analyzed application traffic.
  - Tested application functionality for security weaknesses.
  - Documented identified vulnerabilities.
  - Provided remediation recommendations.

- Repository Structure
/findings – Detailed vulnerability reports
/screenshots – Evidence and screenshots
/report – Security assessment report

- Skills Demonstrated
  - Web Application Security Testing
  - Burp Suite
  - HTTP Request Analysis
  - Vulnerability Assessment
  - Security Documentation
  - Security Reporting
  - Disclaimer

This project was conducted in a legal training environment using OWASP Juice Shop, an intentionally vulnerable application designed for security education and testing.
