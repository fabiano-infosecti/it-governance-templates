# Information Security Policy

**Document ID:** POL-SEC-001
**Version:** 1.0
**Classification:** Public / Internal
**Owner:** [CARGO DO RESPONSÁVEL — ex: CISO / IT Director]
**Last Review:** [DATA]
**Next Review:** [DATA + 1 ANO]
**Approved by:** [NOME / CARGO]

---

## 1. Purpose

This policy establishes the principles, responsibilities and minimum requirements for information security management at **[NOME DA ORGANIZAÇÃO]**, ensuring the confidentiality, integrity and availability of information assets in alignment with ISO/IEC 27001:2022, LGPD (Lei 13.709/2018) and applicable regulations.

---

## 2. Scope

This policy applies to:

- All employees (permanent, temporary, contractors and interns)
- Third-party service providers and partners with access to organizational systems or data
- All information assets: systems, databases, devices, networks, cloud environments and physical records

---

## 3. Definitions

| Term | Definition |
|---|---|
| Information Asset | Any data, system, device or process with value to the organization |
| Confidentiality | Ensuring information is accessible only to authorized parties |
| Integrity | Safeguarding accuracy and completeness of information |
| Availability | Ensuring authorized users have access when needed |
| Incident | Any event that compromises security of an information asset |
| DPO | Data Protection Officer — responsible for LGPD compliance |

---

## 4. Principles

All employees and contractors must adhere to the following principles:

1. **Need to know** — access to information is granted based on job function and minimum necessary
2. **Defense in depth** — multiple security controls are applied in layers
3. **Accountability** — all access and actions on critical systems are logged and auditable
4. **Privacy by design** — data protection is embedded in processes and systems from inception
5. **Continuous improvement** — security controls are regularly reviewed and improved

---

## 5. Responsibilities

### 5.1 Senior Leadership / Board
- Approve this policy and allocate adequate resources for implementation
- Demonstrate commitment to information security culture

### 5.2 IT Executive / CISO
- Maintain and review this policy annually
- Report security metrics to leadership
- Oversee the Information Security Management System (ISMS)

### 5.3 IT Team
- Implement and operate technical controls
- Respond to security incidents
- Maintain system configurations and patch levels

### 5.4 All Employees
- Complete mandatory security awareness training
- Report suspected incidents or vulnerabilities immediately
- Comply with all security policies and procedures
- Protect credentials and devices under their responsibility

### 5.5 Data Protection Officer (DPO)
- Advise on LGPD compliance obligations
- Manage data subject rights requests
- Liaise with ANPD when required

---

## 6. Policy Requirements

### 6.1 Access Control
- Access is granted based on the principle of least privilege
- Privileged accounts must be reviewed quarterly
- MFA (Multi-Factor Authentication) is mandatory for all critical systems and remote access
- Access must be revoked within **24 hours** of employee termination

### 6.2 Password Management
- Minimum length: 12 characters
- Complexity: uppercase, lowercase, numbers and special characters
- Password reuse: last 10 passwords prohibited
- Privileged accounts: rotation every 90 days
- Use of approved password managers is encouraged

### 6.3 Data Classification
| Level | Description | Examples |
|---|---|---|
| Public | Intentionally available externally | Website, marketing materials |
| Internal | General internal use | Policies, procedures, internal communications |
| Confidential | Business-sensitive information | Financial data, contracts, HR records |
| Restricted | Highest sensitivity — limited distribution | Personal data (LGPD), credentials, IP |

### 6.4 Incident Management
- All security incidents must be reported to [CANAL DE REPORTE — ex: security@empresa.com]
- Critical incidents require notification within **1 hour**
- Personal data breaches must be evaluated for LGPD reporting obligations (ANPD — 72 hours)
- Post-Incident Reviews (PIR) are mandatory for critical and high-severity incidents

### 6.5 Third-Party Management
- All vendors with access to organizational data must sign a Data Processing Agreement (DPA)
- Vendor security posture must be assessed before contract signature
- Annual review of active third-party access

### 6.6 Physical Security
- Clean desk policy applies to all office environments
- Sensitive documents must not be left unattended
- Visitor access to IT infrastructure areas requires authorization and escort

### 6.7 Cryptography
- Data in transit: TLS 1.2 minimum (TLS 1.3 preferred)
- Data at rest: AES-256 minimum for confidential and restricted data
- Cryptographic keys must be managed in approved key management systems

---

## 7. Compliance and Enforcement

Non-compliance with this policy may result in:
- Disciplinary action up to and including termination
- Legal liability under LGPD, GDPR or other applicable regulations
- Notification to relevant regulatory authorities

---

## 8. Related Documents

- Access Control Policy (POL-ACC-001)
- Incident Response Policy (POL-INC-001)
- LGPD Privacy Program (LGPD-PROG-001)
- Acceptable Use Policy (POL-USE-001)
- Risk Management Procedure (PROC-RISK-001)

---

## 9. Review History

| Version | Date | Author | Change Description |
|---|---|---|---|
| 1.0 | [DATA] | [NOME] | Initial release |

---

*This document is reviewed annually or after significant changes to the regulatory environment, organizational structure, or threat landscape.*
