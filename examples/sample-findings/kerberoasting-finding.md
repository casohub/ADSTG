# Example: Kerberoasting Finding

**Severity:** High

## Description

Multiple service accounts vulnerable to Kerberoasting were identified.

## Affected Accounts

- svc_sql
- svc_web
- svc_app

## Proof of Concept

```powershell
Invoke-Kerberoast -OutputFormat Hashcat
```

## Remediation

1. Implement 25+ character passwords for all service accounts
2. Use Group Managed Service Accounts (gMSA)
3. Monitor for TGS requests
