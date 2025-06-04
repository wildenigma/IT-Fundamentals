# Security Scenarios and Resolutions

This document illustrates practical security incidents linked to common vulnerabilities, including how they occur and how to mitigate or resolve them.

---

## Scenario 1: SQL Injection Attack on a Customer Portal

**What happened:**  
An attacker inputs malicious SQL into a login field, bypassing authentication and extracting customer data.

**How it was detected:**  
Unusual database query logs and abnormal user activity alerts.

**Resolution:**  
- Replaced vulnerable SQL queries with parameterized statements  
- Added input validation and sanitization  
- Deployed Web Application Firewall (WAF) rules

---

## Scenario 2: Stored Cross-Site Scripting on a Blog Comment Section

**What happened:**  
Malicious JavaScript code was injected into blog comments, stealing cookies of visitors.

**How it was detected:**  
Users reported suspicious redirects and stolen session tokens.

**Resolution:**  
- Implemented output encoding on all user-generated content  
- Added Content Security Policy headers  
- Educated developers on secure coding practices

---

## Scenario 3: Data Exposure from Public Cloud Storage

**What happened:**  
An AWS S3 bucket containing sensitive documents was set to public read access.

**How it was detected:**  
Routine security audit flagged the bucket permissions.

**Resolution:**  
- Updated bucket policies to restrict access  
- Enabled bucket logging and alerts for permission changes  
- Conducted company-wide training on cloud security best practices

---

## Scenario 4: Brute Force Attack Due to Weak Passwords

**What happened:**  
Attackers used automated tools to guess passwords on user accounts.

**How it was detected:**  
Multiple failed login attempts and lockout alerts.

**Resolution:**  
- Enforced strong password requirements  
- Implemented multi-factor authentication (MFA)  
- Added account lockout policies after repeated failed attempts

---

## Scenario 5: Application Crash Due to Buffer Overflow

**What happened:**  
An attacker sent oversized input causing the application to crash and potentially execute code.

**How it was detected:**  
Application logs showed segmentation faults and crashes.

**Resolution:**  
- Updated software to latest patched version  
- Added input validation and buffer size checks  
- Conducted code reviews for memory safety

---

## Scenario 6: Cloud API Abuse via Insecure Authentication

**What happened:**  
API keys were hardcoded and leaked, allowing attackers to manipulate cloud resources.

**How it was detected:**  
Unusual activity spikes and unexpected resource provisioning.

**Resolution:**  
- Rotated API keys immediately  
- Moved secrets to secure vaults  
- Added strict authentication and usage monitoring

---

# Summary

Understanding how vulnerabilities manifest in real environments helps prepare defenses. Regular audits, monitoring, user training, and secure coding prevent many incidents.

---

