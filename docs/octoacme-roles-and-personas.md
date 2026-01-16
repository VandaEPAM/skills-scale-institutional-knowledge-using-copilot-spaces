# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

> **Note**: This document was expanded based on [issue #4](https://github.com/VandaEPAM/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) to address gaps in role clarity and cross-functional collaboration patterns.

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

### Collaboration with Other Roles
- **QA/Testing Engineers**: Review test coverage, pair on testing complex scenarios, fix bugs with proper reproduction steps
- **DevOps Engineers**: Coordinate on CI/CD pipeline optimization, deployment configurations, and troubleshooting
- **UX Designers**: Implement design specifications, provide technical feasibility feedback, review UI implementations
- **Product Managers**: Clarify requirements, propose technical solutions, provide implementation estimates

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

### Collaboration with Other Roles
- **Business Analysts**: Translate detailed requirements into product strategy, validate business assumptions
- **UX Designers**: Align on user needs and experience strategy, prioritize design debt
- **Customer Success**: Review customer feedback, prioritize feature requests, validate solutions address customer needs
- **Developers**: Balance feature scope with technical complexity, clarify acceptance criteria

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

### Collaboration with Other Roles
- **All Team Members**: Facilitate planning sessions, track progress, escalate blockers
- **Business Analysts**: Coordinate requirements gathering, manage scope changes
- **DevOps Engineers**: Coordinate release planning, track infrastructure dependencies
- **Product Managers**: Align on priorities, report project status, manage stakeholder expectations

---

## QA/Testing Engineers

### Role Summary
QA/Testing Engineers ensure software quality through systematic testing, validation, and quality assurance practices. They collaborate with developers and product managers to verify acceptance criteria and prevent defects from reaching production.

### Responsibilities
- Design and execute test plans (unit, integration, end-to-end)
- Validate features against acceptance criteria
- Identify, document, and track defects
- Maintain test automation frameworks and CI integration
- Provide quality metrics and test coverage reports
- Participate in sprint planning to understand testability requirements
- Conduct exploratory testing for edge cases

### Goals
- Ensure high product quality and reliability
- Catch defects early in the development cycle
- Maintain comprehensive test coverage
- Reduce production incidents through thorough validation

### Typical Communication
- Daily standups to report testing status and blockers
- PR reviews focusing on testability and test coverage
- Bug reports with reproduction steps and severity assessment
- Test summary reports at sprint/release milestones

### Collaboration with Other Roles
- **Developers**: Review test coverage, pair on complex test scenarios, clarify reproduction steps for bugs
- **Product Managers**: Validate acceptance criteria are testable, provide feedback on user experience issues
- **Project Managers**: Report testing progress, flag quality risks, estimate testing effort
- **DevOps Engineers**: Coordinate test environment setup, integrate automated tests into CI/CD pipelines

---

## UX Designers

### Role Summary
UX Designers create intuitive, user-centered experiences by conducting research, designing interfaces, and validating solutions with users. They ensure products are usable, accessible, and aligned with user needs.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and visual designs
- Define user flows and interaction patterns
- Ensure accessibility standards (WCAG) compliance
- Collaborate on design systems and component libraries
- Validate designs through user feedback and analytics
- Document design specifications and guidelines

### Goals
- Optimize user satisfaction and task completion rates
- Ensure consistent, accessible user experiences
- Reduce user friction and support burden
- Advocate for user needs in product decisions

### Typical Communication
- Design reviews and critique sessions
- User research findings and personas
- Prototype demos and usability test results
- Design specifications in Figma or similar tools

### Collaboration with Other Roles
- **Product Managers**: Align design solutions with product strategy, validate user needs and priorities
- **Developers**: Provide design specs, clarify implementation details, review UI implementation
- **Business Analysts**: Share user research insights, validate requirements against user needs
- **Customer Success**: Gather user feedback, understand pain points and feature requests

---

## DevOps Engineers

### Role Summary
DevOps Engineers build and maintain infrastructure, CI/CD pipelines, and deployment automation. They enable teams to deliver software reliably, securely, and efficiently.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage cloud infrastructure and container orchestration
- Implement monitoring, logging, and alerting systems
- Automate deployment and rollback procedures
- Ensure security best practices in infrastructure and pipelines
- Optimize build times and resource utilization
- Support incident response and troubleshooting

### Goals
- Minimize deployment time and risk
- Ensure high availability and system reliability
- Automate repetitive operational tasks
- Provide visibility into system health and performance

### Typical Communication
- Infrastructure design docs and runbooks
- Deployment notifications and release coordination
- Incident postmortems and root cause analysis
- Capacity planning and performance reports

### Collaboration with Other Roles
- **Developers**: Optimize build configurations, troubleshoot deployment issues, provide local development environments
- **QA/Testing Engineers**: Set up test environments, integrate automated tests into CI/CD
- **Project Managers**: Report on deployment readiness, estimate infrastructure work, flag capacity constraints
- **Product Managers**: Provide production metrics and system performance data

---

## Business Analysts

### Role Summary
Business Analysts bridge business stakeholders and delivery teams by gathering requirements, analyzing processes, and ensuring solutions deliver measurable business value.

### Responsibilities
- Elicit and document business requirements
- Analyze current processes and identify improvement opportunities
- Define success metrics and KPIs
- Create functional specifications and user stories
- Facilitate workshops with stakeholders
- Validate that delivered solutions meet business needs
- Maintain requirements traceability

### Goals
- Ensure solutions align with business objectives
- Reduce ambiguity in requirements
- Maximize ROI on project investments
- Enable data-driven decision making

### Typical Communication
- Requirements documents and user stories
- Process flow diagrams and data models
- Stakeholder interviews and workshop facilitation
- Business case presentations and ROI analysis

### Collaboration with Other Roles
- **Product Managers**: Translate business strategy into detailed requirements, validate market assumptions
- **Project Managers**: Provide requirements clarity, estimate analysis effort, track scope changes
- **Developers**: Clarify functional requirements, answer business logic questions, validate implementation
- **UX Designers**: Share user research, ensure designs meet business constraints

---

## Customer Success / Support Engineers

### Role Summary
Customer Success and Support Engineers ensure customers achieve their desired outcomes with the product. They provide assistance, gather feedback, and advocate for customer needs in product development.

### Responsibilities
- Respond to customer inquiries and technical issues
- Document and escalate bugs and feature requests
- Create customer-facing documentation and knowledge base articles
- Conduct customer onboarding and training
- Monitor customer health metrics and identify at-risk accounts
- Gather product feedback and usage patterns
- Serve as customer advocate in product planning

### Goals
- Maximize customer satisfaction and retention
- Reduce time to resolution for customer issues
- Identify product improvements from customer feedback
- Enable customer self-service through documentation

### Typical Communication
- Support tickets and issue escalations
- Customer feedback summaries and feature requests
- Knowledge base articles and FAQ updates
- Customer health reports and churn risk analysis

### Collaboration with Other Roles
- **Product Managers**: Share customer feedback, validate feature priorities, report on adoption patterns
- **Developers**: Escalate bugs with reproduction steps, provide customer context for technical decisions
- **UX Designers**: Report usability issues and user pain points from support interactions
- **QA/Testing Engineers**: Validate fixes in customer-reported scenarios

---

## Role Interaction Matrix

This matrix shows key collaboration touchpoints between roles:

| Role | Primary Collaborators | Key Interactions |
|------|----------------------|------------------|
| **Developer** | PM, QA, DevOps, UX | Code reviews, technical design, implementation questions |
| **Product Manager** | Project Manager, Business Analyst, UX, Customer Success | Requirements, prioritization, roadmap, customer feedback |
| **Project Manager** | All roles | Planning, status tracking, risk management, facilitation |
| **QA/Testing Engineer** | Developer, DevOps, PM | Test planning, bug tracking, quality gates |
| **UX Designer** | Product Manager, Developer, Business Analyst | Design reviews, usability research, implementation validation |
| **DevOps Engineer** | Developer, QA, Project Manager | Infrastructure, deployments, CI/CD, monitoring |
| **Business Analyst** | Product Manager, Developer, UX | Requirements clarification, process analysis, validation |
| **Customer Success** | Product Manager, UX, QA | Feedback gathering, issue escalation, feature validation |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The expanded persona set enables more realistic cross-functional project simulations.
- Role interaction patterns help clarify communication responsibilities and escalation paths.

