# Algorithmic Governance Standards (v0.1 Draft)

Framework for deploying, auditing, and governing algorithmic / AI systems used in civic processes.

## 1. Scope
Applies to any automated system affecting proposal visibility, identity verification, evidence summarization, policy simulation, deliberation moderation, or impact assessments.

## 2. Core Principles
1. Transparency First: Public awareness precedes deployment.
2. Explainability: Users must access plain-language model summaries.
3. Accountability: A named Responsible Officer for each system.
4. Proportionality: Oversight intensity matches system risk level.
5. Contestability: Affected parties can challenge outputs.
6. Privacy & Data Minimization: No unnecessary personal data retention.

## 3. System Classification (Risk Tiers)
| Tier | Description | Examples | Oversight Level |
|------|-------------|----------|-----------------|
| 0 | Assistive, no user impact | Formatting tools | Basic disclosure |
| 1 | Informational influence | Evidence summarizers | Transparency + periodic audit |
| 2 | Decision support | Policy simulators | Formal Algorithmic Impact Assessment |
| 3 | High-stakes filtering | Identity verification risk flags | Pre-deployment external audit |
| 4 | Rights-adjacent or allocation | Automated moderation escalation | Continuous monitoring + realtime logging |

## 4. Algorithmic Impact Assessment (AIA) Template
- Purpose & Function
- Data Inputs & Provenance
- Model Architecture & Assumptions
- Performance Metrics (by subgroup)
- Fairness & Bias Tests (metrics justified)
- Explainability Mechanism (user-level)
- Security & Abuse Surfaces
- Human Oversight Points
- Failure Modes & Fallback Plan
- Data Retention & Deletion Policy
- Change Management Procedure

## 5. Mandatory Disclosures
| Element | Public? | Notes |
|---------|--------|-------|
| System Name & Version | ✅ | Versioned semantic tags |
| Purpose Statement | ✅ | Plain language |
| Training Data Categories | ✅ (aggregate) | No raw PII exposure |
| Performance Summary | ✅ | Include subgroup stats |
| Known Limitations | ✅ | Linked to mitigation plan |
| Audit History | ✅ | Timestamped logs |
| Responsible Officer | ✅ | Contact channel |
| Source Code | ✅ (Tier ≥2) | Licensed open-source unless security exception |

## 6. Audit Cadence
| Tier | Internal Review | External Audit | Live Monitoring |
|------|-----------------|---------------|-----------------|
| 0 | Annual | N/A | None |
| 1 | Annual | Biennial sample | Basic logging |
| 2 | Semi-annual | Biennial | Drift detection |
| 3 | Quarterly | Annual | Real-time anomaly alerts |
| 4 | Quarterly | Annual (independent) | Real-time + public dashboard |

## 7. Fairness & Performance Metrics (Illustrative)
- Disparate Impact Ratio
- False Positive / Negative Rates by Demographic Cohort
- Calibration Error
- Explanatory Coverage (% of outputs with user-friendly rationale)
- Latency Thresholds under load

## 8. Change Management
- Version bump required for any model parameter change impacting outputs.
- Public changelog: nature of change, expected impact, rollback plan.
- Emergency patch allowed (security) → retroactive disclosure within 72 hours.

## 9. Incident Response
| Event | Response Time | Escalation |
|-------|---------------|------------|
| Data Leak | Immediate containment | Notify DDRA + public summary 7 days |
| Bias Threshold Breach | 14 days mitigation plan | External audit trigger |
| System Abuse (gaming) | 7 days adjustment | Publish countermeasures summary |

## 10. User Rights
- Right to Explanation (meaningful rationale for impactful outputs)
- Right to Contest (human review request channel)
- Right to Data Minimization (opt-out from non-essential personalization)

## 11. External Participation
- Civic technologist sandbox with synthetic data.
- Bug bounty + bias bounty programs.

## 12. Decommissioning
- Archival snapshot (docs + code + model card)
- Data deletion verification
- Post-mortem public report (lessons learned)

---
*Status: Draft v0.1 — Future additions: standardized model card schema & cryptographic transparency proofs.*
