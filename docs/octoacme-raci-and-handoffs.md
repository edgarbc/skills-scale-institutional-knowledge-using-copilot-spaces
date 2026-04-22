# OctoAcme — Cross-Functional RACI and Hand-offs

Use this lightweight matrix to clarify ownership and consultation points by lifecycle stage.

## Legend
- **R** = Responsible (does the work)
- **A** = Accountable (final decision/ownership)
- **C** = Consulted (provides input)
- **I** = Informed (kept up to date)

## Lifecycle RACI Matrix

| Stage | PM | PdM | Developers | QA/Testing | UX Designer | Data Analyst | Customer Success Manager | Stakeholders/Sponsor | Key deliverables |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Initiation | A/R | R | C | I | C | C | C | C/I | One-pager, initial scope, success metrics, stakeholder map |
| Planning | A | A/R | R | C | R/C | C | C | I | Prioritized backlog, release milestones, ownership map, dependency plan |
| Execution | A | A/C | R | R | C | C/R | C | I | Implemented increments, test evidence, design reviews, metric check-ins |
| Release | A/R | A/C | R | R | C | R/C | R/C | C/I | Release checklist, go/no-go notes, dashboard baseline, customer readiness update |
| Retrospective | A/R | R | C | C | C | R | R/C | I | Retro notes, action items, metric outcomes, feedback summary |

## Hand-off expectations by stage
- **Initiation:** PdM shares problem statement + metrics draft; UX/Data/CSM provide early constraints and signals.
- **Planning:** ownership for each backlog item includes design, build, test, metric validation, and communication responsibilities.
- **Execution:** cross-functional reviews run on a regular cadence (design, quality, and metrics), with open decisions captured in the decision log.
- **Release:** QA validates quality gates, Data Analyst verifies baseline reporting, CSM confirms customer communication/readiness.
- **Retrospective:** metric outcomes and customer feedback are reviewed alongside delivery performance to prioritize improvements.
