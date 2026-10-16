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

## QA / Testing

### Role Summary
QA/Testing validates quality and acceptance criteria across feature deliveries and releases.

### Responsibilities
- Define and execute test plans and cases
- Validate acceptance criteria and non-functional requirements
- Report and triage defects with developers
- Perform smoke and regression checks during releases

### Typical Communication
- Test results in PRs and release notes
- Coordination with Developers and Release Manager

---

## New / Expanded Personas (proposed additions)

### Technical Lead / Engineering Lead
Role Summary:
- Senior engineering role focused on technical strategy and high-impact architecture decisions.

Responsibilities:
- Own technical architecture decisions and design patterns
- Prioritize and manage technical debt and refactors
- Review and approve large technical designs and cross-team integrations
- Mentor engineers and guide code quality initiatives

Interaction with existing roles:
- Works with Developers on implementation details and code reviews
- Partners with Product Manager (PdM) on feasibility, trade-offs, and scheduling impacts
- Aligns with Project Manager (PM) on delivery timelines when technical risks affect scope

Decision authority:
- Final say on architecture within the project scope; escalates policy-level or cross-product architectural changes to engineering leadership.

Typical deliverables:
- Architecture sketches, design docs, RFCs, technical risk assessments

Escalation points:
- Escalate unresolved cross-team technical conflicts to Engineering Lead or CTO-level stakeholders.

---

### Delivery Lead / Scrum Master
Role Summary:
- Focus on team delivery efficiency, process health, and removing impediments.

Responsibilities:
- Facilitate ceremonies (standups, sprint planning, retrospectives)
- Remove impediments and escalate blockers
- Monitor team flow and suggest process improvements
- Track delivery risks and support backlog hygiene

Interaction with existing roles:
- Works with PM on schedules and risk communications
- Collaborates with Developers and QA to improve handoffs and cycle time
- Surfaces impediments to PdM when they affect scope or priorities

Decision authority:
- Guides process decisions and team-level facilitation; not typically a product-scope decision maker.

Typical deliverables:
- Sprint plans, impediment logs, retrospective action items

Escalation points:
- Escalate persistent delivery blockers to the PM or Product Lead.

---

### UX Researcher / Designer Liaison
Role Summary:
- Ensures user insights and design quality inform product decisions and implementation.

Responsibilities:
- Conduct user research and usability testing
- Define and validate user journeys and wireframes
- Ensure accessibility and design consistency
- Provide design assets and specifications to developers

Interaction with existing roles:
- Partners with PdM on prioritization based on user impact
- Works with Developers to clarify implementation details and constraints
- Collaborates with QA to define UX acceptance criteria

Decision authority:
- Final decisions on design consistency and accessibility trade-offs; major product design changes are aligned with PdM.

Typical deliverables:
- Research findings, prototypes, design specs, accessibility checks

Escalation points:
- Escalate usability or accessibility risks to Product Lead and PM.

---

### Site Reliability Engineer (SRE) / Ops Liaison
Role Summary:
- Responsible for reliability, observability, and operational readiness.

Responsibilities:
- Define SLIs/SLOs and runbook requirements
- Advise on deployment strategy, rollback plans, and capacity
- Improve system observability and incident readiness
- Participate in post-incident reviews

Interaction with existing roles:
- Works with Developers on instrumentation and resilience patterns
- Coordinates with Release Manager and PM for deployment windows and risk assessments
- Informs Product Manager of operational trade-offs that affect feature design

Decision authority:
- Owns operational readiness decisions; may block releases if SLOs or runbooks are not met.

Typical deliverables:
- Runbooks, SLO/SLA docs, observability dashboards, incident reports

Escalation points:
- Escalate critical reliability concerns to on-call leads and engineering management.

---

### Release Manager / Deployment Coordinator
Role Summary:
- Coordinates the release process and ensures deployment checklists are followed.

Responsibilities:
- Schedule release windows and communicate release plans
- Maintain and publish release notes and migration steps
- Ensure pre-release checks (QA, security, SRE) are completed
- Coordinate rollbacks and post-deploy verifications when needed

Interaction with existing roles:
- Coordinates with PM for release timing and stakeholder comms
- Works with SRE and QA during deployments
- Partners with Developers for release automation and troubleshooting

Decision authority:
- Coordinates release execution; may recommend delaying or rolling back a release based on pre-deployment checks.

Typical deliverables:
- Release notes, deployment checklists, release timelines

Escalation points:
- Escalate release-critical issues to PM and Product Lead.

---

### Business Analyst / Data Analyst
Role Summary:
- Bridges business requirements and data needs to ensure measurable outcomes.

Responsibilities:
- Clarify requirements and acceptance criteria with stakeholders
- Define success metrics and measurement approaches
- Validate data instrumentation and reporting readiness
- Support A/B testing and analytics interpretation

Interaction with existing roles:
- Works closely with PdM to define measurable outcomes
- Collaborates with Developers to implement data capture and with QA to validate analytics
- Informs PM about data-driven risks or scope impacts

Decision authority:
- Owns metric definitions and data interpretations for feature success.

Typical deliverables:
- Requirement clarifications, metric definitions, dashboards, analysis reports

Escalation points:
- Escalate data quality or measurement gaps to PdM and PM.

---

### Security / Compliance Liaison
Role Summary:
- Ensures security and compliance requirements are considered through planning and delivery.

Responsibilities:
- Review features for security and regulatory compliance requirements
- Propose controls and mitigation actions for identified security risks
- Coordinate security reviews and track remediation items
- Support secure design and threat modeling activities

Interaction with existing roles:
- Works with Tech Lead on secure architecture and mitigations
- Coordinates with PM to include security tasks in planning and releases
- Partners with Developers and QA for verification

Decision authority:
- Can require security remediation or gating before release in line with policy.

Typical deliverables:
- Security review notes, compliance checklists, remediation plans

Escalation points:
- Escalate critical security findings to Security leadership and Product Lead.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
