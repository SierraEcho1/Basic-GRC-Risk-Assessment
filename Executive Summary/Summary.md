# Executive Summary

## Overview
A risk assessment was conducted for the Northstar Medical Group Active Directory and EHR environment. The assessment identified 5 key risks and evaluated the organization's maturity against the NIST Cybersecurity Framework.

## Top Risks Identified
1. **No MFA on Admin Accounts (Score: 20):** Critical risk of credential theft leading to full domain compromise.
2. **No VPN for Remote Access (Score: 16):** Exposure of internal systems to the public internet.
3. **Over-Provisioned EHR Access (Score: 15):** Excessive user permissions increase the risk of unauthorized PHI access.
4. **Delayed Offboarding (Score: 12):** Former employees may retain access to sensitive systems.
5. **Unencrypted Backups (Score: 10):** Risk of data exposure if physical backup media is stolen.

## Recommendations
1. Enforce MFA on all privileged accounts immediately.
2. Require VPN for all remote access.
3. Implement quarterly access reviews.
4. Automate the employee offboarding process.
5. Enable encryption on all database backups.

## Overall Risk Posture
**Moderate** — Several high-severity risks exist that require immediate remediation to achieve compliance with HIPAA and NIST CSF standards.
