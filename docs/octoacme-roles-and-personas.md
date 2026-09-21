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

## Additional cross-functional personas (as needed)

On smaller projects, one person may cover multiple roles. On larger or higher-risk efforts, these personas can be staffed explicitly or consulted during specific phases based on scope, risk, compliance needs, and delivery complexity.

### UX/UI or Product Designer

#### Role Summary
Designers translate user and business needs into usable, accessible product experiences and interaction patterns.

#### Responsibilities
- Partner with Product Managers during [project initiation](octoacme-project-initiation.md) to clarify user problems, personas, and success criteria
- Produce wireframes, interaction flows, and visual designs during [project planning](octoacme-project-planning.md)
- Support design QA during [execution and tracking](octoacme-execution-and-tracking.md)
- Contribute usability insights in [retrospectives](octoacme-retrospective-and-continuous-improvement.md)

#### Goals
- Improve usability, accessibility, and task success rates
- Reduce rework from unclear interaction expectations

#### Typical Communication
- Design reviews with Developers, QA/Testing, and Product Managers
- Annotated mockups, prototypes, and acceptance notes

#### Decision Rights and Deliverables
- Own interaction and visual design decisions within product constraints
- Deliver design artifacts, component usage guidance, and UX acceptance criteria

#### Collaboration and Interactions
- Works with Developers to ensure implementation fidelity
- Partners with Product Managers on discovery and prioritization trade-offs
- Coordinates with Project Managers on design milestones and dependencies
- Supports QA/Testing with usability and accessibility validation
- Shares rationale and outcomes with Stakeholders in demos/reviews

### Technical Lead or Architect

#### Role Summary
Technical Leads/Architects define and steward technical direction so delivery remains scalable, secure, and maintainable.

#### Responsibilities
- Define architecture approach, integration boundaries, and non-functional requirements during [planning](octoacme-project-planning.md)
- Identify and mitigate technical risks through the [risk management process](octoacme-risks-and-communication.md)
- Guide implementation quality during [execution and tracking](octoacme-execution-and-tracking.md)
- Support release readiness and rollback design in [release and deployment](octoacme-release-and-deployment.md)

#### Goals
- Balance speed of delivery with long-term maintainability
- Reduce production incidents caused by design or integration gaps

#### Typical Communication
- Architecture decision records and technical design reviews
- Risk/constraint discussions with Product and Project Managers

#### Decision Rights and Deliverables
- Recommends or approves architecture patterns, standards, and key technical trade-offs
- Delivers architecture diagrams, design decisions, and implementation guardrails

#### Collaboration and Interactions
- Coaches Developers on implementation approaches and code quality
- Aligns with Product Managers on feasibility, scope options, and sequencing
- Works with Project Managers to map technical dependencies and critical path risks
- Partners with QA/Testing on quality strategy and testability of key flows
- Informs Stakeholders on technical risk, cost, and delivery implications

### Business Analyst or Product Operations Partner

#### Role Summary
Business Analysts/Product Operations partners translate operational and business needs into clear, actionable requirements and delivery insights.

#### Responsibilities
- Support [initiation](octoacme-project-initiation.md) by refining problem statements, assumptions, and stakeholder needs
- Define process impacts, acceptance conditions, and traceable requirements in [planning](octoacme-project-planning.md)
- Track execution metrics and decision follow-through during [execution and tracking](octoacme-execution-and-tracking.md)
- Feed outcomes and learning into [retrospectives](octoacme-retrospective-and-continuous-improvement.md)

#### Goals
- Reduce ambiguity and rework from unclear requirements
- Improve transparency from request through outcome measurement

#### Typical Communication
- Requirement reviews, process walkthroughs, and backlog refinement sessions
- Status and outcome summaries for Product Managers and Stakeholders

#### Decision Rights and Deliverables
- Owns requirements clarity and traceability practices
- Delivers requirement artifacts, process maps, and operational readiness checklists

#### Collaboration and Interactions
- Works with Developers to clarify edge cases and workflow expectations
- Supports Product Managers with backlog quality and prioritization inputs
- Partners with Project Managers on scope tracking and dependency visibility
- Coordinates with QA/Testing on test scenarios tied to business outcomes
- Aligns Stakeholders on expected outcomes, constraints, and adoption needs

### Release or Delivery Engineer

#### Role Summary
Release/Delivery Engineers operationalize build, release, and deployment workflows for consistent, low-risk delivery.

#### Responsibilities
- Define release pipeline and environment readiness checkpoints in [planning](octoacme-project-planning.md)
- Support CI/CD flow and release governance during [execution and tracking](octoacme-execution-and-tracking.md)
- Lead release orchestration, smoke validation, and rollback readiness during [release and deployment](octoacme-release-and-deployment.md)
- Surface deployment risks through [risk and communication practices](octoacme-risks-and-communication.md)

