# OctoAcme Project Management Docs

Welcome! This README centralizes OctoAcme's project management guidance, including:
- An overview of project management principles, key roles, and how we run initiatives end-to-end
- Easy-access links to all process docs in this repo

## Project Management Processes (Summary)

OctoAcme follows an **iterative, outcome-driven approach** to project delivery with clear roles and responsibilities across the organization.

### Core Principles
- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments and gather feedback frequently
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

### Project Lifecycle
1. **Initiation**: Define the problem, business need, success metrics, stakeholders, and obtain go/no-go decision
2. **Planning**: Break work into shippable increments, identify dependencies, align timelines, and define acceptance criteria
3. **Execution & Tracking**: Build, test, review code, iterate based on feedback, and track progress toward milestones
4. **Release**: Deploy to production, verify functionality, and announce to stakeholders
5. **Retrospective & Continuous Improvement**: Capture learnings and convert them into actionable improvements

### Key Roles
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, and measures success
- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validates quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic direction

### Communication Cadence
- **Daily standups**: Focus on progress, blockers, and dependencies (15 min)
- **Weekly sync** between PM and PdM: Alignment on status, risks, and decisions
- **Weekly delivery sync**: Team shows progress, updates, and flagged risks
- **Monthly stakeholder updates**: High-level status and strategic progress
- **Ad-hoc escalations**: As needed for business-impacting issues

### Key Practices
- Use GitHub Projects with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Small pull requests (≤ 400 lines when possible) with clear issue links and acceptance criteria
- Automated testing, linting, and security scanning in CI before code review
- Risk Register maintained and reviewed at weekly syncs
- Regular demos and feedback cycles with stakeholders
- Checklists for major gates (planning, pre-release, deployment)

---

## Process Documentation

Explore detailed guidance for each phase of project delivery:

| Process | Purpose |
|---------|---------|
| [Project Management Overview](octoacme-project-management-overview.md) | Introduction to OctoAcme's approach, roles, key artifacts, and lifecycle |
| [Project Initiation Guide](octoacme-project-initiation.md) | Steps to validate and authorize work, align stakeholders, and create a lightweight plan |
| [Project Planning](octoacme-project-planning.md) | How to break approved work into actionable backlog items with clear scope and dependencies |
| [Execution & Tracking](octoacme-execution-and-tracking.md) | Day-to-day execution, team rhythm, workflows, quality standards, and blocker escalation |
| [Risk Management & Communication](octoacme-risks-and-communication.md) | How to identify, manage, and communicate risks, plus stakeholder communication strategies |
| [Release & Deployment Guide](octoacme-release-and-deployment.md) | Standardized approach to releasing features and managing rollbacks |
| [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) | How to capture learnings and convert them into actionable improvements |
| [Roles and Personas](octoacme-roles-and-personas.md) | Detailed descriptions of typical roles and responsibilities |

---

## Quick Start

**New to OctoAcme?**
1. Start with [Project Management Overview](octoacme-project-management-overview.md) to understand our approach and key roles
2. Review [Roles and Personas](octoacme-roles-and-personas.md) to see how your role fits in
3. Explore the process documents that apply to your current project phase

**Kicking off a new project?**
1. Follow the [Project Initiation Guide](octoacme-project-initiation.md) to validate and authorize the work
2. Move into [Project Planning](octoacme-project-planning.md) once approved
3. Use [Execution & Tracking](octoacme-execution-and-tracking.md) during delivery

**Managing risk or communicating status?**
- See [Risk Management & Communication](octoacme-risks-and-communication.md) for templates and escalation paths

**Ready to release?**
- Follow the [Release & Deployment Guide](octoacme-release-and-deployment.md) pre-release checklist

**Wrapping up a project?**
- Use [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to capture learnings and drive improvements

---

## Contributing

To suggest updates, improvements, or new content for these process docs, please:
1. Open an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Include a clear summary of the change, rationale, and suggested content
3. Reference the relevant process document or indicate if this is a new addition

All updates are reviewed and refined collaboratively to ensure consistency and alignment with OctoAcme's project management approach.
