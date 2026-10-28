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

## Engineering Manager

### Role Summary
Engineering Managers support team capacity, engineering health, and sustainable delivery. They help teams resolve dependencies and technical risks without replacing product prioritization or project coordination.

### Responsibilities
- Plan staffing and capacity with delivery needs in mind
- Coach Developers and support engineering quality standards
- Monitor delivery health and help remove execution blockers
- Support dependency resolution and technical risk mitigation

### Goals
- Build a healthy team with sustainable delivery capacity
- Reduce blockers and unplanned delivery risks
- Maintain engineering quality while meeting commitments

### Typical Communication
- Capacity planning and delivery health reviews
- Coaching conversations and engineering team syncs
- Dependency escalations and risk updates

### Interactions with Existing Roles
- Developers: provide coaching, resolve staffing constraints, and help remove blockers
- Product Managers: discuss feasibility and capacity to inform scope trade-offs
- Project Managers: align resource availability, dependencies, and timeline risks

---

## Tech Lead / Staff Engineer

### Role Summary
Tech Leads / Staff Engineers guide technical direction and architecture. They translate product outcomes into implementation approaches and align the team on technical decisions.

### Responsibilities
- Lead architecture decisions and document technical trade-offs
- Define implementation standards and guide design reviews
- Address performance, security, and reliability requirements
- Identify technical dependencies and advise on work sequencing

### Goals
- Deliver coherent, maintainable technical solutions
- Surface technical constraints early
- Reduce implementation risk and avoid unnecessary rework

### Typical Communication
- Technical design docs and architecture decision records
- Design reviews, code reviews, and engineering syncs
- Planning discussions on estimates and technical dependencies

### Interactions with Existing Roles
- Developers: align on designs, mentor implementation, and review technical approaches
- Product Managers: explain feasibility and technical trade-offs while preserving product ownership of priorities
- Project Managers: advise on sequencing, estimates, and technical risks affecting milestones

---

## UX Designer / Researcher

### Role Summary
UX Designers / Researchers investigate user needs and shape usable experiences. They validate proposed solutions and make design intent clear to the delivery team.

### Responsibilities
- Conduct user research and synthesize findings
- Create user flows, prototypes, and interaction designs
- Validate usability and accessibility with users and QA/Testing
- Contribute design inputs to acceptance criteria and review implementation fidelity

### Goals
- Ensure solutions address real user needs
- Improve usability and accessibility
- Reduce uncertainty and design rework before implementation

### Typical Communication
- Research readouts and usability findings
- Design critiques and annotated prototypes
- Design handoffs and implementation reviews

### Interactions with Existing Roles
- Developers: clarify design behavior, discuss feasibility, and review implementation fidelity
- Product Managers: validate user value and inform acceptance criteria and product priorities
- Project Managers: coordinate research, design handoffs, and validation milestones

---

## DevOps / SRE

### Role Summary
DevOps / SRE specialists support reliable delivery pipelines and production operations. They help teams prepare for deployments, observe service health, and respond to incidents.

### Responsibilities
- Maintain CI/CD reliability and deployment automation
- Define observability baselines and operability requirements with Developers and technical leads
- Validate deployment readiness, rollback plans, and incident procedures
- Support incident response and track reliability improvements

### Goals
- Enable safe, repeatable deployments
- Improve service reliability and recovery time
- Surface operational risks before release

### Typical Communication
- Production-readiness reviews and deployment updates
- Operational dashboards, alerts, and runbooks
- Incident coordination and post-incident reviews

### Interactions with Existing Roles
- Developers: collaborate on instrumentation, deployment checks, and operational fixes
- Product Managers: explain reliability impacts and inform prioritization of operational work
- Project Managers: communicate release risks, deployment dependencies, and readiness status

---

## Security / Compliance Representative

### Role Summary
Security / Compliance Representatives guide teams on security risks and applicable control requirements. They support informed risk decisions and help teams build security into design and delivery.

### Responsibilities
- Assess threats, security risks, and applicable compliance requirements
- Contribute security requirements and review secure designs with technical leads
- Verify release controls and evidence with DevOps / SRE
- Guide incident coordination and escalate unresolved risks to designated approvers