#### Goals
- Increase deployment reliability and reduce change failure rate
- Improve release predictability and recovery speed

#### Typical Communication
- Release plans, deployment windows, and go/no-go checklists
- Incident/deployment channel updates during release events

#### Decision Rights and Deliverables
- Owns release process execution standards and deployment readiness gates
- Delivers runbooks, deployment checklists, release notes inputs, and rollback plans

#### Collaboration and Interactions
- Partners with Developers on build packaging and environment compatibility
- Coordinates with Product Managers and Project Managers on release scope/timing
- Works with QA/Testing on pre-release validation and post-deploy checks
- Communicates release status, risks, and outcomes to Stakeholders

### Customer Support or Operations Representative

#### Role Summary
Support/Operations representatives bring customer impact and production realities into planning, release, and continuous improvement.

#### Responsibilities
- Share customer pain points and operational constraints during [initiation](octoacme-project-initiation.md) and [planning](octoacme-project-planning.md)
- Prepare support readiness artifacts before [release and deployment](octoacme-release-and-deployment.md)
- Monitor adoption, incidents, and escalations during [execution and tracking](octoacme-execution-and-tracking.md)
- Contribute customer-facing lessons in [retrospectives](octoacme-retrospective-and-continuous-improvement.md)

#### Goals
- Reduce customer-facing disruption during changes
- Improve time-to-resolution and support experience quality

#### Typical Communication
- Support trend reports, escalation summaries, and runbook feedback
- Release readiness syncs with delivery teams

#### Decision Rights and Deliverables
- Owns support readiness inputs and operational handoff quality
- Delivers FAQs, support scripts, escalation paths, and readiness checklists

#### Collaboration and Interactions
- Works with Developers on reproducible issue details and mitigation paths
- Partners with Product Managers on customer impact prioritization
- Coordinates with Project Managers on communications and go-live preparedness
- Aligns with QA/Testing on high-risk user scenarios and known limitations
- Represents customer and operational concerns to Stakeholders

### Security, Privacy, or Compliance Partner

#### Role Summary
Security/Privacy/Compliance partners ensure controls, policies, and regulatory expectations are addressed through the delivery lifecycle.

#### Responsibilities
- Identify regulatory/security requirements in [initiation](octoacme-project-initiation.md)
- Advise on control requirements, data handling, and evidence expectations in [planning](octoacme-project-planning.md)
- Monitor risk treatment and exception handling in [risk management and communication](octoacme-risks-and-communication.md)
- Validate release controls in [release and deployment](octoacme-release-and-deployment.md)

#### Goals
- Reduce security/privacy risk exposure
- Maintain auditability and policy compliance without unnecessary delivery friction

#### Typical Communication
- Security/compliance reviews, risk acceptance notes, and control checklists
- Escalation paths for high-severity findings

#### Decision Rights and Deliverables
- Approves or advises on security/privacy control sufficiency and exception handling
- Delivers threat/risk findings, compliance guidance, and evidence requirements

#### Collaboration and Interactions
- Works with Developers on secure implementation and remediation priorities
- Partners with Product Managers on compliant feature design trade-offs
- Supports Project Managers with compliance milestones and risk tracking
- Coordinates with QA/Testing on security and privacy validation scenarios
- Informs Stakeholders of compliance posture and release implications

### Data/Analytics Partner

#### Role Summary
Data/Analytics partners define measurement strategy and insights that guide prioritization, execution, and continuous improvement.

#### Responsibilities
- Define success metrics and instrumentation needs during [initiation](octoacme-project-initiation.md) and [planning](octoacme-project-planning.md)
- Validate tracking implementation during [execution and tracking](octoacme-execution-and-tracking.md)
- Analyze release impact after [deployment](octoacme-release-and-deployment.md)
- Provide evidence-based recommendations in [retrospectives](octoacme-retrospective-and-continuous-improvement.md)

#### Goals
- Improve decision quality with timely, reliable metrics
- Connect delivered work to measurable business and customer outcomes

#### Typical Communication
- Dashboard reviews, experiment readouts, and KPI status updates
- Metric definitions and instrumentation guidance

#### Decision Rights and Deliverables
- Owns measurement definitions, data quality checks, and reporting practices
- Delivers KPI definitions, dashboards, experiment analyses, and outcome summaries

#### Collaboration and Interactions
- Works with Developers on event instrumentation and data quality
- Partners with Product Managers on outcome metrics and hypothesis validation
- Coordinates with Project Managers on reporting cadence and milestone evidence
- Supports QA/Testing in validating analytics events and data completeness
- Shares insights and trade-off implications with Stakeholders

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
