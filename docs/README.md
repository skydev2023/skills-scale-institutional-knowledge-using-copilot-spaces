# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management documentation hub. This README is your starting point for understanding how projects are initiated, planned, delivered, released, and continuously improved across the team.

OctoAcme follows a structured, lifecycle-based project management approach that spans five phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. Every project begins with a lightweight one-pager that captures the problem statement, SMART goals, success metrics, and stakeholder alignment before any planning work begins. A formal decision gate ensures that projects only move forward when success metrics are clear, stakeholders agree on priority, and team availability is confirmed. This prevents premature investment in poorly-scoped initiatives and keeps the team focused on high-value work.

The team is organized around clearly defined **personas and roles** — Project Managers (PMs) who coordinate delivery, schedules, and risk; Product Managers (PdMs) who own the product vision and backlog prioritization; Developers who implement and test features; QA engineers who validate acceptance criteria; and Stakeholders who provide inputs and approvals. Communication follows a consistent cadence: daily standups for the delivery team, weekly PM–PdM syncs, monthly stakeholder updates, and ad-hoc escalations when needed. Risks are tracked in a living Risk Register with defined escalation paths moving from team-level triage → PM → Product Lead → Sponsor.

During **execution**, OctoAcme uses GitHub Projects boards (Backlog → Ready → In Progress → In Review → QA → Done) to manage workflow visibility. Pull Requests are kept small (≤ 400 lines when possible), must include issue links and acceptance criteria, and require CI checks (tests, linting, security scans) to pass before review. Quality is reinforced through unit tests, integration tests, end-to-end smoke tests for critical flows, and manual QA for feature acceptance — ensuring that quality is built in throughout delivery rather than bolted on at the end.

**Releases** are standardized across Patch, Minor, and Major types, each requiring acceptance criteria to be met, CI and security scans to pass, release notes to be drafted, and a rollback plan to be in place before deployment. After every sprint, release, or significant milestone, the team holds a **retrospective** (45–75 minutes) structured around what went well, what could improve, and concrete action items with owners and due dates. These action items feed back into the project backlog, closing the loop on continuous improvement and ensuring that institutional learnings are captured and acted upon rather than lost.

## Process Summary

- **Initiation**: Define the project problem, SMART goals, stakeholders, and decision gate criteria before planning begins. See [Project Initiation Guide](./octoacme-project-initiation.md).
- **Planning**: Build a delivery-ready backlog, estimates, milestones, dependencies, and a Definition of Done. See [Project Planning](./octoacme-project-planning.md).
- **Execution & Tracking**: Manage day-to-day delivery through project board workflow, PR standards, and quality checks. See [Execution & Tracking](./octoacme-execution-and-tracking.md).
- **Risk Management & Communication**: Maintain the Risk Register and communicate status, blockers, and escalations consistently. See [Risk Management & Communication](./octoacme-risks-and-communication.md).
- **Release & Deployment**: Standardize patch/minor/major release readiness, rollout, verification, and rollback plans. See [Release & Deployment Guide](./octoacme-release-and-deployment.md).
- **Retrospective & Continuous Improvement**: Capture lessons learned and convert them into tracked action items. See [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md).
- **Roles & Personas**: Clarify role responsibilities and collaboration expectations across delivery. See [Roles & Personas](./octoacme-roles-and-personas.md).

## Documentation Links

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)
