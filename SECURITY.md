# Security Policy

## Reporting Security Vulnerabilities

We take the security of our project seriously. If you believe you have found a security vulnerability, please report it to us as described below.

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report them via email to: security@example.invalid

You should receive a response within 48 hours. If for some reason you do not, please follow up via email to ensure we received your original message.

Please include the following information in your report (as much as possible):

- Type of issue (e.g. buffer overflow, SQL injection, cross-site scripting, etc.)
- Full paths of source file(s) related to the manifestation of the issue
- The location of the affected source code (tag/branch/commit or direct URL)
- Any special configuration required to reproduce the issue
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if possible)
- Impact of the issue, including how an attacker might exploit the issue

This information will help us triage your report more quickly.

## Security Severity Classification

We use the following severity levels for security issues:

### Critical
- Remote code execution
- SQL injection leading to data exposure
- Authentication bypass
- Privilege escalation to admin/root

### High
- Cross-site scripting (XSS) that can be exploited
- Local file inclusion/directory traversal
- Sensitive data exposure
- Denial of service affecting availability

### Medium
- Cross-site request forgery (CSRF)
- Information disclosure (limited)
- Input validation issues

### Low
- Issues that require significant user interaction
- Theoretical attacks with minimal impact
- Configuration issues

## Supported Versions

Please ensure you are using a supported version of the project before reporting vulnerabilities.

| Version | Supported          |
| ------- | ------------------ |
| 1.x.x   | :white_check_mark: |
| < 1.0   | :x:                |

## Security Updates

Security updates will be released as soon as possible after a vulnerability is confirmed and a fix is available. Updates will be published:

1. As a new release on GitHub
2. Announced in release notes
3. Documented in this security policy if necessary

Thank you for helping keep our project secure!