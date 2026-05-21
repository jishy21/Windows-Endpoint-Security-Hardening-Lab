# Security Controls Used

## Overview
This document outlines the security controls implemented during the Windows Endpoint Security Hardening Lab.

---

# Access Control

## Least Privilege
Administrative access was separated from standard user access by creating dedicated security groups and non-admin user accounts.

### Actions Performed
- Created standard user accounts
- Created administrative security groups
- Restricted elevated permissions to approved accounts only

### Security Benefit
Reduces the risk of unauthorized system changes and privilege misuse.

---

# Authentication Security

## Password Complexity Policy
Configured Group Policy settings to enforce stronger passwords.

### Settings Applied
- Minimum password length: 12 characters
- Password complexity: Enabled
- Password history enforced
- Password expiration configured

### Security Benefit
Helps reduce weak password usage and credential-based attacks.

---

## Account Lockout Policy
Configured account lockout settings to mitigate brute-force login attempts.

### Settings Applied
- Lockout threshold: 5 failed attempts
- Lockout duration: 15 minutes
- Counter reset: 15 minutes

### Security Benefit
Limits repeated password guessing attempts.

---

# Endpoint Hardening

## Windows Defender Firewall
Configured firewall settings and created inbound blocking rules.

### Actions Performed
- Verified firewall profiles were enabled
- Blocked inbound SMB traffic on TCP port 445

### Security Benefit
Reduces unnecessary network exposure and attack surface.

---

## SMBv1 Mitigation
Disabled the SMBv1 protocol using PowerShell.

### Security Benefit
Mitigates risks associated with outdated file-sharing protocols and legacy vulnerabilities.

---

# Endpoint Protection

## Windows Defender
Verified real-time protection and endpoint security settings.

### Security Benefit
Provides malware protection and real-time monitoring.

---

# Logging and Monitoring

## Audit Policies
Enabled audit logging through Group Policy.

### Audit Categories Enabled
- Logon events
- Credential validation
- User account management
- Policy changes

### Security Benefit
Improves visibility into authentication events and security-related activity.

---

# Multi-Factor Authentication

## GitHub MFA
Enabled two-factor authentication on GitHub using an authenticator application.

### Security Benefit
Adds an additional authentication factor beyond passwords to help protect accounts from credential theft.
