# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

A role may be assigned to one person or shared across a team. Where responsibilities are combined, the project should name one accountable owner for each decision and artifact.

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

### Decision Boundaries
- Owns product outcomes and backlog priority
- Does not own delivery coordination or technical implementation decisions

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

### Decision Boundaries
- Owns delivery coordination and risk visibility
- Facilitates decisions but does not set product priority or make technical design decisions

---

## QA / Testing

### Role Summary
QA and testing roles validate that delivered work meets functional, usability, and quality expectations.

### Responsibilities
- Define test scope and approach during planning
- Create and execute manual or automated tests
- Validate acceptance criteria and report defects
- Identify quality risks and contribute to the Definition of Done
- Participate in release readiness and post-release verification

### Interaction Patterns
- Partners with Developers on testability and defect resolution
- Partners with Product and Project Managers on acceptance and quality risk
- Provides evidence to stakeholders for release decisions

### Escalation
- Raise blocked or unresolved quality risks to the Project Manager and Product Manager
- Recommend release hold when acceptance evidence is insufficient

---

## Scrum Master / Delivery Facilitator

### Role Summary
The Delivery Facilitator improves team flow and protects agreed ways of working by facilitating ceremonies and removing delivery impediments.

### Responsibilities
- Initiation: help confirm team rhythms and delivery constraints
- Planning: facilitate estimation, capacity, and iteration planning
- Execution: run ceremonies, track impediments, and coach healthy team practices
- Release: coordinate team-level readiness activities
- Retrospective: facilitate candid improvement discussions and follow-up

### Interaction Patterns
- Partners with the Project Manager on risks and delivery visibility
- Partners with Developers and QA on flow, testability, and process improvements
- Escalates persistent cross-team impediments to the Project Manager

### Decision Boundaries
- Facilitates process decisions and owns the team's improvement actions
- Does not set product priority or own project risk accountability

---

## Engineering / Technical Lead

### Role Summary
The Technical Lead provides technical direction and resolves architecture, implementation, and engineering quality trade-offs.

### Responsibilities
- Initiation: identify feasibility constraints and technical risks
- Planning: define design approach, dependencies, estimates, and sequencing
- Execution: guide architecture and code quality and coordinate technical decisions
- Release: confirm technical readiness, rollback implications, and observability needs
- Retrospective: lead technical root-cause analysis and improvement actions

### Interaction Patterns
- Partners with Developers on implementation and QA on testability
- Partners with the Product Manager on feasibility and the Project Manager on dependencies
- Escalates unresolved architectural or cross-team risks to the Project Manager and stakeholders

### Decision Boundaries
- Accountable for technical direction and technical trade-off recommendations
- Does not independently change product scope or delivery commitments

---

## UX Designer / Researcher

### Role Summary
UX roles represent user needs and translate discovery findings into usable experiences and acceptance expectations.

### Responsibilities
- Initiation: contribute user evidence to problem validation
- Planning: define research plans, interaction approaches, and UX acceptance criteria
- Execution: produce designs or prototypes and support implementation
- Release: validate the delivered experience and communicate usability risks
- Retrospective: contribute usability findings and improvement opportunities

### Interaction Patterns
- Partners with the Product Manager on outcomes and the Project Manager on research timing
- Partners with Developers on implementation and QA on usability acceptance
- Shares findings with stakeholders and raises unresolved usability conflicts to the Product Manager

### Decision Boundaries
- Owns UX recommendations within agreed product direction
- Does not reprioritize the backlog or remove a product requirement

---

## Security Lead

### Role Summary
The Security Lead establishes security requirements and ensures security risk is identified, mitigated, tested, and escalated appropriately.

### Responsibilities
- Initiation: identify sensitive assets, compliance needs, and threat assumptions
- Planning: define security requirements, threat-review scope, and testing
- Execution: advise on mitigations and coordinate vulnerability review
- Release: confirm required security checks and exception handling
- Retrospective: track security lessons and improvement actions

### Interaction Patterns
- Partners with Technical Leads and Developers on secure design
- Partners with QA on security testing and the Project Manager on readiness risk
- Escalates suspected or active incidents through the security incident runbook and on-call process

### Decision Boundaries
- Can require a security review or recommend release hold for unaccepted high-risk findings
- Exceptions require the organization's approved security decision process

---

## Release / DevOps Lead

### Role Summary
The Release or DevOps Lead owns release readiness coordination, deployment automation, environment readiness, rollback planning, and post-release verification.

