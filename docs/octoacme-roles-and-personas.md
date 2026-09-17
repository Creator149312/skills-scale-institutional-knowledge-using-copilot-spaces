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

## Engineering Lead

### Role Summary
The Engineering Lead owns technical execution across teams, aligns architecture decisions with product goals, and coordinates delivery for complex dependencies.

### Responsibilities
- Own technical implementation plans and architecture alignment
- Coordinate delivery sequencing across developer teams
- Resolve technical blockers and escalate capacity or dependency risks
- Ensure non-functional requirements (performance, reliability, observability) are addressed

### Key Interactions
- Developers: provides technical direction, reviews designs, and supports execution trade-offs
- Product Managers: aligns solution design with product outcomes and scope decisions
- Project Managers: coordinates delivery milestones, dependencies, and risk escalation
- QA/Testing: ensures testability is designed early and quality risks are addressed before release

### Goals
- Deliver technically sound solutions on predictable timelines
- Reduce cross-team integration risk and rework
- Maintain architectural consistency and delivery quality

### Typical Communication
- Engineering planning syncs and architecture reviews
- Cross-team dependency discussions and milestone alignment updates
- Technical risk and readiness updates to PM/PdM and QA/Testing

---

## QA/Test Lead

### Role Summary
The QA/Test Lead defines test strategy and quality gates, then validates that acceptance criteria and release readiness standards are met.

### Responsibilities
- Define the test strategy for unit, integration, end-to-end, and manual validation
- Set and enforce quality gates for feature acceptance and release readiness
- Coordinate defect triage priorities and test coverage improvements
- Escalate quality risks that threaten delivery commitments

### Key Interactions
- Developers: aligns testability requirements, automation scope, and defect resolution workflows
- Product Managers: verifies acceptance criteria are testable and validates user-facing behavior
- Project Managers: provides quality status, risk visibility, and go/no-go input for milestones
- QA/Testing: organizes execution across testers and ensures consistent validation practices

### Goals
- Improve defect prevention and early risk detection
- Ensure consistent, measurable quality outcomes
- Protect release confidence through reliable validation

### Typical Communication
- Test strategy reviews and quality dashboard updates
- Defect triage and quality gate decision meetings
- Release readiness reports shared with PM/PdM and engineering

---

## Release Manager

### Role Summary
The Release Manager coordinates deployment windows, rollback readiness, and release communications so delivery changes reach production safely.

### Responsibilities
- Plan release calendars, cutover timing, and deployment checklists
- Confirm rollback plans, runbooks, and operational readiness
- Coordinate release approvals and change communication
- Escalate release blockers or sequencing conflicts across teams

### Key Interactions
- Developers: validates deployment prerequisites, feature flags, and rollback support
- Product Managers: aligns release scope with customer-facing commitments
- Project Managers: synchronizes release milestones, risk responses, and stakeholder timing
- QA/Testing: confirms test completion and final validation before production promotion

### Goals
- Increase release predictability and production safety
- Minimize deployment disruption and recovery time
- Keep stakeholders informed before, during, and after releases

### Typical Communication
- Release planning meetings and go/no-go checkpoints
- Deployment status and incident/rollback communications
- Post-release summary updates to PM/PdM, engineering, and QA/Testing

---

## Security/Compliance Lead

### Role Summary
The Security/Compliance Lead reviews delivery risk, governance requirements, and secure implementation practices to ensure releases meet policy and regulatory expectations.

### Responsibilities
- Define and review security and compliance requirements for project scope
- Assess risks in architecture, dependencies, and delivery workflows
- Coordinate remediation priorities for security or compliance gaps
- Escalate unresolved governance risks before release approvals

### Key Interactions
- Developers: partners on secure coding, threat mitigation, and remediation planning
- Product Managers: aligns compliance obligations with product requirements and prioritization
- Project Managers: tracks governance risks, approvals, and mitigation timelines
- QA/Testing: integrates security and compliance checks into validation gates

### Goals
- Reduce security exposure and compliance drift
- Ensure governance requirements are met without blocking delivery late
- Build repeatable secure-delivery practices across teams

### Typical Communication
- Risk reviews, threat-model sessions, and compliance check-ins
- Security findings and mitigation tracking updates
- Release risk sign-off input shared with PM/PdM, engineering, and QA/Testing

---

## Customer Success / Stakeholder Liaison

### Role Summary
The Customer Success / Stakeholder Liaison aligns delivery with customer outcomes, manages stakeholder updates, and prepares adoption readiness plans.

### Responsibilities
- Gather and synthesize stakeholder feedback and customer adoption risks
- Coordinate readiness plans for enablement, rollout communication, and support
- Maintain alignment between delivery progress and customer expectations
- Escalate stakeholder concerns that could impact scope, timing, or adoption

### Key Interactions
- Developers: communicates customer context that affects implementation details
- Product Managers: aligns release messaging with value propositions and success criteria
- Project Managers: coordinates stakeholder cadence, action items, and escalation paths
- QA/Testing: shares user-impact insights for acceptance scenarios and post-release checks

### Goals
- Improve stakeholder confidence and customer readiness
- Reduce adoption friction during rollouts
- Ensure delivered outcomes match communicated expectations

### Typical Communication
- Stakeholder briefings and customer-readiness checkpoints
- Feedback summaries and adoption-risk updates
- Cross-functional rollout communications with PM/PdM, engineering, and QA/Testing

---

## Data/Analytics Lead

### Role Summary
The Data/Analytics Lead defines success measurement, reporting, and evidence tracking so teams can verify outcomes and guide future decisions.

### Responsibilities
- Define delivery and outcome metrics with clear baselines and targets
- Build and maintain reporting cadences for milestone and post-release tracking
- Validate data quality for decision-making and retrospective analysis
- Escalate gaps in instrumentation, reporting coverage, or metric ownership

### Key Interactions
- Developers: specifies instrumentation requirements and validates data capture
- Product Managers: aligns metrics to product hypotheses and business outcomes
- Project Managers: provides status evidence and trend reporting for stakeholder updates
- QA/Testing: confirms measurement signals align with quality and acceptance expectations

### Goals
- Improve evidence-based planning and prioritization
- Increase visibility into delivery health and impact
- Strengthen accountability for measurable outcomes

### Typical Communication
- Metrics definition workshops and reporting reviews
- Weekly trend summaries and milestone evidence updates
- Post-release and retrospective insights shared with PM/PdM, engineering, and QA/Testing

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
