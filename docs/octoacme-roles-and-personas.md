# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Role Naming & Aliases

Different OctoAcme docs may refer to the same role by different names. The table below clarifies common aliases:

| Canonical Name | Also referred to as | Notes |
|---|---|---|
| Product Manager | Product Lead, PdM | Owns product vision and backlog prioritization |
| Project Manager | PM, Delivery Lead | Coordinates schedules, risks, and cross-team communication |
| Developers | Engineering, Dev Team | Includes frontend, backend, and full-stack contributors |
| QA / Testing | QA Engineer, Tester | May be a dedicated role or shared with Developers |

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

### Lifecycle Touchpoints
- **Initiation:** Provides rough effort estimates and flags technical feasibility risks
- **Planning:** Contributes to backlog refinement, DoD definition, and sprint planning
- **Execution:** Primary contributor; raises blockers in standups
- **Release:** Supports deployment, writes migration steps, and assists post-deploy verification
- **Retro:** Shares technical learnings and proposes engineering improvements

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

> **Alias note:** Also referred to as *Product Lead* or *PdM* in other OctoAcme docs.

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

### Lifecycle Touchpoints
- **Initiation:** Authors the project one-pager; reviews with sponsor
- **Planning:** Owns backlog prioritization and acceptance criteria
- **Execution:** Validates completed work against acceptance criteria
- **Release:** Reviews and approves release notes
- **Retro:** Reviews success metrics and prioritizes improvement actions

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

> **Alias note:** Also referred to as *PM* or *Delivery Lead* in other OctoAcme docs.

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

### Lifecycle Touchpoints
- **Initiation:** Facilitates stakeholder alignment and creates the project board skeleton
- **Planning:** Runs kickoff meeting; tracks dependencies and risk register
- **Execution:** Monitors progress, escalates blockers, updates risk register weekly
- **Release:** Schedules deployment windows; coordinates release communications
- **Retro:** Facilitates retrospective and tracks action items to completion

---

## UX Designer

### Role Summary
UX Designers drive user experience practices by researching user needs, creating prototypes, and validating usability. They collaborate closely with Product Managers on requirements and with Developers on implementation to ensure deliverables meet customer needs.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Define and validate user flows and interaction patterns
- Provide continuous design feedback during development
- Maintain a design system or style guide for the project

### Goals
- Ensure features are intuitive and meet real user needs
- Reduce rework by validating designs before implementation
- Bridge the gap between product requirements and technical delivery

### Typical Communication
- Design reviews with Product Managers and Developers
- Usability test findings shared with the team
- Annotated prototypes and design specs in shared repositories

### Interaction Model
- **With Product Managers:** Co-define user stories and acceptance criteria; translate product goals into user flows
- **With Developers:** Provide design specs and answer implementation questions; review built UI against designs
- **With Project Managers:** Flag design-related risks or scope changes; estimate design effort during planning

### Lifecycle Touchpoints
- **Initiation:** Contributes user research insights to the project one-pager
- **Planning:** Creates initial wireframes and participates in backlog refinement
- **Execution:** Produces detailed designs and reviews implemented UI in sprints
- **Release:** Validates final UX before release; contributes to release notes where user-facing changes are significant
- **Retro:** Reviews usability feedback and proposes UX improvements

---

## DevOps Engineer

### Role Summary
DevOps Engineers own build pipelines, deployment strategies, infrastructure as code, and site reliability efforts. They work closely with Developers to streamline deliveries to production and respond rapidly to incidents or downtime.

### Responsibilities
- Design and maintain CI/CD pipelines and release automation
- Manage cloud infrastructure and environment configuration (infrastructure as code)
- Monitor system reliability, performance, and uptime
- Respond to and triage production incidents
- Enforce security scanning and compliance checks in the pipeline

### Goals
- Enable fast, reliable, and repeatable deployments
- Minimize deployment risk and mean time to recovery (MTTR)
- Provide developers with observable, self-service infrastructure

### Typical Communication
- Incident notifications and post-mortem reports
- Infrastructure change announcements
- Pipeline status and deployment runbooks

### Interaction Model
- **With Developers:** Define branching strategies, review deployment-related PRs, and support local environment parity
- **With Product Managers:** Communicate infrastructure constraints that affect feature timelines
- **With Project Managers:** Surface infrastructure risks in the risk register; confirm deployment windows

