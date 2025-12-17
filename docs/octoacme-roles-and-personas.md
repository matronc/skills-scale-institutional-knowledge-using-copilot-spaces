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

## Quality Assurance (QA) Lead

### Role Summary
QA Leads define testing strategy, coordinate manual and automated testing efforts, and ensure quality standards are met before releases. They work closely with developers and product managers to verify acceptance criteria.

### Responsibilities
- Design and maintain test plans and test cases
- Coordinate manual QA and exploratory testing
- Define and track quality metrics and test coverage
- Sign off on releases and feature acceptance
- Identify and triage bugs and regressions
- Champion quality standards and best practices

### Goals
- Ensure high product quality and reliability
- Minimize production defects and customer-impacting issues
- Reduce time to detect and resolve issues

### Typical Communication
- QA status updates in sprint planning and reviews
- Bug reports and regression tracking
- Release sign-off and go/no-go decisions

### Interactions with Core Roles
| Role | Interaction | Handoffs & Decision Points |
|------|-------------|----------------------------|
| Developers | Daily collaboration on feature testing | Developers hand off completed features; QA provides feedback and sign-off |
| Product Manager | Acceptance criteria validation | PM defines criteria; QA verifies they are testable and met |
| Project Manager | Test plan reviews and milestone tracking | PM coordinates timelines; QA provides testing estimates and blockers |

---

## UX Designer

### Role Summary
UX Designers research user needs, create wireframes and prototypes, and ensure the product delivers an intuitive and accessible user experience. They collaborate with product managers and developers to balance user needs with technical constraints.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define interaction patterns and information architecture
- Collaborate with developers on implementation
- Validate designs through user feedback and analytics

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Reduce user friction and support costs
- Ensure design consistency across the product

### Typical Communication
- Design reviews and critique sessions
- User research findings and personas
- Design specs and component documentation

### Interactions with Core Roles
| Role | Interaction | Handoffs & Decision Points |
|------|-------------|----------------------------|
| Product Manager | Requirements gathering and user story refinement | PM shares goals and constraints; Designer proposes solutions |
| Developers | Design implementation and feasibility discussions | Designer hands off specs; Developers flag technical constraints |
| QA Lead | Usability and accessibility testing coordination | Designer defines expected UX; QA validates implementation |

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain CI/CD pipelines, infrastructure, and deployment automation. They enable developers to ship code safely and efficiently while maintaining system reliability and observability.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure as code and cloud resources
- Implement monitoring, logging, and alerting
- Automate deployments and rollback procedures
- Ensure security and compliance in infrastructure
- Support incident response and troubleshooting

### Goals
- Minimize deployment time and manual steps
- Maximize system uptime and reliability
- Improve developer productivity through automation

### Typical Communication
- Infrastructure and deployment status updates
- Incident post-mortems and root cause analysis
- Architecture reviews and capacity planning

### Interactions with Core Roles
| Role | Interaction | Handoffs & Decision Points |
|------|-------------|----------------------------|
| Developers | Pipeline configuration and deployment support | Developers commit code; DevOps ensures CI/CD runs smoothly |
| QA Lead | Test environment provisioning and data management | DevOps provides test environments; QA validates configuration |
| Project Manager | Deployment scheduling and risk assessment | PM coordinates releases; DevOps executes and monitors deployments |

---

## Scrum Master

### Role Summary
Scrum Masters facilitate Scrum ceremonies, remove impediments, and coach the team on agile practices. They ensure the team follows agreed processes and continuously improves delivery efficiency.

### Responsibilities
- Facilitate sprint planning, daily standups, reviews, and retrospectives
- Remove blockers and shield the team from distractions
- Track sprint metrics (velocity, burndown, cycle time)
- Coach team on agile and Scrum best practices
- Foster continuous improvement and team health

### Goals
- Maximize team productivity and flow
- Enable self-organization and accountability
- Continuously improve team processes and collaboration

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective action items and team health metrics
- Blocker escalation and team advocacy

### Interactions with Core Roles
| Role | Interaction | Handoffs & Decision Points |
|------|-------------|----------------------------|
| Developers | Daily check-ins and impediment removal | Developers raise blockers; Scrum Master resolves or escalates |
| Product Manager | Backlog refinement and priority alignment | PM sets priorities; Scrum Master ensures team understanding and capacity |
| Project Manager | Cross-team coordination and dependency tracking | Scrum Master identifies dependencies; PM coordinates resolution |

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams. They gather requirements, analyze processes, and ensure solutions align with business objectives and constraints.

### Responsibilities
- Elicit and document business requirements
- Analyze current processes and identify improvement opportunities
- Create functional specifications and use cases
- Facilitate stakeholder workshops and requirements reviews
- Validate solutions against business needs
- Support user acceptance testing (UAT)

### Goals
- Ensure solutions deliver measurable business value
- Reduce requirement gaps and rework
- Improve stakeholder alignment and satisfaction

### Typical Communication
- Requirements documentation and functional specs
- Stakeholder meetings and requirement reviews
- UAT coordination and sign-off

### Interactions with Core Roles
| Role | Interaction | Handoffs & Decision Points |
|------|-------------|----------------------------|
| Product Manager | Requirements definition and prioritization | BA documents detailed requirements; PM prioritizes based on value |
| Developers | Clarification of functional requirements | BA provides specs; Developers ask questions and propose technical approaches |
| QA Lead | UAT coordination and acceptance criteria validation | BA defines business acceptance; QA validates technical acceptance |

---

## Stakeholder Advocate

### Role Summary
Stakeholder Advocates represent business units, customers, or executive leadership. They ensure the project delivers on strategic goals, provide feedback, and make key go/no-go decisions.

### Responsibilities
- Represent stakeholder interests and requirements
- Provide business context and strategic direction
- Review and approve major milestones and deliverables
- Escalate issues and make trade-off decisions
- Communicate project status to leadership

### Goals
- Ensure alignment with business strategy and goals
- Maximize return on investment (ROI)
- Manage stakeholder expectations and satisfaction

### Typical Communication
- Weekly or bi-weekly status updates
- Milestone reviews and demos
- Executive briefings and steering committee meetings

### Interactions with Core Roles
| Role | Interaction | Handoffs & Decision Points |
|------|-------------|----------------------------|
| Product Manager | Strategic alignment and roadmap reviews | PM proposes roadmap; Stakeholder approves or redirects |
| Project Manager | Status updates and escalation decisions | PM reports status and risks; Stakeholder makes go/no-go decisions |
| Business Analyst | Business requirements validation | BA documents requirements; Stakeholder reviews and approves |

---

## Support/On-call Engineer

### Role Summary
Support and On-call Engineers respond to production incidents, triage customer issues, and provide operational expertise. They ensure system reliability and minimize customer impact during incidents.

### Responsibilities
- Monitor production systems and respond to alerts
- Triage and resolve production incidents
- Escalate complex issues to engineering teams
- Document incident timelines and root causes
- Provide customer support for technical issues
- Contribute to runbooks and incident playbooks

### Goals
- Minimize incident resolution time and customer impact
- Improve system reliability and observability
- Build institutional knowledge through documentation

### Typical Communication
- Incident reports and status updates
- Post-incident reviews and action items
- On-call handoffs and escalation procedures

### Interactions with Core Roles
| Role | Interaction | Handoffs & Decision Points |
|------|-------------|----------------------------|
| Developers | Incident escalation and hotfix coordination | Support triages incidents; Developers provide fixes |
| DevOps Engineer | Infrastructure troubleshooting and monitoring | Support flags infrastructure issues; DevOps investigates and resolves |
| Project Manager | Incident impact assessment and communication | Support provides incident details; PM communicates to stakeholders |

---

## Security Liaison

### Role Summary
Security Liaisons ensure security and compliance requirements are integrated throughout the development lifecycle. They perform threat modeling, security reviews, and coordinate remediation of vulnerabilities.

### Responsibilities
- Conduct threat modeling and security reviews
- Review code and architecture for security vulnerabilities
- Define security requirements and acceptance criteria
- Coordinate security scanning and penetration testing
- Track and prioritize vulnerability remediation
- Ensure compliance with security policies and regulations

### Goals
- Minimize security vulnerabilities and exposure
- Ensure compliance with security standards
- Build security awareness across the team

### Typical Communication
- Security review findings and recommendations
- Vulnerability reports and remediation tracking
- Security training and awareness updates

### Interactions with Core Roles
| Role | Interaction | Handoffs & Decision Points |
|------|-------------|----------------------------|
| Developers | Security requirements and code review | Security defines requirements; Developers implement and request reviews |
| DevOps Engineer | Infrastructure security and secrets management | Security defines policies; DevOps implements controls |
| Product Manager | Security trade-offs and feature prioritization | Security flags risks; PM balances security with other priorities |

---

## How these personas are used

### Purpose
These persona definitions provide a shared vocabulary for:
- **RACI and responsibility mapping**: Clarify who is Responsible, Accountable, Consulted, and Informed for each activity
- **Onboarding**: Help new team members understand role expectations and collaboration patterns
- **Assignment of owners**: Ensure each work item, decision, and deliverable has a clear owner
- **Cross-functional alignment**: Improve handoffs and reduce gaps in communication

### Usage Guidelines
- Reference these personas when creating project one-pagers to define the "Proposed team / roles"
- Use persona definitions to tailor communication (e.g., level of detail, focus areas)
- Leverage these definitions in the [Role-Responsibility Matrix](role-responsibility-matrix.md) to assign RACI for key activities
- Apply personas as prompts for Copilot Spaces to shape role-specific guidance

