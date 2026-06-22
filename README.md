# Security Writeups

A curated collection of real-world security research, vulnerability disclosures, and application security case studies.

Most findings were discovered through manual testing, source analysis, and business logic exploration rather than automated scanning.

---

## About

I'm an Application Security Engineer and Security Researcher focused on:

* Broken Access Control
* IDOR / BOLA
* Business Logic Vulnerabilities
* Authentication & Authorization Issues
* API Security
* Secure Coding

This repository serves as an index of my public security writeups.

---

## Published Writeups

### 1. The MFA Bypass That Wasn't an MFA Problem

**Category:** Authentication / Authorization

A case study showing how an apparent MFA bypass ultimately traced back to broken API authorization controls. The issue highlights the difference between authentication and authorization failures and why MFA alone cannot protect insecure backend logic.

🔗 https://cybersecuritywriteups.com/the-mfa-bypass-that-wasnt-an-mfa-problem-a-lesson-in-broken-api-authorization-b6f0fbd4154f

---

### 2. From Quantity Manipulation to Negative Shipping Costs

**Category:** Business Logic Vulnerability

An e-commerce business logic flaw that allowed manipulation of purchase calculations through unexpected quantity values, ultimately leading to negative shipping costs and incorrect order totals.

🔗 https://cybersecuritywriteups.com/from-quantity-manipulation-to-negative-shipping-costs-a-business-logic-flaw-in-an-e-commerce-73f6c80b9b17

---

### 3. I Was Removed From the Organization, But My Access Still Worked

**Category:** Broken Access Control

A practical example of improper authorization enforcement where access persisted even after organizational membership was revoked, demonstrating common access lifecycle management failures.

🔗 https://cybersecuritywriteups.com/i-was-removed-from-the-organization-but-my-access-still-worked-lessons-from-a-broken-access-151158d95f7d

---

### 4. From a Simple Profile Endpoint to a 100k+ User IDOR on HackerRank

**Category:** IDOR / BOLA

A real-world account access vulnerability discovered through a seemingly harmless profile endpoint that exposed access to more than 100,000 user profiles.

🔗 https://cybersecuritywriteups.com/from-a-simple-profile-endpoint-to-a-100k-user-idor-on-hackerrank-6f9b6e6fe746

---

## Key Areas of Research

| Area                  | Examples                                   |
| --------------------- | ------------------------------------------ |
| Broken Access Control | Privilege Escalation, Authorization Bypass |
| IDOR / BOLA           | Object Reference Manipulation              |
| Business Logic        | Pricing, Workflow, Validation Flaws        |
| API Security          | Authorization, Data Exposure               |
| Authentication        | MFA & Session Management Issues            |

---

## Responsible Disclosure

All research published here follows responsible disclosure practices.

* No user accounts were abused.
* No automated harvesting was performed.
* No data was retained beyond validation requirements.
* Findings were reported to affected organizations whenever applicable.

---

## Connect

* Medium: [https://medium.com/@hanggaaji](https://hangga-aji-sayekti.medium.com/)
* Portfolio: [hangga.web.id](https://hangga.web.id)
* LinkedIn: [https://linkedin.com/in/hanggaaji](https://www.linkedin.com/in/hanggaajisayekti/)
