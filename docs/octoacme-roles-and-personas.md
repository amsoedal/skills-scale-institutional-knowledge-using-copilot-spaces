# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.
Role definitions are adaptable to the team’s operating model; on smaller teams, one person may cover multiple roles.

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

## QA / Test Engineer

### Role Summary
QA / Test Engineers assess product quality and risk by defining and executing test strategies that verify expected behavior and readiness.

### Responsibilities
- Develop risk-based test plans and maintain automated or manual tests
- Verify acceptance criteria and report defects, coverage gaps, and quality risks
- Partner with Developers to improve testability and resolve issues
- Coordinate test environments and regression or exploratory testing

### Goals
- Detect important issues early and provide reliable evidence of quality
- Ensure delivered behavior meets agreed acceptance criteria
- Make quality risks and release readiness visible

### Decision / Approval Boundaries
- Choose appropriate test methods and report whether quality evidence meets agreed criteria
- Recommend against release when material quality risks remain; does not independently change product scope or accept business risk
- Escalate unresolved acceptance or risk decisions to the Product Manager and Project Manager

### Typical Communication
- Test plans, test results, defect reports, and quality-risk updates
- Triage discussions with Developers and readiness reviews with delivery leads

### Collaboration & Handoffs
- Aligns expected behavior and acceptance criteria with the Product Manager, and reports verification results for product acceptance
- Works with Developers on testability, defect reproduction, and fixes; hands verified results and open risks back to them
- Shares coverage, blockers, and readiness risks with the Project Manager for plans and status updates
- Coordinates release verification with the Release / Operations (SRE) Lead

---

## Design / UX Researcher

### Role Summary
Design / UX Researchers investigate user needs and shape usable, accessible solutions through research, design, and validation.

### Responsibilities
- Plan and conduct user research; synthesize findings and usability risks
- Create and validate design flows, prototypes, and accessibility guidance
- Document design decisions and communicate implications to delivery partners
- Review implemented experiences and identify gaps from intended behavior

### Goals
- Ensure solutions address validated user needs
- Improve usability, accessibility, and consistency
- Give the team actionable evidence to guide product decisions

### Decision / Approval Boundaries
- Select appropriate research methods and make design recommendations within agreed product goals
- Does not set product priority or unilaterally approve technical feasibility; escalate scope or policy trade-offs to the Product Manager
- Surface usability or accessibility risks to the Product Manager and Project Manager when they affect delivery

### Typical Communication
- Research plans and findings, design reviews, prototypes, and accessibility notes
- Regular product and engineering critiques, with timing and dependency updates to the Project Manager

### Collaboration & Handoffs
- Partners with the Product Manager to frame research questions, validate outcomes, and translate findings into backlog decisions
- Reviews feasibility and design details with Developers and the Tech Lead / Engineering Lead; hands off validated designs and acceptance considerations
- Coordinates research, reviews, and design dependencies with the Project Manager
- Shares usability and accessibility risks with the QA / Test Engineer for verification planning

---

## Tech Lead / Engineering Lead

### Role Summary
Tech Leads / Engineering Leads guide technical decisions and engineering coordination so the team can deliver maintainable solutions within agreed constraints.

### Responsibilities
- Guide architecture, technical design, code quality, and engineering standards
- Support estimation and identify technical risks, dependencies, and mitigations
- Coordinate implementation across Developers and support technical problem-solving
- Communicate engineering progress and trade-offs to product and project leads

### Goals
- Deliver secure, reliable, maintainable solutions
- Make technical choices and risks clear early
- Help Developers execute effectively without compromising agreed quality

### Decision / Approval Boundaries
- Decide or facilitate technical approaches within agreed architecture, security, and delivery constraints
- Does not unilaterally change product scope, priority, or commitments; raise material cost, risk, or schedule trade-offs with the Product Manager and Project Manager
- Escalate decisions beyond delegated engineering authority to the appropriate technical owner

### Typical Communication
- Design proposals, estimates, code reviews, and technical risk updates
- Engineering syncs with Developers and planning or trade-off discussions with product and project leads

### Collaboration & Handoffs
- Coordinates implementation and review with Developers, handing off technical decisions, estimates, and actionable work
- Advises the Product Manager on feasibility and trade-offs so scope and acceptance criteria can be adjusted deliberately
- Provides the Project Manager with dependencies, estimates, risks, and milestone impacts
- Aligns testability with the QA / Test Engineer, design implementation with the Design / UX Researcher, and deployability with the Release / Operations (SRE) Lead

---

## Release / Operations (SRE) Lead

### Role Summary
Release / Operations (SRE) Leads coordinate safe deployment and operational readiness, including monitoring, incident response, and recovery.

### Responsibilities
- Define deployment, observability, reliability, and operational readiness requirements
- Coordinate release plans, environment readiness, and post-deployment verification
- Maintain monitoring, alerting, rollback, and incident-response procedures
- Identify operational risks and communicate mitigations before launch

### Goals
- Release changes safely and predictably
- Protect service reliability and provide clear recovery paths
- Ensure owners can detect and respond to production issues

### Decision / Approval Boundaries
- Set operational readiness evidence and recommend or initiate a deployment pause when safeguards or service health are inadequate
- Does not unilaterally approve product scope or accept business risk; escalates launch trade-offs to the Product Manager and Executive Sponsor / Business Owner
- Follow established incident authority and communicate deployment or rollback decisions promptly

### Typical Communication
- Release checklists, readiness reviews, deployment and monitoring updates, and incident channels
- Coordination with engineering, QA, and project leads before and after release

### Collaboration & Handoffs
- Works with Developers and the Tech Lead / Engineering Lead on deployability, observability, capacity, and rollback; hands off deployment requirements before implementation and operational findings afterward
- Coordinates verification and smoke-test evidence with the QA / Test Engineer
- Confirms launch impact and customer communication needs with the Product Manager
- Aligns release windows, dependencies, and stakeholder updates with the Project Manager
- Escalates material reliability or launch risks to the Executive Sponsor / Business Owner when business decisions are needed

---

## Executive Sponsor / Business Owner

### Role Summary
Executive Sponsors / Business Owners provide strategic direction, secure resources, and make escalated business decisions for an initiative.

### Responsibilities
- Confirm the initiative’s alignment with business goals and expected outcomes
- Provide or secure sponsorship, funding, and organizational support
- Resolve escalated business-level conflicts, constraints, and trade-offs
- Review progress and approve agreed strategic or funding decision gates

### Goals
- Achieve valuable outcomes aligned with organizational strategy
- Ensure the initiative has appropriate authority and resources
- Make timely decisions when trade-offs exceed the delivery team’s mandate

### Decision / Approval Boundaries
- Approve strategic direction, funding, and explicitly assigned business decision gates
- Delegate day-to-day product prioritization to the Product Manager and delivery coordination to the Project Manager
- Does not direct implementation details or override engineering, quality, or operational safeguards; make business-risk decisions transparently with the responsible leads

### Typical Communication
- Milestone and outcome reviews, concise status and escalation briefings, and gate approvals
- Regular alignment with the Product Manager and Project Manager; focused decisions when escalated

### Collaboration & Handoffs
- Aligns outcomes and strategic constraints with the Product Manager, who translates them into product direction and priorities
- Gives the Project Manager timely decisions on escalations, resources, and constraints; receives delivery status and risks
- Reviews technical, quality, design, and operational trade-offs with Developers and the Tech Lead / Engineering Lead, QA / Test Engineer, Design / UX Researcher, and Release / Operations (SRE) Lead as relevant, then returns business decisions to the Product Manager and Project Manager for planning

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
