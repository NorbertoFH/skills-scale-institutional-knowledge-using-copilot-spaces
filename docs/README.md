# OctoAcme Project Management Docs

This folder is the entry point for OctoAcme's project management process documentation. Use it as a navigation hub to understand how projects move from idea to delivery, who is responsible at each stage, and which artifacts and checkpoints keep work predictable and transparent.

## Process documentation index

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning Guide](./octoacme-project-planning.md)
- [Execution and Tracking Guide](./octoacme-execution-and-tracking.md)
- [Risk Management and Communication](./octoacme-risks-and-communication.md)
- [Release and Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and Personas](./octoacme-roles-and-personas.md)

## OctoAcme project management process summary

OctoAcme runs projects through a five-phase lifecycle: Initiation, Planning, Execution, Release, and Close & Retrospective. Initiation validates the business problem and success metrics with a one-pager and stakeholder alignment. Planning then converts the idea into a prioritized backlog, milestones, dependencies, and clear acceptance criteria. Execution is iterative, with work managed in GitHub Projects and delivered in small increments through review and QA. Release uses a defined checklist to confirm readiness, deployment safety, and post-deploy verification before production rollout.

Delivery is coordinated by clear role ownership across Project Managers, Product Managers, Developers, QA, and Stakeholders. PMs drive planning, risk tracking, and communication; PdMs shape outcomes and prioritize value; Developers and QA implement and validate shippable increments. Communication follows a regular cadence that keeps teams aligned: standups for near-term execution, weekly delivery/risk syncs for coordination, and recurring stakeholder updates for visibility and decisions. Escalation paths are explicit, moving from team-level triage to PM/Product Lead and then sponsor-level escalation when business impact grows.

Risk management and quality assurance are embedded throughout the lifecycle instead of treated as end-stage activities. Teams maintain a risk register with ownership, impact/likelihood, mitigation actions, and status updates reviewed during regular syncs. Quality controls include acceptance criteria, definition of done, automated CI checks, security scans, test coverage across unit/integration/smoke levels, and manual validation where needed. Retrospectives close each cycle by documenting lessons learned and concrete improvements so future projects become faster, safer, and more predictable.

## Using these docs in Copilot Spaces

- Add this `docs/` folder (or selected process documents) as Space context so Copilot can ground responses in OctoAcme standards.
- Start with the [Project Management Overview](./octoacme-project-management-overview.md), then drill into phase-specific guides for detailed checklists and templates.
- Reference the role and communication docs when asking Copilot to draft plans, status updates, risk logs, release notes, or retrospective actions.
