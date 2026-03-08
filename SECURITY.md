# Security Policy

## 🔒 Reporting a Vulnerability

If you discover a security vulnerability in DC Movies, please report it responsibly.

### How to Report

**DO NOT** create a public GitHub issue for security vulnerabilities.

Instead, please email: **security@deniscasian.com**

### What to Include

- Description of the vulnerability
- Steps to reproduce the issue
- Potential impact of the vulnerability
- Suggested fix if you have one

### Response Timeline

| Action | Timeframe |
|--------|-----------|
| Initial response | Within 48 hours |
| Status update | Within 7 days |
| Fix deployed | Depends on severity |

### Scope

The following are in scope:

- Authentication bypass
- Data exposure
- Cross-site scripting (XSS)
- Cross-site request forgery (CSRF)
- Injection vulnerabilities
- Authorization issues

The following are out of scope:

- Third-party services such as Firebase and Gumroad
- Social engineering attacks
- Physical attacks
- Denial of service attacks

### Recognition

While this is a private project and there is no bug bounty program, I will credit you in the changelog if desired and send a thank-you note.

## 🛡️ Security Measures in Place

- **Authentication** — Firebase Auth with secure session management
- **Database** — Firestore security rules restrict access
- **API Keys** — Proxied through Cloudflare Workers
- **HTTPS** — Enforced on all connections
- **Content Security Policy** — Implemented headers
- **License Verification** — Server-side validation via Gumroad API

---

Thank you for helping keep DC Movies secure!