### Goals
- Identify and mitigate security risks early
- Make control requirements and evidence expectations clear
- Ensure risk acceptance follows documented approval paths

### Typical Communication
- Threat assessments and security design reviews
- Control checklists, evidence reviews, and risk registers
- Security escalation and incident guidance

### Interactions with Existing Roles
- Developers: clarify secure implementation requirements and review remediation evidence
- Product Managers: explain security impacts and required controls to inform scope and priority decisions
- Project Managers: coordinate reviews, track mitigations, and route risk acceptance to designated approvers

---

## Customer Support / Success Liaison

### Role Summary
Customer Support / Success Liaisons bring customer feedback and support needs into delivery planning. They help teams prepare customers and support staff for release changes.

### Responsibilities
- Share voice-of-customer insights and recurring pain points
- Describe customer impact during incidents and track known issues
- Prepare support enablement and customer-facing release guidance
- Feed support trends and release feedback into retrospectives

### Goals
- Keep customer needs visible throughout delivery
- Improve support readiness and release communication
- Reduce recurring customer friction and support escalations

### Typical Communication
- Customer feedback summaries and support trend reports
- Release briefings, enablement materials, and known-issues updates
- Incident impact updates and retrospective inputs

### Interactions with Existing Roles
- Developers: provide reproducible issue details and validate workarounds and technical explanations
- Product Managers: share customer impact and recurring needs to inform backlog prioritization
- Project Managers: coordinate support handoffs, release messaging, and customer-impact escalations

---

## Role Handoffs and Decision Boundaries

Product Managers retain product prioritization, Project Managers coordinate delivery, and Developers own implementation. New roles provide specialist direction and evidence within these boundaries.

| Role | Key handoff to existing roles | Decision boundary |
| --- | --- | --- |
| Engineering Manager | Capacity and blocker updates to Developers and Project Managers; scope constraints to Product Managers | Owns staffing and coaching; does not replace product prioritization or project scheduling |
| Tech Lead / Staff Engineer | Technical approach to Developers; feasibility and sequencing advice to Product and Project Managers | Guides architecture and technical standards; product scope trade-offs remain with Product Managers |
| UX Designer / Researcher | Designs and research findings to Developers; user-value evidence to Product Managers; design dependencies to Project Managers | Guides design and usability validation; Product Managers prioritize resulting work |
| DevOps / SRE | Operability requirements to Developers; reliability impacts to Product Managers; readiness evidence to Project Managers | Guides operational readiness and incident response; follows agreed release and escalation procedures |
| Security / Compliance Representative | Security requirements to Developers; control impacts to Product Managers; risk and review status to Project Managers | Assesses controls and recommends mitigations; designated approvers accept residual risk |
| Customer Support / Success Liaison | Issue details to Developers; customer insights to Product Managers; support readiness to Project Managers | Owns support feedback and enablement inputs; Product Managers prioritize fixes and Project Managers coordinate release communications |

---

## Examples of Lifecycle Engagement

| Role | Initiation | Planning | Execution | Release | Retrospective |
| --- | --- | --- | --- | --- | --- |
| Engineering Manager | Assess team capacity | Align staffing and dependencies | Remove blockers and coach delivery | Confirm engineering support coverage | Identify team health improvements |
| Tech Lead / Staff Engineer | Identify technical constraints | Define architecture and sequencing | Guide implementation and reviews | Review technical readiness | Propose technical debt improvements |
| UX Designer / Researcher | Research user needs | Validate flows and prototypes | Review designs with Developers | Check experience against design criteria | Share usability findings |
| DevOps / SRE | Identify operational needs | Plan pipelines and observability | Validate automation and runbooks | Support deployment, monitoring, and rollback | Review incidents and reliability trends |
| Security / Compliance Representative | Identify applicable controls | Assess threats and plan reviews | Review mitigations and evidence | Verify controls and escalate unresolved risks | Improve security review practices |
| Customer Support / Success Liaison | Share customer pain points | Identify support and enablement needs | Track known issues and customer feedback | Brief support teams and validate messaging | Share recurring issues and release feedback |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
