# 03 - NIST CSF Gap Analysis

## Identify (ID)
- **Current State:** Basic asset inventory is maintained in a spreadsheet.
- **Gap:** No formal data classification policy.
- **Recommendation:** Develop and implement a formal Data Classification Policy.

## Protect (PR)
- **Current State:** RBAC is partially implemented in Active Directory.
- **Gap:** No periodic access reviews; no MFA on admin accounts.
- **Recommendation:** Implement quarterly access reviews and enforce MFA for privileged users.

## Detect (DE)
- **Current State:** Basic logging on domain controllers.
- **Gap:** No centralized SIEM or alerting for anomalous behavior.
- **Recommendation:** Deploy a SIEM solution and configure alerts for failed logins.

## Respond (RS)
- **Current State:** Ad-hoc incident response.
- **Gap:** No formal Incident Response Plan (IRP).
- **Recommendation:** Draft and test an Incident Response Plan.

## Recover (RC)
- **Current State:** Nightly backups of the EHR database.
- **Gap:** Backups are not encrypted and recovery has never been tested.
- **Recommendation:** Encrypt backups and conduct quarterly recovery drills.