### Responsibilities
- Initiation: identify operational constraints and release dependencies
- Planning: establish release stages, environments, automation, and rollback approach
- Execution: prepare pipelines and environments and coordinate operational readiness
- Release: execute or coordinate deployment, smoke tests, observability checks, and rollback
- Retrospective: drive release and automation improvements

### Interaction Patterns
- Partners with the Project Manager on release windows and stakeholder communication
- Partners with Developers and Technical Leads on deployability
- Partners with QA on smoke testing and Support or stakeholders on launch readiness
- Escalates deployment failures or operational incidents through the incident process

### Decision Boundaries
- Owns technical release execution and rollback recommendations
- Does not own product priority or final business launch decisions unless delegated

---

## Customer Support Lead

### Role Summary
The Customer Support Lead represents customer-reported issues and ensures support readiness for releases and ongoing operations.

### Responsibilities
- Initiation: provide customer-impact evidence and recurring issue themes
- Planning: contribute support effort, enablement needs, and launch risks
- Execution: prepare support materials and monitor customer reports
- Release: coordinate launch communications and feedback collection
- Retrospective: feed recurring problems into backlog planning and improvement actions

### Interaction Patterns
- Partners with the Product Manager on feedback and prioritization
- Partners with the Project Manager on stakeholder communication and release planning
- Escalates high-impact or emerging incidents through agreed support and incident channels

### Decision Boundaries
- Owns support readiness and customer-facing operational guidance
- Does not independently change product scope or technical behavior

---

## Data Analyst

### Role Summary
The Data Analyst validates success measures and provides evidence about delivery, adoption, and outcomes.

### Responsibilities
- Initiation: validate metric definitions and measurement feasibility
- Planning: build reporting and instrumentation plans
- Execution: prepare dashboards, monitor trends, and investigate anomalies
- Release: validate adoption or outcome signals
- Retrospective: contribute evidence for improvement decisions

### Interaction Patterns
- Partners with the Product Manager on outcome measures
- Partners with the Project Manager on project reporting and Developers on event or data needs
- Escalates serious measurement gaps or unexpected adverse trends to the Product Manager and Project Manager

### Decision Boundaries
- Owns measurement methods and evidence quality
- Does not set product priority or claim unsupported causal conclusions

---

## Business Analyst

### Role Summary
The Business Analyst clarifies requirements, process impacts, stakeholder needs, and traceability between needs and delivered outcomes.

### Responsibilities
- Initiation: map stakeholders, workflows, requirements, and dependencies
- Planning: refine requirements, acceptance criteria, scope boundaries, and process impacts
- Execution: clarify requirements and validate process alignment
- Release: verify operational process readiness
- Retrospective: assess requirement gaps and process improvements

### Interaction Patterns
- Partners with the Product Manager on requirements and priority context
- Partners with Developers and QA on implementability and acceptance evidence
- Partners with the Project Manager on scope, dependencies, and stakeholder decisions
- Escalates unresolved requirement conflicts or cross-team process impacts to the Product Manager and Project Manager

### Decision Boundaries
- Owns requirements clarity and traceability recommendations
- Does not independently approve scope or technical architecture

---

## Responsibility Matrix

Use RACI to assign one accountable owner per activity. Projects may adapt the matrix when roles are combined or omitted.

| Activity / Artifact | Product Manager | Project Manager | Delivery Facilitator | Technical Lead | Release / DevOps Lead | Developers | QA / Testing |
|---|---|---|---|---|---|---|---|
| Outcome definition | A/R | C | C | C | I | C | C |
| Backlog priority | A/R | C | C | C | I | C | C |
| Integrated delivery plan | C | A/R | R | C | C | C | C |
| Ceremonies and impediment flow | C | C | A/R | C | I | R | R |
| Technical architecture | C | I | C | A/R | C | R | C |
| Test approach and quality evidence | C | C | C | C | C | R | A/R |
| Release readiness | C | A | C | C | R | R | R |
| Deployment and rollback | I | C | I | C | A/R | R | C |
| Retrospective actions | C | A | R | C | C | R | R |

Legend: **A** = accountable, **R** = responsible, **C** = consulted, **I** = informed.

---

## Handoff Checklist

- Initiation: confirm outcome, delivery, technical, UX, security, data, and operational owners.
- Planning: record owners for backlog, architecture, test approach, release, support, and measurement artifacts.
- Execution: communicate blocked decisions through the Project Manager while using specialist leads for technical, security, UX, or quality escalation.
- Release: confirm readiness with QA, the Release/DevOps Lead, Security Lead, Support Lead, and stakeholders when required.
- Retrospective: convert approved improvements into backlog items or issues with an owner and due date.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
