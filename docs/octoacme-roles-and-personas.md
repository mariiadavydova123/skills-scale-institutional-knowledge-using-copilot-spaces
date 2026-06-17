# OctoAcme — Roles and Personas (Extended)

This document expands the personas and role definitions used across project management and delivery to clarify responsibilities and handoffs.

## Purpose
Expanding the personas and roles section will close gaps in accountability and clarify interactions between functional roles (PM, PdM, Developers, QA). Better definitions reduce handoff friction, speed decision-making, and improve risk ownership and escalations.

## How to use this doc
For each persona below you'll find:
- Responsibilities — a short bullet list of primary responsibilities.
- Interactions — who they typically coordinate with and when.

---

## Delivery Lead / Delivery Manager

Responsibilities:
- Coordinate sprint commitments and capacity planning across teams
- Track cross-team dependencies and removal of blockers
- Maintain a delivery-oriented timeline and risk register
- Facilitate standups, retro follow-ups, and delivery ceremonies

Interactions:
Works closely with the Project Manager for scheduling and risk communications, Product Manager for scope trade-offs, and Developers for capacity and impediments. Escalates persistent blockers to stakeholders.

---

## Technical Lead (Tech Lead)

Responsibilities:
- Lead or drive architecture and design decisions
- Ensure code quality through reviews and standards
- Mentor team engineers and guide technical direction
- Balance short-term delivery with long-term maintainability

Interactions:
Partners with Developers on design and code reviews, SRE/Infrastructure for operational considerations, and Product Manager to evaluate technical trade-offs and estimate effort.

---

## Release / Build Engineer

Responsibilities:
- Maintain CI/CD pipelines, release automation and deployment tooling
- Coordinate release windows and validate release readiness
- Own rollback procedures and release runbooks

Interactions:
Works with Developers and QA for release validation, Project Manager to schedule releases, and SRE for production rollout and post-deploy verification.

---

## Site Reliability Engineer (SRE) / Production Engineer

Responsibilities:
- Define and maintain runbooks and monitoring
- Own incident response procedures and post-incident reviews
- Improve system reliability and observability

Interactions:
Collaborates with Developers on instrumentation and observability, Release Engineer on deployment safety, and Project Manager for incident communications.

---

## UX Researcher / Designer Liaison

Responsibilities:
- Conduct lightweight research and usability testing
- Produce design artifacts and acceptance criteria
- Validate user assumptions and measure UX outcomes

Interactions:
Works with Product Manager to shape requirements, with Developers and QA to ensure acceptance criteria reflect user needs and edge cases.

---

## Business Analyst / Requirements Specialist

Responsibilities:
- Translate stakeholder requests into clear acceptance criteria
- Refine backlog items and document edge cases
- Help scope features and clarify non-functional requirements

Interactions:
Bridges Stakeholders and Product Manager; works with Developers and QA to ensure requirements are testable and well-defined.

---

## Data Analyst / Insights Owner

Responsibilities:
- Define metrics and success criteria
- Instrument features and build dashboards
- Analyze results and provide recommendations

Interactions:
Works with Product Manager to define success metrics, with Developers on instrumentation, and with Stakeholders on reporting and interpretation.

---

## Compliance / Security Reviewer

Responsibilities:
- Review features for regulatory, privacy, and security risks
- Sign off on required controls and compliance checklists
- Escalate compliance blockers and work with teams to remediate

Interactions:
Engages during planning and pre-release gates with Product Manager and SRE; coordinates with Security on complex issues.

---

## Support / Ops Liaison

Responsibilities:
- Ensure supportability and handover to operations/support teams
- Maintain runbooks and known-issue docs for support staff
- Provide feedback loops from support to engineering/product

Interactions:
Works with SRE and Release Engineer to ensure smooth support transitions and informs Product Manager of recurring issues that may require backlog attention.

---

## Acceptance Criteria for this update

- [x] Content aligns with existing process docs and naming conventions
- [x] Update improves clarity or closes a documented gap
- [ ] Proposed content has been reviewed with stakeholders (if needed)

---

### Notes
If you'd like I can split this into per-role files (e.g., docs/personas/<role>.md) or shorten it to be a one-page summary for quick reference. I can also add interaction diagrams or a RACI matrix if that would help.
