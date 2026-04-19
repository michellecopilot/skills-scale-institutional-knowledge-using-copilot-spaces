# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation – your hub for best practices, templates, and process documents that guide how we run projects at OctoAcme..

## What You'll Find Here

- Overview of our approach  
- End-to-end process documents: initiation, planning, execution, risk, release, retros, roles  
- Templates and checklists to streamline delivery

## Project Management Practices at OctoAcme

OctoAcme follows a structured project lifecycle: **Initiation**, **Planning**, **Execution**, **Release**, and **Close & Retrospective**. The Initiation phase validates business need through a lightweight Project One-pager that captures the problem statement, objectives, success metrics, stakeholders, and initial risk assessment. Once stakeholders approve the initiative, the Planning phase breaks work into shippable increments with prioritized backlogs, clear acceptance criteria, and a Definition of Done. During Execution, teams operate on a predictable rhythm of daily standups (15 min), weekly delivery syncs, and sprint-based iterations using a project board with columns: Backlog, Ready, In Progress, In Review, QA, and Done. Pull requests are kept small (≤400 lines), require at least one approval, and must pass automated tests and security scanning before merging.

OctoAcme defines clear role ownership with a Project Manager coordinating delivery and schedules, a Product Manager owning outcomes and prioritization, Developers implementing features collaboratively, QA/Testing validating quality, and designated Stakeholders providing inputs and approvals. Communication is structured through weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, and monthly stakeholder updates. The team employs a three-level escalation path for blockers: team-level triage in standups, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. All key artifacts—Project Charter, Risk Register, Release Plan, and Retrospective notes—are maintained in the project repository to ensure transparency and single-source-of-truth documentation.

Quality is enforced through unit tests for new logic, integration tests where applicable, end-to-end smoke tests before release, and security scanning in CI pipelines. Risk management is proactive, with a Risk Register maintained throughout the project lifecycle capturing ID, description, impact, likelihood, owner, and mitigation plans—reviewed weekly during syncs. After each sprint, release, or milestone, OctoAcme conducts retrospectives to capture learnings and convert them into action items with clear owners and timelines. Success is measured through velocity tracking, burndown monitoring, and dashboards tracking key signals like errors, latency, and usage. This culture of continuous improvement, paired with psychological safety and data-informed decision-making, enables OctoAcme teams to iterate efficiently while maintaining predictable delivery and institutional knowledge.

## 📚 Process Docs Index

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning Guide](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)
