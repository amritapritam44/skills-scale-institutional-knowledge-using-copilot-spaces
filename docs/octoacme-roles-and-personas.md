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

## Quality Assurance / Testing Lead

### Role Summary
QA and Testing Leads define quality standards, develop test strategies, and validate that deliverables meet acceptance criteria and performance expectations. They own end-to-end quality assurance across the project lifecycle.

### Responsibilities
- Define Definition of Done criteria and quality standards
- Create and maintain test plans (unit, integration, E2E, security, performance)
- Collaborate on acceptance criteria with Product and Development teams
- Execute testing and validate release readiness
- Track defects and quality metrics
- Identify and escalate quality risks
- Coordinate with Security team for security testing

### Goals
- Ensure zero critical defects reach production
- Reduce cycle time through early quality practices
- Maintain customer confidence through reliable releases

### Typical Communication
- Planning meetings to define test strategy
- Daily standups for blocker identification
- Release gates and deployment checklists
- Metrics and quality dashboards

### Key Interactions
- **With Developers:** Code review for testability, test case collaboration
- **With Product Managers:** Acceptance criteria validation, feature prioritization by risk
- **With Project Managers:** Release readiness assessment, timeline impact of quality issues
- **With Technical Leads:** Complex test strategy and performance validation

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural direction, technical governance, and design reviews. They identify technical risks, propose solutions, and ensure implementation quality and scalability.

### Responsibilities
- Define technical architecture and design standards
- Review designs and code for technical excellence
- Identify technical risks and propose mitigations
- Mentor developers and support knowledge transfer
- Oversee technical dependencies and integration points
- Drive performance, security, and maintainability standards

### Goals
- Deliver technically sound, scalable solutions
- Reduce technical debt and long-term maintenance burden
- Enable rapid iteration through good architecture

### Typical Communication
- Design reviews and technical spike discussions
- Architecture decision records (ADRs)
- Code reviews and design feedback
- Escalation of technical risks

### Key Interactions
- **With Developers:** Technical mentoring, design guidance, code review
- **With Product Managers:** Trade-off discussion (time, scope, quality)
- **With Project Managers:** Technical risk escalation and timeline impact
- **With Security Officer:** Security architecture review

---

## Product Lead

### Role Summary
Product Leads own strategic product direction and serve as the escalation point for Product Managers. They align cross-functional teams, resolve prioritization conflicts, and ensure consistent customer value delivery.

### Responsibilities
- Define product vision and strategy
- Escalate and resolve prioritization conflicts
- Align multiple product initiatives and roadmaps
- Represent product voice in executive forums
- Measure and communicate product outcomes
- Mentor Product Managers

### Goals
- Maximize product-market fit and customer outcomes
- Ensure strategic alignment across initiatives
- Build a sustainable, scalable product organization

### Typical Communication
- Strategic planning and roadmap reviews
- Executive steering committees
- Cross-project alignment meetings
- Quarterly business reviews (QBRs)

### Key Interactions
- **With Product Managers:** Guidance, escalation support, conflict resolution
- **With Project Managers:** Cross-project dependency resolution
- **With Sponsors/Executives:** Business outcomes and strategic alignment
- **With Technical Leads:** Feasibility and trade-off discussion

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors are business owners who approve project initiation, allocate resources, and ensure projects align with business strategy. They escalate blockers and make high-level trade-off decisions.

### Responsibilities
- Approve project charter and business case
- Allocate resources (budget, team, timeline)
- Remove executive-level blockers
- Provide strategic alignment and priority guidance
- Approve releases and go/no-go decisions
- Communicate business outcomes to leadership

### Goals
- Ensure projects deliver business value
- Optimize resource allocation across portfolio
- Reduce time-to-value and business risk

### Typical Communication
- Project approval and initiation gates
- Monthly or quarterly steering reviews
- Escalation of resource or priority conflicts
- Post-release business impact reviews

### Key Interactions
- **With Project Managers:** Status updates, escalation support, resource decisions
- **With Product Leads:** Strategic alignment and portfolio prioritization
- **With Developers/Technical Leads:** Release approval and go/no-go decisions

---

## Security & Compliance Officer

### Role Summary
Security Officers define security requirements, perform threat assessments, and ensure compliance throughout the project lifecycle. They are critical escalation points for security and compliance risks.

### Responsibilities
- Define security and compliance requirements
- Perform threat modeling and risk assessments
- Review designs and code for security vulnerabilities
- Configure and oversee security scanning in CI/CD
- Coordinate incident response for security issues
- Maintain compliance documentation and audit trails
- Escalate critical security risks

### Goals
- Prevent security breaches and data loss
- Maintain compliance with regulatory standards
- Build security-first culture

### Typical Communication
- Security requirement workshops
- Design and code security reviews
- Risk registers and threat assessments
- Incident response coordination
- Compliance audits and reporting

### Key Interactions
- **With Developers:** Security best practices, vulnerability remediation
- **With QA/Testing Lead:** Security testing strategy and validation
- **With Technical Leads:** Secure architecture design
- **With Project Managers:** Security risk escalation and timeline impact

---

## Scrum Master / Delivery Coordinator

### Role Summary
Scrum Masters (or Delivery Coordinators in non-Agile contexts) facilitate team ceremonies, remove process blockers, and maintain team velocity. They coach the team on process adherence and continuous improvement.

### Responsibilities
- Facilitate stand-ups, planning, and retrospectives
- Identify and remove process blockers
- Track team velocity and burndown
- Coach team on process and best practices
- Manage project board and workflow
- Escalate dependency and resource conflicts
- Maintain team morale and psychological safety

### Goals
- Maintain consistent team velocity
- Reduce process friction and wasted effort
- Foster continuous improvement mindset

### Typical Communication
- Daily standups and ceremony facilitation
- Retrospectives and action item tracking
- Escalation of team blockers
- Metrics and velocity reporting

### Key Interactions
- **With All Team Members:** Ceremony facilitation and process coaching
- **With Project Manager:** Dependency and resource escalation
- **With Product Manager:** Backlog refinement and prioritization support

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
