# IT Risk Assessment Matrix

**Document ID:** PROC-RISK-001  
**Version:** 1.0  
**Owner:** [CISO / IT Director]  
**Organization:** [NOME DA ORGANIZAÇÃO]  
**Last Review:** [DATA]

---

## Risk Scoring Methodology (5×5)

### Likelihood Scale

| Score | Level | Description |
|---|---|---|
| 5 | Almost Certain | Expected to occur in most circumstances (>80%) |
| 4 | Likely | Will probably occur in most circumstances (60–80%) |
| 3 | Possible | Might occur at some time (40–60%) |
| 2 | Unlikely | Could occur at some time (20–40%) |
| 1 | Rare | May occur only in exceptional circumstances (<20%) |

### Impact Scale

| Score | Level | Financial | Operational | Reputational | Regulatory |
|---|---|---|---|---|---|
| 5 | Critical | > R$ 1M | Full service outage | National media coverage | Regulatory action / fine |
| 4 | High | R$ 100K–1M | Major degradation | Sector-wide visibility | ANPD/regulator notification |
| 3 | Medium | R$ 10K–100K | Partial impact | Local/industry visibility | Compliance breach (internal) |
| 2 | Low | R$ 1K–10K | Minor disruption | Limited internal visibility | Minor procedural deviation |
| 1 | Negligible | < R$ 1K | No operational impact | No visibility | No regulatory implication |

### Risk Matrix

```
         │ IMPACT
         │  1-Neg  2-Low  3-Med  4-High  5-Crit
─────────┼────────────────────────────────────────
5-AlmCert│    5     10     15     20      25  🔴
4-Likely │    4      8     12     16      20  🔴
3-Possible│   3      6      9     12      15  🟡
2-Unlikely│   2      4      6      8      10  🟡
1-Rare   │   1      2      3      4       5  🟢
```

**Risk Levels:**
- 🔴 **Critical (15–25):** Immediate action required — escalate to C-level
- 🟡 **High (8–12):** Treatment plan within 30 days — IT Executive ownership
- 🟠 **Medium (4–6):** Treatment plan within 90 days — Manager ownership
- 🟢 **Low (1–3):** Accept or monitor — document decision

---

## Risk Register

| ID | Risk Description | Category | Threat Source | Vulnerability | L | I | Score | Level | Owner | Current Controls | Treatment | Residual Risk | Due Date | Status |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|
| RSK-001 | Ransomware attack encrypting critical systems | Cybersecurity | External threat actor | Unpatched systems / phishing | 4 | 5 | 20 | 🔴 Critical | CISO | EDR, backup, firewall | Implement MFA + security awareness + patch mgmt | Medium | [DATA] | In Progress |
| RSK-002 | LGPD personal data breach | Compliance / Legal | Internal / External | Inadequate access controls | 3 | 5 | 15 | 🔴 Critical | DPO / CISO | Data classification, DPA agreements | Implement DLP, complete ROPA, DPIA for high-risk ops | Medium | [DATA] | Planned |
| RSK-003 | Cloud cost overrun (FinOps) | Financial | Internal | Lack of cloud governance | 4 | 3 | 12 | 🟡 High | IT Director | Monthly cost review | Implement tagging policy + budget alerts + FinOps tooling | Low | [DATA] | Planned |
| RSK-004 | Key employee departure (knowledge loss) | People | Voluntary exit | Undocumented processes | 3 | 3 | 9 | 🟡 High | IT Director | Informal knowledge sharing | Document runbooks + cross-training program | Low | [DATA] | Planned |
| RSK-005 | Third-party vendor breach affecting our data | Supply Chain | External via vendor | Insufficient vendor assessment | 3 | 4 | 12 | 🟡 High | CISO | DPA, annual review | Implement vendor risk questionnaire + tiering | Medium | [DATA] | In Progress |
| RSK-006 | [ADD RISK] | | | | | | | | | | | | | |

**L** = Likelihood | **I** = Impact

---

## Risk Treatment Options

| Option | When to Apply |
|---|---|
| **Mitigate** | Implement controls to reduce likelihood or impact |
| **Transfer** | Insurance, outsourcing, contractual liability transfer |
| **Accept** | Risk score is acceptable; document rationale and review date |
| **Avoid** | Discontinue the activity that generates the risk |

---

## Review Schedule

| Risk Level | Review Frequency |
|---|---|
| Critical | Monthly |
| High | Quarterly |
| Medium | Semi-annually |
| Low | Annually |

---

## Revision History

| Version | Date | Author | Changes |
|---|---|---|---|
| 1.0 | [DATA] | [NOME] | Initial release |