### Lifecycle Touchpoints
- **Initiation:** Identifies infrastructure requirements and potential technical blockers
- **Planning:** Estimates infrastructure work and flags environment dependencies
- **Execution:** Maintains CI pipeline health; reviews deployment-related changes
- **Release:** Executes deployment checklist; manages rollback plan and smoke tests
- **Retro:** Reviews incident history and deployment metrics; drives reliability improvements

---

## Data Analyst

### Role Summary
Data Analysts support evidence-based decisions by defining success metrics, building dashboards, and generating actionable insights from user and system data. They partner primarily with Product Managers to track outcomes and drive data-driven improvements.

### Responsibilities
- Define and document measurable success metrics for projects
- Build and maintain dashboards tracking key performance indicators (KPIs)
- Analyze experiment results and usage data
- Identify trends and surface insights to the product and project team
- Support data quality and integrity in reporting pipelines

### Goals
- Ensure decisions are grounded in data rather than assumptions
- Provide timely and actionable insights to the team
- Make success metrics visible and understandable to all stakeholders

### Typical Communication
- Dashboard links and metric reports shared in weekly syncs
- Analysis write-ups for feature experiments and A/B tests
- Data review sessions with Product Managers

### Interaction Model
- **With Product Managers:** Co-define success metrics during initiation; review experiment results together
- **With Developers:** Collaborate on instrumentation and event tracking requirements
- **With Project Managers:** Provide data to inform release readiness and project health reporting

### Lifecycle Touchpoints
- **Initiation:** Helps define measurable success metrics in the project one-pager
- **Planning:** Identifies data collection requirements and instrumentation gaps
- **Execution:** Monitors dashboards and flags anomalies; supports ongoing measurement
- **Release:** Validates metric baselines before and after release
- **Retro:** Presents outcome data and experiment results to inform improvement priorities

---

## Support Lead

### Role Summary
Support Leads act as the bridge between the project team and end users. They triage user feedback and production issues, communicate release changes, and coordinate with Product Managers and QA on escalated items.

### Responsibilities
- Triage incoming user feedback and production bug reports
- Escalate critical issues to engineering and project teams
- Communicate planned changes and outages to users and support staff
- Coordinate with QA during user acceptance testing (UAT)
- Help Product Managers refine acceptance criteria based on real-world usage patterns

### Goals
- Reduce the impact of production issues on end users
- Ensure users are informed about changes that affect them
- Feed real-world insights back into the product and project process

### Typical Communication
- Incident communications and outage notices to users and stakeholders
- Bug and feedback triage reports shared with Product and QA
- Participation in UAT and release readiness reviews

### Interaction Model
- **With Product Managers:** Provide user feedback and production bug trends to inform backlog prioritization
- **With Developers / DevOps:** Escalate critical production issues; collaborate on incident triage
- **With Project Managers:** Flag emerging user-facing risks; confirm release communication plans

### Lifecycle Touchpoints
- **Initiation:** Provides input on user pain points and known support gaps
- **Planning:** Reviews acceptance criteria and flags operational considerations
- **Execution:** Participates in UAT; validates fixes resolve reported issues
- **Release:** Drafts user-facing release communications; confirms support staff are briefed
- **Retro:** Shares support ticket trends and escalation patterns as improvement input

---

## RACI Summary Matrix

This matrix maps common OctoAcme artifacts and activities to roles using a simplified RACI model:
- **R** = Responsible (does the work)
- **A** = Accountable (owns the outcome)
- **C** = Consulted (provides input before/during)
- **I** = Informed (notified of progress/completion)

| Artifact / Activity | Developers | Product Manager | Project Manager | UX Designer | DevOps Engineer | Data Analyst | Support Lead |
|---|---|---|---|---|---|---|---|
| Project One-pager | C | A/R | C | C | C | C | C |
| Backlog & Acceptance Criteria | C | A/R | I | C | C | C | C |
| Definition of Done (DoD) | A/R | C | C | C | C | — | — |
| Risk Register | C | C | A/R | I | C | I | I |
| Sprint / Iteration Planning | R | A | R | C | C | I | I |
| CI/CD Pipeline & Deployments | C | I | I | I | A/R | I | I |
| Release Notes | C | A | R | C | C | I | R |
| Incident Communications | C | I | I | I | R | I | A/R |
| Retro Action Items | C | C | A/R | C | C | C | C |
| Success Metrics & Dashboards | C | A | I | C | C | R | C |
| User Research & Prototypes | C | C | I | A/R | — | C | C |

> For a standalone version of this matrix, see [docs/templates/role-raci-matrix.md](templates/role-raci-matrix.md).

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

