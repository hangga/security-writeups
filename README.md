# Security Writeups

A curated collection of real-world application security research, vulnerability disclosures, and technical writeups.

These cases focus on vulnerabilities uncovered through manual testing, source code analysis, and business logic exploration—not automated scanning.

## Topics

- Broken Access Control
- IDOR / BOLA
- Business Logic Vulnerabilities
- Authentication & Authorization
- API Security

## Writeups

### The MFA Bypass That Wasn't an MFA Problem
**Authentication / Authorization**

An investigation into an apparent MFA bypass that ultimately revealed broken API authorization, demonstrating why strong authentication cannot compensate for flawed backend access control.

🔗 https://cybersecuritywriteups.com/the-mfa-bypass-that-wasnt-an-mfa-problem-a-lesson-in-broken-api-authorization-b6f0fbd4154f

---

### How I Found an Email Verification Bypass on an AI Freelance Platform
**Authentication**

A real-world email verification bypass caused by inconsistent state management between the registration and email verification flows, allowing accounts to be created with unverified email addresses.

🔗 https://infosecwriteups.com/how-i-found-an-email-verification-bypass-on-an-ai-freelance-platform-6ad76663b658

---

### From Quantity Manipulation to Negative Shipping Costs
**Business Logic**

A business logic flaw in an e-commerce application that allowed manipulation of order calculations through unexpected quantity values, resulting in negative shipping costs.

🔗 https://cybersecuritywriteups.com/from-quantity-manipulation-to-negative-shipping-costs-a-business-logic-flaw-in-an-e-commerce-73f6c80b9b17

---

### I Was Removed From the Organization, But My Access Still Worked
**Broken Access Control**

A case study showing how access remained valid after organizational membership was revoked, highlighting common authorization and access lifecycle failures.

🔗 https://cybersecuritywriteups.com/i-was-removed-from-the-organization-but-my-access-still-worked-lessons-from-a-broken-access-151158d95f7d

---

### From a Simple Profile Endpoint to a 100k+ User IDOR on HackerRank
**IDOR / BOLA**

A seemingly harmless profile endpoint led to an authorization flaw affecting more than 100,000 user accounts.

🔗 https://cybersecuritywriteups.com/from-a-simple-profile-endpoint-to-a-100k-user-idor-on-hackerrank-6f9b6e6fe746

## Responsible Disclosure

All writeups follow responsible disclosure practices and exclude sensitive information that could impact users or organizations.

## About Me

I'm an Application Security Engineer and Security Researcher with a focus on application security, API security, business logic vulnerabilities, and authorization flaws.

- 🌐 Portfolio: https://hangga.web.id
- ✍️ Medium: https://hangga-aji-sayekti.medium.com
- 💼 LinkedIn: https://www.linkedin.com/in/hanggaajisayekti/
