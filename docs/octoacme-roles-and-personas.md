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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas

The following personas are additions to improve clarity, handoffs, and accountability for cross-cutting concerns such as releases, platform stability, security, UX, and customer readiness.

### Release Manager
Role summary
- Owns release coordination and readiness for production deployments.

Responsibilities
- Coordinate release schedule and deployment windows.
- Authorize deployment readiness (sign-off on release checklist).
- Own release notes and post-release verification.
- Make rollback or mitigation decisions when necessary.

Interaction points
- Works closely with PM, PdM, Developers, QA, and Platform/DevOps for scheduling and readiness.
- Notifies Customer Success/Support for customer-impacting changes.

### Program Manager
Role summary
- Coordinates across multiple related projects to manage cross-team dependencies and milestone-level risks.

Responsibilities
- Track program-level milestones, dependencies, and risks.
- Facilitate cross-project planning and synchronization.
- Escalate strategic conflicts to Product Lead and Sponsor.

Interaction points
- Partners with Project Managers for day-to-day execution oversight.
- Engages Product Lead and PMs to resolve resource or priority conflicts.

### Platform / DevOps Lead
Role summary
- Ensures platform stability, CI/CD practices, and environment standards.

Responsibilities
- Maintain and improve deployment pipelines and environment reliability.
- Define platform constraints, standards, and observability requirements.
- Support production troubleshooting and on-call runbook readiness.

Interaction points
- Collaborates with Developers and Release Manager on pipeline and deployment issues.
- Advises PMs on lead time and platform-related risks.

### UX Researcher / Design Lead
Role summary
- Drives user research and ensures design findings inform acceptance criteria and prioritization.

Responsibilities
- Plan and run research studies and usability testing.
- Synthesize findings into actionable design requirements and acceptance criteria.
- Validate proposed solutions against user needs.

Interaction points
- Works with PdM on prioritization and with Developers for implementation details.
- Provides artifacts for PRs and acceptance criteria where UX impact exists.

### Security Liaison
Role summary
- Coordinates security reviews and ensures security considerations are embedded in the lifecycle.

Responsibilities
- Schedule and conduct security reviews and threat modeling.
- Track security findings and remediation plans.
- Ensure security acceptance criteria and compliance checks are in place.

Interaction points
- Partners with Developers and Platform Lead on fixes; escalates critical issues to Product Lead and Security on-call.

### Customer Success / Support Representative
Role summary
- Represents customer impact and readiness; prioritizes customer-facing issues.

Responsibilities
- Provide customer context and prioritize support/enablement needs.
- Coordinate onboarding materials, release communications, and support runbooks.
- Feed customer feedback into the backlog.

Interaction points
- Works with PdM and PM on release readiness and stakeholder communications.
- Provides input to QA and Documentation for customer-facing content.

---

## Interaction Matrix
A concise matrix outlining primary touchpoints and responsibilities for quick reference.

| Role \\\ Touchpoint | Planning & Prioritization | Build & QA | Release Readiness | Post-release (Support) | Escalation Owner |
|-------------------:|:-------------------------:|:----------:|:-----------------:|:-----------------------:|:----------------:|
| Product Manager    | Owns outcomes & prioritization | Define acceptance criteria | Inform PD/PM of priorities | Monitor success metrics | PdM / Product Lead |
| Project Manager    | Coordinate timelines & resources | Track in-progress work | Coordinate cross-team readiness | Ensure actions for follow-ups | PM |
| Release Manager    | Input for scheduling | Validate release artifacts (notes, migrations) | Own sign-off and deployment | Coordinate rollback if needed | Release Manager |
| Platform/DevOps    | Advise on constraints | Maintain CI/CD & envs | Execute/verify pipeline | Lead triage for platform incidents | Platform Lead |
| Developers         | Implement features | Unit/integration tests | Provide build artifacts & fixes | Respond to incidents | Feature owner / Dev |
| QA                 | Test planning | Execute test plans | Validate smoke tests | Triage regressions | QA Lead |
| Security Liaison   | Define security criteria | Conduct reviews | Validate remediation | Escalate critical findings | Security Liaison |
| UX Research/Design | Research inputs | Validate UI/UX | Approve UX-related releases | Monitor UX metrics | Design Lead |
| Customer Success   | Provide customer priorities | Validate docs & onboarding | Coordinate customer comms | Lead customer-facing response | CS Rep |

Notes:
- This matrix is intended as a short reference. For complex releases, use the Release Readiness Checklist (docs/release-readiness-checklist.md).

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
