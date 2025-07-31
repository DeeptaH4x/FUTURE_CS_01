# Task 1: Web Application Security Testing

**Intern Name:** Deepta Chakravarty  
**Task Code:** FUTURE_CS_01  
**Domain:** Cybersecurity  
**Internship:** Future Interns (Self-paced)  

---

## Objective
To perform web application security testing on **DVWA (Damn Vulnerable Web Application)** and identify common vulnerabilities such as:

- SQL Injection (SQLi)  
- Reflected Cross-Site Scripting (XSS)  
- Stored Cross-Site Scripting (XSS)

---

## Tools Used
- DVWA (Damn Vulnerable Web Application)  
- Burp Suite Community Edition  
- Kali Linux  
- Google Chrome Browser  

---

## Vulnerabilities Tested

### 1. SQL Injection (SQLi)
- **Payload Used:** `' OR '1'='1`  
- **Result:** Extracted user data and bypassed authentication (Critical)

### 2. Reflected XSS
- **Payload Used:** `<script>alert("XSS")</script>`  
- **Result:** Alert box triggered; input reflected without sanitization (High)

### 3. Stored XSS
- **Payload Used:** `<script>alert("Stored XSS")</script>`  
- **Result:** Script stored in backend and executed on every page load (Very High)

---

## Full Report
The detailed report is available in:  
**TASK 1-future interns.pdf**

---

## Outcome
This task helped me:

- Gain hands-on experience in **ethical web penetration testing**  
- Learn to **detect and exploit SQLi and XSS vulnerabilities**  
- Understand the importance of **input validation and secure coding practices**  

---

## Recommendations
- Use **parameterized queries / prepared statements** to prevent SQL Injection  
- **Sanitize and validate** all user inputs  
- **Encode output** before rendering in the browser  
- Implement **Content Security Policy (CSP)**  
- Perform **regular security audits and patching**  

---

> This project demonstrates the importance of secure coding and regular vulnerability testing to protect web applications.
