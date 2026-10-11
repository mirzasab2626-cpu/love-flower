# Security Policy

We take the security of this project and the safety of its users seriously. This document outlines our security policies, supported versions, and the process for responsibly reporting potential vulnerabilities.

---

## 🛡️ Supported Versions

We actively provide maintenance and security updates for the following versions:

| Version | Supported          | Status             |
| :------ | :----------------: | :----------------- |
| `1.x.x` | :white_check_mark: | Currently Supported |
| `< 1.0` | :x:                | Deprecated / End of Life |

---

## 🔍 Reporting a Vulnerability

If you discover a security vulnerability within this repository, please do **NOT** open a public issue. We ask that you report it responsibly through private channels.

### How to Report

1. **Email Contact:** Please send an email to the repository maintainer with the subject line:
   `[SECURITY VULNERABILITY] - Flower Animation`
2. **GitHub Security Advisory:** Alternatively, if available on the repository, submit a confidential report via **GitHub Security Advisories** by navigating to `Security` > `Advisories` > `Report a vulnerability`.

### What to Include in Your Report

To help us investigate and resolve the issue quickly, please include:
- A clear description of the vulnerability.
- Step-by-step instructions or proof-of-concept (PoC) to reproduce the issue.
- The affected browsers, operating systems, or environments.
- Any potential impact or recommended fixes if known.

---

## ⏱️ Response & Resolution Timeline

We are committed to handling all valid security reports promptly:

- **Initial Acknowledgment:** Within **48 hours** of receiving your report.
- **Vulnerability Assessment:** Within **5 business days**, confirming severity and scope.
- **Remediation & Patch Release:** Security fixes will be prioritized and released as quickly as possible.
- **Public Disclosure:** Coordinated public disclosure will take place once a fix has been tested and deployed.

---

## 🔒 Client-Side Security Best Practices

As a purely static client-side web application, users deploying or hosting this project are encouraged to follow these standard web security best practices:

1. **HTTPS Enforcement:** Always deploy this application over HTTPS (e.g., via GitHub Pages, Vercel, Netlify, or Cloudflare) to ensure encryption in transit.
2. **Content Security Policy (CSP):** When serving in production, configure HTTP response headers with a restrictive CSP:
   ```http
   Content-Security-Policy: default-src 'self'; style-src 'self' 'unsafe-inline' https://fonts.googleapis.com; font-src 'self' https://fonts.gstatic.com; media-src 'self' https://cdn.pixabay.com;
   ```
3. **External Resources:** Avoid loading untrusted third-party scripts or external dependencies.

---

## 📜 Attribution & Thanks

We sincerely appreciate the efforts of security researchers and community members who practice responsible disclosure to help keep our open-source software safe.
