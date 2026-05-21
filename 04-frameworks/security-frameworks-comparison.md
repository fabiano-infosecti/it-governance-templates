# Security Frameworks Comparison
## ISO 27001:2022 × NIST CSF 2.0 × CIS Controls v8

**Document ID:** FWK-COMP-001  
**Version:** 1.0  
**Owner:** [CISO / IT Director]  
**Last Review:** [DATA]

---

## Quick Reference: Framework Purpose

| Framework | Origin | Primary Focus | Best For |
|---|---|---|---|
| **ISO/IEC 27001:2022** | ISO / IEC (International) | ISMS — Information Security Management System | Certification, contractual requirement, enterprise governance |
| **NIST CSF 2.0** | NIST (USA) | Risk-based cybersecurity framework | Risk management, sector flexibility, US-regulated industries |
| **CIS Controls v8** | CIS (USA) | Prioritized technical security controls | Practical implementation, SMB to Enterprise, quick wins |
| **LGPD** | Brazil | Personal data protection and privacy | Brazilian regulatory compliance |

---

## Structural Comparison

### ISO 27001:2022 — Annex A Controls (93 controls, 4 themes)

| Theme | Controls | Examples |
|---|---|---|
| Organizational (37) | Policies, roles, threat intelligence, supplier security | Information security policy, roles & responsibilities |
| People (8) | Awareness, training, remote work, confidentiality | Security awareness, screening, disciplinary process |
| Physical (14) | Physical perimeter, clean desk, equipment security | Physical security perimeters, equipment maintenance |
| Technological (34) | Authentication, encryption, monitoring, SIEM, DLP | Access control, malware protection, backup, logging |

### NIST CSF 2.0 — 6 Functions

| Function | Goal | Key Categories |
|---|---|---|
| **Govern (GV)** | Establish cybersecurity risk strategy | Org context, risk management strategy, roles |
| **Identify (ID)** | Understand assets, risks and environment | Asset management, risk assessment, improvement |
| **Protect (PR)** | Implement safeguards | IAM, awareness, data security, platform security |
| **Detect (DE)** | Find cybersecurity events | Monitoring, adverse event analysis |
| **Respond (RS)** | Act on detected events | Incident management, analysis, communication |
| **Recover (RC)** | Restore capabilities | Incident recovery, communication |

### CIS Controls v8 — 18 Controls (3 Implementation Groups)

| IG | Target | Controls |
|---|---|---|
| IG1 | Small org / basic hygiene | Controls 1–6 (inventory, config, data, access, accounts, audit logs) |
| IG2 | Medium org | IG1 + Controls 7–11 (email, browser, malware, recovery, network) |
| IG3 | Large / high-risk org | All 18 controls (pen testing, incident response, app security) |

---

## Cross-Framework Mapping (Key Domains)

| Security Domain | ISO 27001 (Annex A) | NIST CSF 2.0 | CIS Controls v8 |
|---|---|---|---|
| Asset Management | A.5.9, A.5.10 | ID.AM | CIS 1, CIS 2 |
| Access Control / IAM | A.8.2, A.8.3, A.5.15–18 | PR.AA | CIS 5, CIS 6 |
| Data Protection | A.5.33, A.8.11, A.8.12 | PR.DS | CIS 3 |
| Security Awareness | A.6.3 | PR.AT | CIS 14 |
| Vulnerability Management | A.8.8 | ID.RA, PR.PS | CIS 7 |
| Incident Management | A.5.24–28 | DE, RS | CIS 17 |
| Network Security | A.8.20–22 | PR.IR | CIS 12, CIS 13 |
| Cryptography | A.8.24 | PR.DS | CIS 3 |
| Supplier / Third-party | A.5.19–22 | GV.SC | CIS 15 |
| Logging & Monitoring | A.8.15–17 | DE.CM | CIS 8 |
| Backup & Recovery | A.8.13 | RC.RP | CIS 11 |
| Application Security | A.8.25–31 | PR.PS | CIS 16 |

---

## Implementation Guidance

### Which framework to lead with?

```
Are you seeking formal certification?
  └─ YES → Lead with ISO 27001
  └─ NO  → Continue...

Are you in a US-regulated industry or working with US partners?
  └─ YES → Lead with NIST CSF
  └─ NO  → Continue...

Do you need quick, prioritized technical controls?
  └─ YES → Lead with CIS Controls (start at IG1)

Do you handle Brazilian personal data?
  └─ ALWAYS complement with LGPD compliance program
```

### Recommended layered approach for Brazilian enterprises

1. **Foundation:** CIS Controls IG1 (immediate technical hygiene)
2. **Governance:** ISO 27001 Annex A (policy and management structure)
3. **Risk Framework:** NIST CSF (risk-based communication with leadership)
4. **Compliance:** LGPD program (mandatory for Brazilian operations)

---

## Maturity Self-Assessment

Rate your organization 1–5 for each domain:

| Domain | Current Maturity (1–5) | Target Maturity | Gap | Priority |
|---|---|---|---|---|
| Asset Inventory | | | | |
| Access Control / MFA | | | | |
| Patch Management | | | | |
| Security Awareness | | | | |
| Incident Response | | | | |
| Data Protection / LGPD | | | | |
| Third-party Risk | | | | |
| Logging & Monitoring | | | | |
| Backup & Recovery | | | | |
| Application Security | | | | |

**Maturity Scale:**
- 1 — Initial (ad hoc, no formal process)
- 2 — Developing (some practices, not consistent)
- 3 — Defined (documented, consistently applied)
- 4 — Managed (measured, metrics-driven)
- 5 — Optimizing (continuous improvement, benchmarked)

---

## References

- [ISO/IEC 27001:2022](https://www.iso.org/standard/27001)
- [NIST Cybersecurity Framework 2.0](https://www.nist.gov/cyberframework)
- [CIS Controls v8](https://www.cisecurity.org/controls)
- [LGPD — Lei 13.709/2018](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm)
- [ANPD — Autoridade Nacional de Proteção de Dados](https://www.gov.br/anpd)
