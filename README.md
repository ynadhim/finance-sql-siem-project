# finance-sql-siem-project

SOC-style lab demonstrating SQL Server auditing, least privilege, and Elastic SIEM detection in a simulated finance environment.

## Overview
This project simulates a finance database monitored by Elastic SIEM.  
It focuses on detecting unauthorized access attempts, credential usage, and suspicious activity against sensitive payroll data.

## Lab Architecture
- Windows Server 2022 (SQL Server)
- Ubuntu Server (Elastic Agent)
- Elastic Stack (SIEM, Alerts, Timelines, Cases)
- SQL Server Auditing enabled
- Least-privilege SQL users

## Key Scenarios Detected
- Unauthorized payroll access attempts
- Credential Manager access by non-privileged user
- Failed authentication attempts
- SQL-related security events correlated in Elastic

## Evidence
Screenshots included:
- Elastic Alerts
- Elastic Timelines
- Elastic Events
- Elastic Rules
- Elastic Cases
- Fleet / Agent status
- Ubuntu Elastic Agent health
- SQL audit activity

## Skills Demonstrated
- SQL Server auditing
- Least privilege access control
- SIEM alert analysis
- Timeline creation
- Incident-style investigation
- Log correlation
- Enabled SQL encryption (TLS)

## Future Improvements
- Implement key management / certificates
- Network segmentation (VLANs)
- IDS/IPS and firewall rules
