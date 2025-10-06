# Policy Lifecycle (v0.1 Draft)

A canonical state machine for proposals in the Generational Republic. Each state has entry criteria, mandatory artifacts, and exit conditions.

## Overview Diagram (Conceptual)

Draft → Endorsement Threshold → Classification → Parallel Reviews (Evidence / Rights / Future) → Consolidated Dossier → Citizen Deliberation → Ballot Formation → Vote → Implementation → Monitoring → Scheduled Reassessment

## 1. Draft
- Actor: Any citizen or authorized working group.
- Required: Proposal Template completion.
- Quality Gate: Minimum completeness heuristic (problem, rationale, preliminary references).

## 2. Endorsement Threshold
- Mechanism: Verified digital signatures (anti-fraud safeguards).
- Parameter: 2–5% (see `GOVERNANCE_PARAMETERS.md`).
- Outcome: Moves to classification queue.

## 3. Classification
- Triage Panel: Assigns category (Minor / Standard / Major Impact / Rights-Sensitive / High-Risk Future).
- Rules: Major Impact triggers full RIA + FIA; Minor may bypass certain layers but not rights safeguards.

## 4. Parallel Reviews
### 4a. Evidence Brief (SIC)
- Inputs: Proposal + cited references + external submissions.
- Output: Evidence Brief + Evidence Score.

### 4b. Rights Impact Assessment (RIA)
- Actors: Proponent + Rights Chamber facilitation + EPC advisory.
- Output: RIA Report (impacts, mitigations, strict scrutiny analysis if applicable).

### 4c. Future Impact Assessment (FIA)
- Actors: Futures Institute + CoG.
- Output: FIA + draft Future Impact Report (FIR).

## 5. Consolidated Dossier
- Aggregates: Proposal vCurrent, Evidence Brief, RIA, FIR, Mitigation Plans, Advisory Objections.
- Public Comment Window: 15–30 days (structured feedback form; spam filtering).

## 6. Citizen Deliberation
- Citizen Jury: Reviews dossier, interrogates experts, issues Recommendations Report.
- Optional Panels: Citizen–Scientist Panels for technical disputes.

## 7. Ballot Formation
- Variant Curation: Up to N alternative implementations (ranked-choice ready) + status flags.
- Mandatory Inclusions: Scientific Objection (if any), Rights Risks summary, Future Mitigation notes.

## 8. Vote
- Participation Gate: Evidence Interaction Module (non-punitive; ensures brief exposure).
- Method: Ranked or quadratic (see parameters).
- Turnout & demographic monitoring for equity.

## 9. Implementation
- Executive Council drafts Implementation Plan (KPIs, timeline, responsible agencies).
- Conditional Approvals enforced (must satisfy preconditions before activation).

## 10. Monitoring
- Dashboards: Publish KPI performance + rights & future risk indicators.
- Feedback Loop: Citizen issue reporting integrated.

## 11. Scheduled Reassessment
- Trigger: Sunset date or adaptive threshold breach.
- Pathways: Renewal (with updated assessments), Amendment, Sunset / Decommission.

## Escalation & Intervention Points
- Scientific Objection: Display-only, escalates if repeated across cycles.
- Rights Emergency Pause: CRC injunction pre-implementation or mid-course.
- Generational Veto: Blocks prior to Ballot Formation unless overridden.

## Data & Transparency Norms
- All artifacts public by default (exceptions: privacy-sensitive datasets → anonymized release).
- Machine-readable formats for external analysis.

## Metrics (Suggested Baselines)
- Median time Draft → Vote by category.
- % Proposals receiving full tri-layer review.
- % Mitigation Plans fully satisfied pre-implementation.
- Reassessment Compliance Rate.

---
*Iterate via PRs: add sequence diagram, formal state table, and risk classification taxonomy in future versions.*
