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

### Key Interactions
- **With QA/Testing**: Provides build artifacts, reviews test results, fixes defects
- **With UX Designer**: Receives design specs, provides feasibility feedback, coordinates handoff
- **With DevOps Engineer**: Coordinates CI/CD pipeline setup, deployment strategy
- **With Product Manager**: Clarifies requirements, participates in acceptance criteria definition

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

### Key Interactions
- **With Project Manager**: Aligns on scope, timeline, and stakeholder priorities
- **With UX Designer**: Collaborates on user research, validates design direction
- **With Business Analyst**: Reviews requirements documentation, validates traceability
- **With Developers**: Defines acceptance criteria, reviews implementation

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

### Key Interactions
- **With Product Manager**: Coordinates delivery roadmap, manages scope/timeline trade-offs
- **With Scrum Master**: Collaborates on team rhythm and ceremony scheduling (if applicable)
- **With Business Analyst**: Ensures requirements are properly documented and tracked
- **With Developers/QA**: Tracks progress, removes blockers, manages dependencies

---

## Scrum Master

### Role Summary
Scrum Masters facilitate Agile ceremonies, remove impediments, and coach teams on continuous improvement practices. They enable teams to maintain a healthy, predictable delivery rhythm while supporting collaboration with Project and Product Managers.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove impediments and blockers that prevent team progress
- Coach the team on Agile principles and practices
- Track sprint metrics (velocity, burn-down) and identify process improvements
- Support cross-team communication and dependency management
- Escalate systemic issues affecting team performance

### Goals
- Maximize team velocity and consistency
- Foster a culture of continuous improvement
- Reduce cycle time and unplanned disruptions
- Enable autonomy and psychological safety within the team

### Typical Communication
- Daily ceremonies with delivery team
- Weekly sync with Project Manager on team health
- Monthly metrics review with stakeholders
- Ongoing coaching and one-on-ones as needed

### Key Interactions
- **With Project Manager**: Provides team health metrics, surfaces capacity constraints
- **With Developers/QA**: Removes technical and process blockers, coaches on best practices
- **With Product Manager**: Advocates for team sustainability over rushed delivery
- **With Business Analyst**: Coordinates requirement clarity and definition refinement

---

## UX Designer

### Role Summary
UX Designers design user interfaces and user journeys, conduct user research, and ensure usability best practices. They collaborate closely with Product Managers for requirements and with Developers for implementation handoff.

### Responsibilities
- Conduct user research and usability testing to inform design decisions
- Create wireframes, prototypes, and high-fidelity designs
- Define user journeys and experience flows
- Establish design standards and component libraries
- Review implementation against design specifications
- Participate in design reviews and gather feedback iteratively

### Goals
- Deliver intuitive, accessible user experiences
- Reduce support burden through thoughtful design
- Validate design decisions with user research
- Maintain consistency across the product

### Typical Communication
- Design reviews with Product Manager and Developers
- User research findings and insights documentation
- Design specification handoff documents
- Feedback and iteration cycles

### Key Interactions
- **With Product Manager**: Collaborates on user research, validates design direction against goals
- **With Developers**: Provides design specs and assets, reviews implementation fidelity, iterates
- **With QA/Testing**: Provides acceptance criteria for UI/UX validation
- **With Business Analyst**: Reviews user requirements for design feasibility

---

## DevOps Engineer

### Role Summary
DevOps Engineers manage build, deployment, and infrastructure automation. They partner with Developers and QA to streamline CI/CD processes, ensure system reliability, and enable consistent environments across development, staging, and production.

### Responsibilities
- Design and maintain CI/CD pipelines
- Automate build, test, and deployment processes
- Manage infrastructure as code (IaC) for consistency
- Monitor system performance and reliability
- Coordinate safe, repeatable releases
- Support incident response and rollback procedures

### Goals
- Reduce time-to-market through automation
- Minimize human error in deployments
- Ensure high system availability and performance
- Enable teams to self-serve infrastructure needs safely

### Typical Communication
- CI/CD pipeline configuration and optimization with Developers
- Infrastructure and deployment requirements documentation
- Incident response and escalation communications
- Performance and reliability metrics reviews

### Key Interactions
- **With Developers**: Collaborates on build requirements, optimizes pipeline performance
- **With QA/Testing**: Provides test environments, coordinates testing infrastructure
- **With Project Manager**: Communicates deployment windows and infrastructure readiness
- **With Release/Ops Team**: Coordinates production deployments and monitoring

---

## Business Analyst

### Role Summary
Business Analysts bridge stakeholders and delivery teams by analyzing requirements, documenting needs, and enabling traceability from business objectives through delivery. They support Product Management in outcome measurement and help drive requirements clarity.

### Responsibilities
- Gather and document business requirements from stakeholders
- Create clear, testable requirement specifications
- Establish traceability matrices between requirements, design, and test cases
- Validate solutions meet business objectives
- Support product outcome measurement and metrics
- Facilitate requirements review and sign-off

### Goals
- Ensure shared understanding of what needs to be built
- Reduce rework due to unclear or missed requirements
- Enable measurable validation of delivery outcomes
- Support continuous product improvement through outcome tracking

### Typical Communication
- Requirements documentation and specifications
- Stakeholder interviews and analysis summaries
- Traceability matrices and coverage reports
- Outcome measurement and validation reports

### Key Interactions
- **With Product Manager**: Translates market/business strategy into detailed requirements
- **With Project Manager**: Tracks requirement status and ensures documentation currency
- **With Developers/QA**: Clarifies requirements, supports test case development
- **With Stakeholders**: Gathers inputs, validates understanding, enables sign-off

---

## Role Interaction Matrix

| Phase | PM | PdM | Developer | QA | Scrum Master | UX Designer | DevOps | Business Analyst |
|-------|----|----|-----------|-----|---|---|---|---|
| **Initiation** | Lead charter | Defines success metrics | Input | Input | N/A | Feasibility | N/A | Validates requirements |
| **Planning** | Creates plan | Prioritizes backlog | Estimates | Input | Facilitates ceremonies | Designs flow | Prepares infra | Documents requirements |
| **Execution** | Tracks progress | Refines backlog | Implements | Validates | Removes blockers | Iterates design | Optimizes CI/CD | Clarifies specs |
| **Release** | Manages timeline | Validates MVP | Delivers code | Signs off | Communicates | Final design QA | Executes deploy | Validates outcomes |
| **Retrospective** | Facilitates | Analyzes metrics | Provides input | Reviews quality | Leads process review | Gathers feedback | Shares reliability metrics | Validates measurement |

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the **Role Interaction Matrix** when planning cross-functional work to ensure all stakeholders are engaged at the right time.
- During onboarding, share the relevant persona section with new team members to clarify their responsibilities and key interactions.
