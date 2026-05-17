# Botium Toys: Security Audit

## Controls Assessment

| Control | In Place | Explanation |
|---------|----------|-------------|
| Least Privilege | No | All employees have access to all data; needs to be limited |
| Disaster recovery plans | No | No plans in place; needed for business continuity |
| Password policies | No | Policy exists but is weak and not enforced properly |
| Separation of duties | No | Not implemented; increases risk of insider threats |
| Firewall | Yes | Firewall is active with defined security rules |
| IDS | No | No IDS installed; cannot detect intrusions |
| Backups | No | No backups of critical data exist |
| Antivirus software | Yes | Installed and monitored regularly |
| Manual monitoring for legacy systems | No | Monitored but no regular schedule or clear procedures |
| Encryption | No | No encryption used for sensitive customer data |
| Password management system | No | No centralized system; affects productivity |
| Locks | Yes | Physical locations have sufficient locks |
| CCTV | Yes | Up-to-date CCTV surveillance in place |
| Fire detection/prevention | Yes | Fire alarm and sprinkler systems in place |

## Compliance Checklist

### PCI DSS
| Best Practice | Adherence | Explanation |
|--------------|-----------|-------------|
| Authorized access to credit card info | No | All employees can access internal data including card info |
| Secure storage of credit card data | No | No encryption used for stored card data |
| Data encryption implemented | No | Encryption not currently in use |
| Secure password management | No | No centralized password management system |

### GDPR
| Best Practice | Adherence | Explanation |
|--------------|-----------|-------------|
| E.U. data kept private | No | No encryption or access controls for E.U. customer data |
| 72-hour breach notification plan | Yes | Plan exists to notify E.U. customers within 72 hours |
| Data classified and inventoried | No | Data has not been properly classified |
| Privacy policies enforced | Yes | Privacy policies documented among IT staff |

### SOC
| Best Practice | Adherence | Explanation |
|--------------|-----------|-------------|
| User access policies established | No | No least privilege controls in place |
| Sensitive data confidential | No | PII/SPII accessible to all employees |
| Data integrity validated | Yes | IT ensures data integrity controls are in place |
| Data available to authorized users only | No | Access is not restricted to authorized users |
