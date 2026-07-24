# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management knowledge base. This directory contains the complete guide to how OctoAcme runs projects—from initiation through retrospectives.

## Quick Overview

OctoAcme uses a structured, phase-based approach to project delivery that emphasizes customer value, iterative delivery, clear ownership, and data-driven decisions. 

### Core Principles

Our project management approach is grounded in five key principles:

- **Customer-First**: Prioritize customer value and usability in all decisions
- **Iterative Delivery**: Deliver small, testable increments rather than big-bang releases
- **Clear Ownership**: Every project has a named Project Manager (PM) and Product Lead responsible for outcomes
- **Data-Informed Decisions**: Measure impact and iterate based on evidence and metrics
- **Psychological Safety**: Encourage feedback, learning, and continuous improvement across all team members

### Project Management Processes

OctoAcme manages all cross-functional projects that deliver product features, services, or integrations through a consistent five-phase lifecycle:

1. **Initiation** — Validate business need, identify stakeholders, and create a Project One-pager with success metrics and timeline
2. **Planning** — Break work into shippable increments, identify dependencies and risks, establish Definition of Done
3. **Execution & Tracking** — Manage day-to-day delivery with regular standups, demos, and quality gates
4. **Release & Deployment** — Standardize release processes, deploy to production, verify outcomes
5. **Retrospective & Continuous Improvement** — Capture learnings and convert them into actionable improvements

### Key Roles

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, collaborate on design, and maintain code quality
- **QA/Testing**: Validate quality against acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic guidance

### Key Artifacts

Every OctoAcme project produces:
- Project Charter / One-pager
- Roadmap and Release Plan
- Sprint/Iteration Backlog with Acceptance Criteria
- Definition of Done (DoD)
- Risk Register
- Retrospective notes and action items

---

## Documentation Index

### Start Here

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, principles, core roles, key artifacts, and communication cadence. Start here if you're new to OctoAcme.

### Project Lifecycle

Follow these guides in sequence as you move through each phase of your project:

1. **[Project Initiation Guide](octoacme-project-initiation.md)** 
   - Validate business need and confirm measurable outcomes
   - Identify stakeholders and champions
   - Create a Project One-pager with success criteria and timeline
   - Make go/no-go decision to proceed to planning
   - *When to use*: When a new project idea or feature proposal is ready to be explored

2. **[Project Planning](octoacme-project-planning.md)**
   - Break work into shippable increments
   - Identify dependencies and risks
   - Estimate scope using T-shirt sizing or story points
   - Define Definition of Done (DoD)
   - Create release plan and milestone map
   - *When to use*: After initiation is approved and before execution begins

3. **[Execution & Tracking](octoacme-execution-and-tracking.md)**
   - Manage day-to-day execution and team rhythm (daily standups, weekly syncs)
   - Use project board workflow (Backlog → Ready → In Progress → In Review → QA → Done)
   - Implement quality gates (unit tests, integration tests, security scanning)
   - Track velocity, burndown, and success metrics
   - Escalate blockers following three-level escalation path
   - *When to use*: During the active development and delivery phase

4. **[Release & Deployment Guide](octoacme-release-and-deployment.md)**
   - Standardize release processes and reduce risk
   - Complete pre-release requirements (passing CI, security scans, release notes)
   - Execute deployment checklist for staging and production
   - Document and execute rollback procedures if needed
   - Announce release to stakeholders
   - *When to use*: When preparing to ship features to production

5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)**
   - Capture learnings: what went well, what could improve
   - Run effective retrospectives (45–75 minutes, blameless culture)
   - Convert action items into backlog or issues with clear owners and timelines
   - Measure impact of improvements and iterate
   - *When to use*: After each sprint, release, or important milestone

### Cross-Cutting Concerns

These guides apply throughout the project lifecycle:

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** 
  - Identify, assess, mitigate, and monitor risks using a Risk Register
  - Manage stakeholder communication with weekly status templates
  - Follow escalation paths for team-level → PM → Product Lead → Sponsor
  - Incident communication and post-incident retrospectives
  - *Use throughout*: Planning and execution phases

- **[Roles & Personas](octoacme-roles-and-personas.md)**
  - Detailed role descriptions: Project Manager, Product Manager, Developer, QA
  - Responsibilities, goals, and typical communication for each role
  - How roles collaborate across the project lifecycle
  - *Reference when*: Clarifying responsibilities or onboarding new team members

---

## Common Scenarios

Not sure where to start? Use this quick reference:

| Scenario | Start With |
|----------|-----------|
| **New project proposal?** | [Project Initiation Guide](octoacme-project-initiation.md) |
| **How do we run projects here?** | [Project Management Overview](octoacme-project-management-overview.md) |
| **Planning a project** | [Project Planning](octoacme-project-planning.md) |
| **Day-to-day execution** | [Execution & Tracking](octoacme-execution-and-tracking.md) |
| **Shipping a release** | [Release & Deployment Guide](octoacme-release-and-deployment.md) |
| **Project wrapped—what did we learn?** | [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) |
| **Unclear on roles?** | [Roles & Personas](octoacme-roles-and-personas.md) |
| **Managing risks or communicating status** | [Risk Management & Communication](octoacme-risks-and-communication.md) |

---

## How to Use These Docs

### For Project Teams

- **Kickoff**: Use [Project Initiation Guide](octoacme-project-initiation.md) and [Project Management Overview](octoacme-project-management-overview.md) to align the team on OctoAcme's approach
- **Planning**: Follow [Project Planning](octoacme-project-planning.md) to build your backlog and timeline
- **Execution**: Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md) during daily work
- **Release**: Use [Release & Deployment Guide](octoacme-release-and-deployment.md) as your deployment checklist
- **Close-out**: Run a [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) to capture learnings

### For Onboarding

- New to OctoAcme? Start with [Project Management Overview](octoacme-project-management-overview.md)
- Join an active project? Review [Execution & Tracking](octoacme-execution-and-tracking.md) and [Roles & Personas](octoacme-roles-and-personas.md)
- Leading a project? Familiarize yourself with all five lifecycle phases

### For Contributing

- These docs are the source of truth for OctoAcme project practices
- Keep project charters and plans updated in individual project repositories
- Suggest improvements via GitHub issues using the **"Add Content to Project Management Process Docs"** issue template (`.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml`)

---

## Communication Cadence

To keep projects aligned and transparent, OctoAcme follows this communication rhythm:

- **Daily**: Team standups (15 min) — focus on progress, blockers, dependencies
- **Twice-weekly** (or as agreed): Delivery team syncs
- **Weekly**: PM + Product Manager sync
- **Weekly**: Risk register review and status update
- **Monthly**: Stakeholder updates and progress reviews
- **As-needed**: Ad-hoc escalations for high-priority issues

---

## Questions?

- **First time here?** Read [Project Management Overview](octoacme-project-management-overview.md)
- **Not sure which doc?** Check the "Common Scenarios" table above
- **Found a gap or improvement?** Create an issue using the process doc update template
- **Need clarification on a process?** Reach out to your Project Manager or check the relevant phase guide

---

*Last updated: 2026*
*OctoAcme Project Management Handbook — Centralized Knowledge for Scalable Delivery*
