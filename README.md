# DVWA Web Application VAPT

This repository presents a structured Vulnerability Assessment and Penetration Testing (VAPT)
exercise performed on Damn Vulnerable Web Application (DVWA) within a controlled lab environment.

The objective of this assessment was to identify, exploit, and analyze common web application
vulnerabilities while demonstrating a clear understanding of attack vectors, impact, and remediation.

---

## Scope of Assessment

Target Application:
- Damn Vulnerable Web Application (DVWA)

Vulnerability Classes Assessed:
- SQL Injection (SQLi)
- Cross-Site Scripting (XSS)

Environment:
- Isolated local lab setup
- No real-world or production systems involved

---

## Methodology Overview

The assessment followed a practical, attacker-oriented approach:

1. Application reconnaissance and input identification
2. Manual vulnerability testing using crafted payloads
3. Validation of exploitable behavior through controlled proofs of concept
4. Analysis of security impact and risk exposure
5. Documentation of mitigation strategies aligned with secure coding practices

Both manual testing and logic-based exploitation techniques were used to ensure
a deeper understanding beyond automated tool output.

---

## Key Findings

### SQL Injection (SQLi)
- Improper input handling allowed manipulation of backend SQL queries
- Enabled database enumeration and sensitive data extraction
- Demonstrated potential for authentication bypass and full database compromise

### Cross-Site Scripting (XSS)
- Identified stored and reflected XSS vectors
- Successful execution of injected JavaScript in user browser context
- Highlighted risks including session hijacking and client-side attacks

---

## Impact Analysis

The identified vulnerabilities collectively demonstrate how insufficient input
validation and output encoding can lead to:

- Unauthorized access to sensitive data
- Compromise of application integrity
- User session manipulation
- Increased risk of secondary attacks

---

## Recommendations

- Implement parameterized queries and prepared statements
- Enforce strict input validation and output encoding
- Apply Content Security Policy (CSP)
- Follow secure development lifecycle (SDLC) practices
- Perform regular security assessments and code reviews

---

## Deliverables

- Detailed VAPT report documenting findings, proof of concept, impact, and remediation

---

## Ethical Notice

All testing activities documented in this repository were conducted exclusively
on intentionally vulnerable lab applications for educational purposes.

No unauthorized systems were tested.

## Author

**Mahil Joshi**  
- LinkedIn: https://linkedin.com/in/mahiljoshi  
- GitHub: https://github.com/mahiljoshi  
