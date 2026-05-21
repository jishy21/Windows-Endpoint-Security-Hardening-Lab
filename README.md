# Windows Endpoint Security Hardening Lab

## Overview
This lab demonstrates hands-on practice with core Security+ concepts including least privilege, secure authentication, endpoint hardening, firewall configuration, account lockout policies, audit logging, and basic vulnerability mitigation.

The lab was completed using a Windows Server Active Directory environment and a Windows client workstation. Security controls were applied through Group Policy, Windows Defender Firewall, PowerShell, and Windows Security settings.

## Objectives
- Enforce least privilege access
- Configure password and account lockout policies
- Harden endpoint firewall settings
- Disable outdated services and protocols
- Verify endpoint protection status
- Enable basic audit logging
- Demonstrate MFA usage on an important account
- Document work using ticket-style reports

## Technologies Used
- Windows Server 2022
- Windows 10/11
- Active Directory Domain Services
- Group Policy Management
- Windows Defender Firewall
- Windows Security
- PowerShell
- Event Viewer
- GitHub MFA

## Skills Practiced
- Endpoint hardening
- Identity and access management
- Least privilege access
- Password policy enforcement
- Account lockout configuration
- Firewall rule creation
- Vulnerability mitigation
- Audit logging
- Security documentation
- Basic threat surface reduction

## Lab Tasks Completed

### 1. Least Privilege Access
Created standard user and help desk admin accounts. Administrative access was separated from normal user access using security groups.

### 2. Password and Lockout Policy
Configured Group Policy settings for password complexity, password length, password history, and account lockout protection.

### 3. Firewall Hardening
Verified Windows Defender Firewall settings and created an inbound rule to block unnecessary network traffic.

### 4. SMBv1 Mitigation
Used PowerShell to check and disable SMBv1, reducing exposure to outdated protocol vulnerabilities.

### 5. Endpoint Protection
Verified Windows Defender protection settings and confirmed endpoint security features were enabled.

### 6. Audit Logging
Enabled audit policies for logon events, credential validation, account management, and policy changes.

### 7. MFA Enforcement
Enabled multi-factor authentication on GitHub to demonstrate secure authentication practices.

## Security Concepts Demonstrated
- Least privilege
- Defense in depth
- Multi-factor authentication
- Account lockout protection
- Endpoint hardening
- Attack surface reduction
- Vulnerability mitigation
- Logging and monitoring

## Documentation
Ticket-style documentation was created for each task to simulate real-world IT/security support work.

## Result
This lab demonstrates practical entry-level security and endpoint support skills aligned with CompTIA Security+ concepts and real-world help desk/security technician responsibilities.
