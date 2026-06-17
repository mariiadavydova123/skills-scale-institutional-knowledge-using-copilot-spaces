# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Delivery Lead / Delivery Manager

### Role Summary
Delivery Leads coordinate sprint commitments, capacity planning, and day-to-day delivery orchestration. They identify and resolve impediments to keep the team moving forward.

### Responsibilities
- Coordinate sprint commitments and capacity planning
- Manage cross-team dependencies and integration points
- Resolve day-to-day delivery impediments and blockers
- Track velocity and burndown metrics
- Facilitate daily standups and sprint ceremonies
- Escalate risks and dependencies to Project Manager

### Goals
- Keep the team focused and unblocked
- Maintain predictable velocity and delivery rhythm
- Ensure smooth handoffs across teams and milestones

### Interactions
Works closely with the **Project Manager** on schedules and risk escalation, the **Product Manager** on prioritization and scope changes, and **Developers** on capacity constraints and impediments. Coordinates with **QA** on testing readiness and with **Release Engineer** on deployment scheduling.

### Typical Communication
- Daily standups with delivery team
- Weekly capacity planning reviews
- Impediment tracking and escalation logs

---

## Technical Lead

### Role Summary
Technical Leads drive architecture decisions, code quality standards, and technical mentoring. They balance technical excellence with delivery velocity.

### Responsibilities
- Lead architecture and design decisions for the project
- Review design trade-offs and technical feasibility assessments
- Establish and enforce code quality standards
- Mentor developers and review code for quality and consistency
- Identify and mitigate technical risks
- Collaborate on performance and observability requirements

### Goals
- Deliver architecturally sound, maintainable solutions
- Build team technical capability through mentoring
- Reduce technical debt and rework

### Interactions
Partners closely with **Developers** on design reviews and code quality, with **SRE/Infrastructure** on operational and scalability considerations, and with **Product Manager** to evaluate technical trade-offs against business needs. Works with **Release Engineer** on deployment architecture.

### Typical Communication
- Design review meetings and RFC discussions
- Code review comments and mentoring sessions
- Technical documentation and architecture decisions

---

## Release / Build Engineer

### Role Summary
Release and Build Engineers own CI/CD pipelines, release automation, and deployment coordination. They ensure reliable, repeatable release processes.

### Responsibilities
- Maintain and enhance CI/CD pipelines
- Coordinate release planning and scheduling
- Manage release automation and rollback procedures
- Ensure pre-release validation (tests, security scans, smoke tests)
- Document release runbooks and procedures
- Support post-deployment verification

### Goals
- Enable fast, safe, and reliable deployments
- Reduce manual effort and human error in releases
- Provide clear visibility into release status and artifacts

### Interactions
Works with **Developers** and **QA** to validate release readiness, with **Project Manager** to schedule deployment windows, and with **SRE** for production rollout coordination and incident response. Collaborates with **Technical Lead** on deployment architecture.

### Typical Communication
- Release checklists and pre-deployment sign-offs
- Deployment logs and post-deployment reports
- Runbook documentation and process improvements

---

## Site Reliability Engineer (SRE) / Production Engineer

### Role Summary
SREs define operational standards, monitor production health, and own incident response. They bridge development and operations to ensure reliability and observability.

### Responsibilities
- Define runbooks and operational procedures
- Monitor production health and establish alerting
- Own incident response and on-call escalation
- Lead post-incident reviews and blameless retrospectives
- Collaborate on observability and logging requirements
- Define service level objectives (SLOs) and error budgets

### Goals
- Maintain high system reliability and availability
- Enable fast incident detection and response
- Continuously improve observability and operational maturity

### Interactions
Collaborates with **Developers** on instrumentation and observability, with **Release Engineer** on deployment coordination and runbook validation, and with **Project Manager** for incident communications and escalations. Works with **Technical Lead** on architectural reliability considerations.

### Typical Communication
- Incident response channels and on-call schedules
- Post-incident review notes and action items
- Observability and monitoring dashboards
- SLO and alerting threshold discussions

---

## UX Researcher / Designer Liaison

### Role Summary
UX Researchers validate usability assumptions and provide design artifacts that inform acceptance criteria and implementation decisions.

### Responsibilities
- Conduct lightweight user research and usability testing
- Create wireframes, prototypes, and design specifications
- Define user-centered acceptance criteria
- Validate solutions with target users before and after implementation
- Identify usability issues and accessibility requirements

