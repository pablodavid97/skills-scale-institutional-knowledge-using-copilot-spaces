# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process hub. This directory contains comprehensive guidance on how OctoAcme manages projects from initiation through completion.

## About OctoAcme Project Management

OctoAcme follows a **customer-first, iterative approach** to project delivery with clear ownership, data-informed decisions, and a culture of continuous improvement. Our processes are designed to:

- **Deliver customer value** through prioritized, incremental releases
- **Maintain transparency** across teams and stakeholders
- **Reduce risk** through structured planning and continuous monitoring
- **Enable learning** via retrospectives and process improvements

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle Overview

Our standard project lifecycle consists of five key phases:

1. **Initiation**: Define the problem, identify stakeholders, and get approval
2. **Planning**: Break work into shippable increments and create a detailed plan
3. **Execution**: Build, test, and deliver features with daily standup oversight
4. **Release**: Deploy to production and verify success
5. **Close & Retrospective**: Capture learnings and identify improvements

## Key Workflows & Processes

### Project Initiation
OctoAcme projects begin with a **lightweight Project One-pager** that confirms business need and measurable outcomes. Each project has a named Project Manager (PM) and Product Manager (PdM), supported by developers, QA/testing specialists, and stakeholders. Projects move through a five-phase lifecycle with clear decision gates at each phase.

### Planning & Execution
Execution is managed through **GitHub Projects** with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done). Teams follow a disciplined workflow with:
- Daily standups (15 min) focused on progress, blockers, and dependencies
- Weekly delivery syncs to review progress and flag risks
- Small pull requests (≤400 lines) with at least one approval before merging
- Automated CI testing, linting, and security scanning before release

### Quality Assurance
Quality is built in throughout execution with:
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows
- Security scanning in CI
- Manual QA for feature acceptance when needed

### Risk Management & Communication
OctoAcme maintains a **Risk Register** tracking ID, description, impact, likelihood, owner, mitigation plan, and status—reviewed weekly during syncs. Communication follows a three-level escalation path (team-level → PM → Product Lead → Sponsor) with regular stakeholder updates through standardized weekly status templates.

### Release & Deployment
Release follows a formal checklist including pre-release requirements, smoke testing in staging, post-deploy verification, and a documented rollback plan for incidents. All acceptance criteria must be met and PRs merged with passing CI and security scans before deployment.

### Continuous Improvement
After each sprint, release, or milestone, OctoAcme conducts **45–75 minute retrospectives** structured around what went well, what could improve, and actionable items with clear owners and due dates. Action items are tracked as backlog issues and reviewed in weekly PM syncs.

## Process Documentation

### Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** - Start here for a high-level introduction to our approach, roles, and key artifacts
- **[Roles and Personas](octoacme-roles-and-personas.md)** - Understand the responsibilities of Project Managers, Product Managers, Developers, and other key roles

### Phase-Specific Guides
- **[Project Initiation Guide](octoacme-project-initiation.md)** - How to validate business need, align stakeholders, and decide go/no-go
- **[Project Planning](octoacme-project-planning.md)** - Breaking work into shippable increments and creating a detailed delivery plan
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** - Day-to-day execution, team rhythm, and progress tracking
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** - Standardized release process and deployment checklist
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - Capturing learnings and driving improvements

### Cross-Cutting Concerns
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** - Identifying, tracking, and communicating risks and dependencies across all phases

## How to Use These Docs

- **New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) and [Roles and Personas](octoacme-roles-and-personas.md)
- **Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) and [Project Planning](octoacme-project-planning.md)
- **In active delivery?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and update your [Risk Register](octoacme-risks-and-communication.md)
- **Planning a release?** Use the [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **Wrapping up?** Schedule a [Retrospective](octoacme-retrospective-and-continuous-improvement.md) and capture action items

## Key Contacts

- **For questions about processes:** See your Project Manager
- **For process improvements:** File an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template

## Communication Cadence

- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed
