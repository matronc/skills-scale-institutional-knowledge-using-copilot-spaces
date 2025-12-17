# OctoAcme Role-Responsibility Matrix

## Purpose
This RACI matrix clarifies who is **Responsible**, **Accountable**, **Consulted**, and **Informed** for key project activities. Use this matrix to avoid confusion, ensure clear ownership, and streamline decision-making.

## RACI Legend
- **R (Responsible)**: Performs the work to complete the activity
- **A (Accountable)**: Ultimately answerable for completion and has approval authority; only one A per activity
- **C (Consulted)**: Provides input and expertise; two-way communication
- **I (Informed)**: Kept up to date on progress; one-way communication

---

## Role-Activity Matrix

| Activity | Product Manager | Project Manager | Developers | QA Lead | UX Designer | DevOps Engineer | Scrum Master | Business Analyst | Stakeholder Advocate | Support/On-call | Security Liaison |
|----------|----------------|-----------------|------------|---------|-------------|-----------------|--------------|------------------|---------------------|-----------------|------------------|
| **Initiation** | A | R | C | C | C | I | I | C | C | I | I |
| **Backlog Prioritization** | A | C | C | I | C | I | R | C | C | I | I |
| **Estimation** | C | I | R | C | C | C | A | I | I | I | I |
| **Acceptance Criteria Definition** | A | I | C | C | R | I | I | R | C | I | C |
| **Development** | I | I | A/R | C | C | C | C | I | I | I | C |
| **Testing** | I | I | C | A/R | C | C | I | I | I | I | C |
| **Release Approval** | A | C | I | R | I | R | I | I | C | I | C |
| **Incident Response** | I | C | R | C | I | A/R | I | I | I | R | C |
| **Post-release Retrospective** | C | A | R | R | C | R | R | C | I | C | C |

---

## Activity Details and Examples

### 1. Initiation
**What it is**: Project kickoff, defining objectives, success metrics, and assembling the team.

**Example**:
- **Product Manager (A)**: Owns the project vision and business case
- **Project Manager (R)**: Organizes kickoff meeting, creates project plan
- **Business Analyst (C)**: Provides detailed requirements and process analysis
- **Stakeholder Advocate (C)**: Approves strategic direction and budget

**When to escalate**: If strategic alignment or budget is unclear, escalate to Stakeholder Advocate.

---

### 2. Backlog Prioritization
**What it is**: Ordering work items by business value, dependencies, and risk.

**Example**:
- **Scrum Master (R)**: Facilitates backlog refinement sessions
- **Product Manager (A)**: Makes final prioritization decisions based on value
- **Business Analyst (C)**: Provides business context and requirement clarity
- **Developers (C)**: Provide technical input on dependencies and feasibility

**When to escalate**: If prioritization conflicts arise between teams or stakeholders, escalate to Product Manager or Stakeholder Advocate.

---

### 3. Estimation
**What it is**: Sizing work items (story points, T-shirt sizes, hours) to plan capacity.

**Example**:
- **Developers (R)**: Estimate implementation effort
- **Scrum Master (A)**: Facilitates estimation sessions (e.g., planning poker)
- **QA Lead (C)**: Estimates testing effort
- **DevOps Engineer (C)**: Estimates infrastructure and deployment work

**When to escalate**: If estimates vary widely or uncover significant unknowns, escalate to Project Manager for risk assessment.

---

### 4. Acceptance Criteria Definition
**What it is**: Defining clear, testable conditions for a feature to be considered done.

**Example**:
- **UX Designer (R)**: Defines UX acceptance criteria (e.g., interaction flows, accessibility)
- **Business Analyst (R)**: Defines functional acceptance criteria
- **Product Manager (A)**: Approves final acceptance criteria
- **QA Lead (C)**: Ensures criteria are testable
- **Security Liaison (C)**: Adds security-related acceptance criteria

**When to escalate**: If acceptance criteria are ambiguous or conflicting, escalate to Product Manager.

---

### 5. Development
**What it is**: Writing code, implementing features, and creating unit tests.

**Example**:
- **Developers (A/R)**: Write and test code, submit pull requests
- **UX Designer (C)**: Provides design clarifications and reviews implementation
- **DevOps Engineer (C)**: Supports local dev environment and CI pipeline
- **Security Liaison (C)**: Reviews code for security issues

**When to escalate**: If technical blockers or unclear requirements emerge, escalate to Project Manager or Product Manager.

---

### 6. Testing
**What it is**: Running manual and automated tests to verify acceptance criteria.

**Example**:
- **QA Lead (A/R)**: Coordinates testing efforts, executes test plans, signs off on quality
- **Developers (C)**: Fix bugs and provide clarifications
- **UX Designer (C)**: Validates usability and design implementation
- **Security Liaison (C)**: Validates security controls

**When to escalate**: If critical bugs or test blockers prevent sign-off, escalate to Project Manager and Product Manager.

---

### 7. Release Approval
**What it is**: Final go/no-go decision for deploying to production.

**Example**:
- **Product Manager (A)**: Makes final release decision based on readiness
- **QA Lead (R)**: Provides QA sign-off and quality assessment
- **DevOps Engineer (R)**: Confirms deployment readiness and rollback plan
- **Project Manager (C)**: Provides status and risk assessment
- **Stakeholder Advocate (C)**: Informed of release timing and scope

**When to escalate**: If release readiness is uncertain or risks are high, escalate to Stakeholder Advocate.

---

### 8. Incident Response
**What it is**: Responding to production incidents, mitigating impact, and restoring service.

**Example**:
- **Support/On-call (R)**: Triages incident and coordinates response
- **DevOps Engineer (A/R)**: Investigates infrastructure issues and executes rollback if needed
- **Developers (R)**: Provides hotfixes and technical expertise
- **Project Manager (C)**: Coordinates communication to stakeholders
- **Security Liaison (C)**: Assesses security implications

**When to escalate**: If incident is critical or prolonged, escalate to Project Manager and Product Manager for stakeholder communication.

---

### 9. Post-release Retrospective
**What it is**: Reviewing what went well, what didn't, and defining action items for improvement.

**Example**:
- **Project Manager (A)**: Facilitates retrospective and tracks action items
- **Scrum Master (R)**: Ensures team participation and psychological safety
- **Developers (R)**: Provide technical feedback and improvement ideas
- **QA Lead (R)**: Shares quality insights and testing lessons learned
- **DevOps Engineer (R)**: Reviews deployment and infrastructure issues

**When to escalate**: If systemic issues or process breakdowns are identified, escalate to Stakeholder Advocate or leadership.

---

## Escalation Guidelines

### When to Escalate
- Conflicting priorities or resource constraints
- Unclear accountability or decision-making authority
- Blockers that cannot be resolved at the team level
- Risks that threaten project timeline, scope, or quality
- Scope changes or significant deviations from the plan

### Escalation Path
1. **Level 1 (Team)**: Scrum Master or Project Manager facilitates resolution within the team
2. **Level 2 (Product Lead)**: Product Manager escalates to Product Lead or cross-team coordination
3. **Level 3 (Stakeholder/Sponsor)**: Project Manager escalates to Stakeholder Advocate or executive sponsor for business-impacting decisions

---

## How to Use This Matrix

### For Planning
- Reference this matrix when creating project one-pagers to assign roles and responsibilities
- Use during project initiation to clarify ownership and decision-making authority
- Include in onboarding materials to help new team members understand their role

### For Execution
- Consult when unclear who should own or approve a decision
- Use to resolve conflicts about ownership or accountability
- Reference during retrospectives to identify process gaps

### For Communication
- Identify who should be informed or consulted for each activity
- Ensure appropriate stakeholders are included in decisions
- Reduce over-communication by clarifying I (Informed) vs. C (Consulted)

---

## Maintenance
- Review and update this matrix quarterly or when roles/processes change
- Capture feedback during retrospectives and incorporate improvements
- Ensure new team members are onboarded with the latest version