### Goals
- Ensure solutions meet user needs and expectations
- Reduce rework from usability misalignment
- Improve customer satisfaction and adoption

### Interactions
Works closely with the **Product Manager** to shape requirements and user stories, and with **Developers** and **QA** to ensure acceptance criteria reflect user needs and design intent. Coordinates with **Accessibility Specialist** (if present) on inclusive design.

### Typical Communication
- Research findings and usability reports
- Design specifications and wireframes
- Acceptance criteria refinement sessions

---

## Business Analyst / Requirements Specialist

### Role Summary
Business Analysts translate stakeholder requests into clear, actionable acceptance criteria and backlog items. They reduce ambiguity and ensure scope clarity.

### Responsibilities
- Gather and analyze stakeholder requirements
- Translate business needs into acceptance criteria and user stories
- Refine backlog items and clarify scope
- Document edge cases and business rules
- Validate requirements with stakeholders before handoff to development

### Goals
- Reduce scope creep and rework through clarity
- Speed development by eliminating requirement ambiguity
- Improve stakeholder satisfaction through better understanding

### Interactions
Bridges **Stakeholders** and the **Product Manager** to capture and prioritize requirements. Works with **Developers** and **QA** on clarifying scope, acceptance criteria, and edge cases. Collaborates with **UX Researcher** on requirement validation.

### Typical Communication
- Requirement elicitation notes and requirement documents
- Acceptance criteria reviews and refinement sessions
- Stakeholder communication summaries

---

## Data Analyst / Insights Owner

### Role Summary
Data Analysts define success metrics, instrument features for measurement, and analyze results to inform post-launch decisions.

### Responsibilities
- Define key success metrics and KPIs for the project
- Work with developers on instrumentation and event tracking
- Analyze results and create dashboards for stakeholders
- Identify trends, anomalies, and optimization opportunities
- Support A/B testing and feature validation

### Goals
- Enable data-driven decision-making post-launch
- Maximize the impact of delivered features
- Identify optimization and iteration opportunities

### Interactions
Works closely with the **Product Manager** to define success metrics and validate outcomes, with **Developers** on instrumentation implementation, and with **Stakeholders** on metrics reporting and dashboards. Collaborates with **SRE** on operational metrics and health signals.

### Typical Communication
- Metrics definition workshops and success criteria alignment
- Dashboard and reporting summaries
- Post-launch analysis and insights reports

---

## Compliance / Security Reviewer

### Role Summary
Compliance and Security Reviewers assess regulatory, privacy, and security risks. They ensure solutions meet compliance requirements and organizational security standards.

### Responsibilities
- Review requirements for regulatory and privacy implications
- Assess security architecture and controls
- Approve or flag features for compliance risk
- Define security acceptance criteria
- Sign off on releases that meet security and compliance standards

### Goals
- Prevent compliance and security incidents
- Ensure solutions meet regulatory requirements
- Build security into the development process

### Interactions
Engages during planning and pre-release gates with the **Product Manager** and **Technical Lead** to review architecture and controls. Works with **SRE** on operational security and incident response. Escalates issues to Security on-call for critical findings. Collaborates with **Business Analyst** on compliance-related requirements.

### Typical Communication
- Security and compliance review checklists
- Risk assessment and mitigation plans
- Pre-release security sign-off

---

## Support / Ops Liaison

### Role Summary
Support and Ops Liaisons provide input on supportability, documentation, and operational handover. They ensure smooth transitions from development to support teams.

### Responsibilities
- Provide input on feature supportability and documentation needs
- Define support runbooks and troubleshooting guides
- Ensure knowledge transfer to support and operations teams
- Identify recurring support issues and escalation paths
- Support early rollout and support team readiness

### Goals
- Reduce support burden and customer issues
- Accelerate support team time-to-resolution
- Improve customer experience post-launch

### Interactions
Works with **SRE** and **Release Engineer** to ensure smooth support transitions and operational readiness. Collaborates with **Product Manager** to understand feature capabilities and limitations. Informs **Developers** of recurring issues and improvement opportunities. Coordinates with **Project Manager** on support team readiness planning.

### Typical Communication
- Support runbooks and troubleshooting guides
- Support readiness reviews and training plans
- Feedback loops on recurring support issues

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Interactions" sections to understand cross-functional dependencies and communication needs.
