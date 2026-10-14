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

## Delivery Lead / Engineering Manager

### Role Summary
Delivery Leads (often Engineering Managers) focus on team-level delivery, capacity, and people management to ensure reliable execution against the project plan.

### Responsibilities
- Coordinate sprint-level delivery and capacity planning
- Balance resources across workstreams and remove impediments
- Support career development and performance guidance for engineers
- Help prioritize technical work and operational improvements

### Goals
- Ensure predictable delivery and healthy team capacity
- Reduce bottlenecks and unblock work quickly
- Maintain team morale and growth

### Typical Communication / Interactions
- Works closely with the Project Manager on schedules and dependency coordination
- Partners with Product Managers to align capacity to priorities
- Collaborates with Engineering Leads and Developers on implementation risks and technical blockers
- Coordinates with QA to ensure testing capacity and release readiness

---

## Engineering Lead / Tech Lead

### Role Summary
Engineering Leads (Tech Leads) own technical direction, architecture decisions, and code quality within a project or feature area.

### Responsibilities
- Lead technical design and architecture for features
- Drive code quality, standards, and reviews
- Prioritize technical debt and mentor engineers on implementation choices
- Perform risk analysis for technical approaches

### Goals
- Deliver scalable, maintainable, and secure solutions
- Reduce long-term maintenance cost through good design
- Accelerate developer productivity with clear technical guidance

### Typical Communication / Interactions
- Advises Product Managers on technical trade-offs and effort implications
- Mentors Developers and performs design/code reviews
- Coordinates with Delivery Lead on implementation timelines
- Works with Release/DevOps Engineers on deployability and environment needs

---

## UX / Product Designer

### Role Summary
UX/Product Designers lead user research, define user flows and UI specifications, and ensure products are usable and accessible.

### Responsibilities
- Conduct user research and usability testing
- Produce design specs, prototypes, and accessibility guidance
- Collaborate on acceptance criteria that reflect user needs
- Validate designs before and after implementation

### Goals
- Deliver intuitive, accessible user experiences that meet business goals
- Reduce rework by clarifying UX expectations early

### Typical Communication / Interactions
- Partners with Product Managers to translate requirements into designs
- Hands off designs and assets to Developers and Engineering Leads
- Works with QA on usability checks and acceptance testing
- Engages with Analytics Owner to validate UX assumptions using data

---

## Release / DevOps Engineer

### Role Summary
Release or DevOps Engineers own CI/CD pipelines, environment stability, and runbooks to ensure safe, reliable deployments.

### Responsibilities
- Maintain and improve CI/CD pipelines and deployment automation
- Create deployment and rollback runbooks and verify staging environments
- Monitor deployment health and operational metrics
- Support incident response and post-deploy verification

### Goals
- Enable fast, low-risk deployments and quick rollbacks
- Improve operational resilience and observability

### Typical Communication / Interactions
- Coordinates with Project Manager and Delivery Lead on release windows and plans
- Works with Developers and Engineering Leads on deployment requirements and automation
- Partners with Support Liaison during incidents and with Security Owner for secure deployments

---

## Security Owner / Security Reviewer

### Role Summary
Security Owners provide guidance on security design, perform threat modeling, and drive remediation of vulnerabilities.

### Responsibilities
- Lead threat modeling and security reviews for features
- Define security requirements and compliance checks
- Triage and prioritize security findings and remediation
- Maintain security runbooks and coordinate vulnerability disclosures

### Goals
- Reduce security risk and ensure compliance with organizational policies
- Bake security considerations into the delivery lifecycle

### Typical Communication / Interactions
- Consults with Engineering Leads and Tech Leads during architecture and design
- Informs Project Managers of security-related schedule impacts or constraints
- Works with Release/DevOps to ensure secure deployment practices

---

## QA Lead / Test Engineer

### Role Summary
QA Leads define testing strategies and own verification that features meet acceptance criteria and quality standards.

### Responsibilities
- Define test strategies and maintain test suites (unit/integration/e2e)
- Validate acceptance criteria and run pre-release checks
- Coordinate test environments and automation efforts
- Track and report quality metrics

### Goals
- Ensure high confidence in releases and reduce production regressions
- Improve automation coverage and reduce manual testing overhead

### Typical Communication / Interactions
- Works with Developers to ensure testability and coverage
- Partners with Product Managers to clarify acceptance criteria
- Coordinates with Release/DevOps on pre-release checks and staging tests

---

## Data / Analytics Owner

### Role Summary
Data or Analytics Owners define what to measure, own instrumentation plans, and ensure the team can measure success against defined metrics.

### Responsibilities
- Define success metrics, telemetry, and dashboards
- Specify instrumentation requirements and validate data quality
- Analyze results and provide insights to inform product decisions

### Goals
- Ensure product decisions are data-informed and success is measurable
- Provide timely, accurate metrics that validate outcomes

### Typical Communication / Interactions
- Partners with Product Managers to define success metrics and experiments
- Works with Developers to implement instrumentation and with QA to validate data pipelines
- Reports findings to PM and Project Manager for regular status updates

---

## Support Liaison / On-call Representative

### Role Summary
Support Liaisons bridge post-release operational support, incident triage, and feedback loops between users, support, and engineering.

### Responsibilities
- Triage and coordinate incidents and support tickets
- Communicate impact and timelines to Product and Project Managers
- Feed user-reported issues back into the backlog and track fixes

### Goals
- Reduce time-to-resolution for production issues
- Ensure customer-impacting problems are prioritized and addressed

### Typical Communication / Interactions
- Communicates incidents and status to PM and PdM
- Works with Release/DevOps and Developers during incident response
- Coordinates bug triage and prioritization with engineering

---

## Compliance / Privacy Owner

### Role Summary
Compliance or Privacy Owners ensure regulatory and privacy requirements are identified, documented, and satisfied for applicable projects.

### Responsibilities
- Identify applicable regulations and privacy requirements
- Coordinate evidence collection and documentation for audits
- Advise on design or scope changes needed for compliance

### Goals
- Ensure the product meets legal and regulatory obligations
- Reduce compliance risk through proactive guidance

### Typical Communication / Interactions
- Advises Product Managers on scope and timeline implications
- Works with Engineering Leads to implement controls and evidence collection
- Coordinates with Security Owner and Support Liaison as needed

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
