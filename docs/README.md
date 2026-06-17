# OctoAcme Project Management Docs

This folder collects OctoAcme's program and delivery process documents. The goal is to make project management guidance easy to discover and use so teams run projects consistently, reduce onboarding friction, and keep a single source of truth for roles, cadence, artifacts, and how we handle risks and releases.

Links
- Project Management Overview — docs/octoacme-project-management-overview.md
- Project Initiation Guide — docs/octoacme-project-initiation.md
- Project Planning — docs/octoacme-project-planning.md
- Execution & Tracking — docs/octoacme-execution-and-tracking.md
- Risks & Communication — docs/octoacme-risks-and-communication.md
- Release & Deployment — docs/octoacme-release-and-deployment.md
- Retrospective & Continuous Improvement — docs/octoacme-retrospective-and-continuous-improvement.md
- Roles & Personas — docs/octoacme-roles-and-personas.md

Brief overview of OctoAcme project management processes
- Customer-first, iterative delivery: We prioritize customer value and deliver in small, testable increments rather than large, risky releases.
- Clear ownership and roles: Each project has a named Project Manager (PM) and Product Lead who coordinate scope, priorities, and stakeholder communication.
- Lightweight initiation and planning: Start with a project one-pager (problem, goal, success metrics) and confirm stakeholders before moving into planning.
- Timeboxed execution: Use sprints/iterations, pull items with clear acceptance criteria, and keep PRs small to reduce review friction.
- Definition of Done & quality gates: Every backlog item should have acceptance criteria; CI, tests, and security scans must pass before merge.
- Risk-first communication: Maintain a risk register, surface blockers in standups, and escalate per the defined paths when necessary.
- Release discipline & rollback readiness: Prepare release notes, smoke tests, and rollback plans for production releases.
- Continuous improvement: Run retrospectives after milestones and track action items to closure.

When and how to use each document
- octoacme-project-management-overview.md — Quick intro for new team members: roles, lifecycle, cadence, and core artifacts.
- octoacme-project-initiation.md — Use when validating new project ideas; fill the project one-pager and confirm go/no-go.
- octoacme-project-planning.md — Use when moving into planning: backlog, estimates, DoD, and release milestones.
- octoacme-execution-and-tracking.md — Daily/weekly execution guidance: standups, PR workflow, CI expectations, and reporting.
- octoacme-risks-and-communication.md — Maintain and communicate the Risk Register and stakeholder updates.
- octoacme-release-and-deployment.md — Follow for pre-release checks, deployment steps, and rollback playbooks.
- octoacme-retrospective-and-continuous-improvement.md — Run retrospectives and convert action items into backlog issues.
- octoacme-roles-and-personas.md — Reference role responsibilities and typical communication patterns.

How to contribute updates
- Use the "Add Content to Project Management Process Docs" issue template in .github/ISSUE_TEMPLATE/ to propose changes.
- Link proposed changes to an issue, and include rationale and acceptance criteria.
- Small doc updates can follow a normal PR review; larger process changes should be reviewed with affected stakeholders.

Contact / questions
- For process questions or suggested changes, open an issue using the process-doc update template or ping the Project Manager listed on the project one-pager.
