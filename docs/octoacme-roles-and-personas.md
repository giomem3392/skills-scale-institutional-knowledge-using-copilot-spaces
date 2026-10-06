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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality assurance strategy, test planning, and acceptance validation. They ensure features meet acceptance criteria and quality standards before release.

### Responsibilities
- Develop and maintain test plans aligned with release schedules
- Define QA acceptance criteria in collaboration with Product Managers and Developers
- Execute manual and automated testing; manage test environments
- Identify and triage defects with severity and priority
- Validate security and performance requirements
- Conduct smoke tests before production deployments
- Collaborate with Release Managers on pre-release verification

### Goals
- Ensure zero critical defects in production releases
- Reduce cycle time through efficient test automation
- Provide clear quality signals to stakeholders and decision-makers

### Interaction with Existing Roles
- Works closely with **Developers** during sprint planning to align on test coverage and acceptance criteria
- Coordinates with **Product Managers** to validate that features meet business requirements
- Partners with **Project Managers** to ensure QA is on the critical path and risks are flagged early
- Collaborates with **Security Lead** on security validation and compliance testing

### Typical Communication
- Sprint planning and backlog refinement
- Defect triage and bug reports
- Pre-release QA sign-off
- Post-incident root cause analysis

---

## Technical Lead/Architect

### Role Summary
Technical Leads guide technical decisions, design approaches, and architecture to ensure solutions are scalable, maintainable, and aligned with long-term vision.

### Responsibilities
- Participate in design reviews and architecture decisions
- Identify technical risks and propose mitigations
- Mentor developers and provide technical guidance
- Ensure code quality standards and architectural consistency
- Assess scalability, performance, and security implications
- Work with DevOps/Platform Engineers on infrastructure requirements

### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and prevent architectural drift
- Build team capability and knowledge sharing

### Interaction with Existing Roles
- Guides **Developers** through design reviews and technical mentoring
- Advises **Product Managers** on technical feasibility and trade-offs
- Escalates technical risks and timeline impacts to **Project Managers**
- Collaborates with **Security Lead** on threat modeling and secure design

### Typical Communication
- Technical design discussions and code reviews
- Architecture decision records (ADRs)
- Escalation of technical risks
- Technical mentoring sessions

---

## Design/UX Lead

### Role Summary
Design/UX Leads ensure customer-centric design and usability across features. They translate customer needs into intuitive, accessible user experiences.

### Responsibilities
- Conduct user research and gather usability requirements
- Create wireframes, prototypes, and design specifications
- Ensure consistency across product interfaces and experiences
- Validate designs through user testing and iteration
- Define accessibility standards and inclusivity requirements
- Work with Developers to review implementation against design specifications

### Goals
- Deliver intuitive, user-friendly interfaces
- Maximize customer satisfaction and adoption
- Ensure accessible design for all users

### Interaction with Existing Roles
- Collaborates with **Product Managers** to understand user needs and priorities
- Partners with **Developers** during implementation to ensure design fidelity
- Works with **QA/Testing Lead** to include usability in acceptance criteria
- Advises **Project Managers** on design-related timeline impacts

### Typical Communication
- Design reviews and usability testing sessions
- Design specifications and component libraries
- Feedback from user research and user testing
- Design iterations based on QA and developer feedback

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors are business owners, decision makers, and funding authorities. They set business priorities, approve budgets, and ensure projects align with organizational goals.

### Responsibilities
- Define business objectives and success metrics
- Approve project initiation and resource allocation
- Make key decisions on scope, priorities, and trade-offs
- Provide oversight and governance
- Communicate project status to executive leadership
- Support escalations and remove blockers

### Goals
- Ensure projects deliver measurable business value
- Maintain alignment with organizational strategy
- Manage stakeholder expectations and communications

### Interaction with Existing Roles
- Receives project updates and status from **Project Managers**
- Reviews success metrics and outcomes with **Product Managers**
- Approves major decisions and resource requests
- Escalates issues and strategic concerns as needed

### Typical Communication
- Monthly stakeholder updates and business reviews
- Approval gate meetings
- Executive briefings and decision forums
- Ad-hoc escalations on blockers or strategic changes

---

## DevOps/Platform Engineer

### Role Summary
DevOps/Platform Engineers manage infrastructure, deployment pipelines, and production readiness. They ensure systems are reliable, scalable, and secure.

### Responsibilities
- Design and maintain deployment pipelines and infrastructure as code
- Manage CI/CD configuration and automation
- Ensure production readiness and deployment safety
- Monitor system performance, reliability, and security
- Support incident response and troubleshooting
- Collaborate with developers on deployment requirements and best practices

### Goals
- Enable fast, reliable deployments to production
- Maintain high system uptime and performance
- Automate operational tasks and reduce manual work

### Interaction with Existing Roles
- Works with **Developers** on deployment requirements and infrastructure needs
- Supports **Release Managers** with deployment execution and rollback procedures
- Advises **Technical Leads** on scalability and infrastructure decisions
- Collaborates with **Security Lead** on compliance and infrastructure security

### Typical Communication
- Release planning and deployment coordination
- Infrastructure and deployment pipeline design reviews
- Incident response and post-incident reviews
- Monitoring dashboards and alerting

---

## Security Lead

### Role Summary
Security Leads manage security requirements, threat assessment, and compliance to protect systems and data.

### Responsibilities
- Define security requirements and acceptance criteria
- Conduct threat assessments for new features
- Review code for security vulnerabilities
- Ensure compliance with relevant standards and regulations
- Participate in security scanning and incident response
- Maintain security policies and guidelines
- Work with DevOps on infrastructure and deployment security

### Goals
- Prevent security breaches and data exposure
- Embed security into the development lifecycle
- Maintain compliance and regulatory alignment

### Interaction with Existing Roles
- Defines security acceptance criteria with **Product Managers** and **QA/Testing Lead**
- Partners with **Developers** on secure coding practices and code reviews
- Advises **Technical Leads** on threat modeling and secure architecture
- Collaborates with **DevOps/Platform Engineers** on infrastructure security
- Reports compliance status and risks to **Project Managers** and **Stakeholders**

### Typical Communication
- Security review gates in the release process
- Threat assessment reports and security advisories
- Security incident playbooks
- Post-incident blameless retrospectives
- Compliance and audit reports

---

## Release Manager

### Role Summary
Release Managers coordinate release planning, deployment scheduling, and post-release verification. They ensure smooth, predictable transitions to production.

### Responsibilities
- Create and maintain release plans and schedules
- Coordinate pre-release activities and sign-offs
- Manage release communications to stakeholders
- Execute or oversee deployments with DevOps/Platform Engineers
- Conduct post-release verification and smoke testing
- Manage rollback procedures if issues arise
- Document release notes and deployment artifacts

### Goals
- Execute on-time, low-risk releases
- Minimize disruption and production incidents
- Maintain clear communication with all stakeholders

### Interaction with Existing Roles
- Coordinates with **Project Managers** on release scheduling and milestone alignment
- Works with **QA/Testing Lead** to ensure all acceptance criteria are met before release
- Partners with **DevOps/Platform Engineers** on deployment execution
- Gets sign-off from **Product Managers** on release readiness
- Reports status and risks to **Stakeholders** and **Project Managers**

### Typical Communication
- Release planning meetings and status updates
- Pre-release checklists and sign-off gates
- Deployment coordination and rollout communications
- Post-release retrospectives

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understanding the interactions between personas helps teams identify dependencies, communication patterns, and accountability.
