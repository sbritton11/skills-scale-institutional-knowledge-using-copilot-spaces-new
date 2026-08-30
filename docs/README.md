# OctoAcme Project Management Documentation

Welcome to the OctoAcme project management process documentation. This hub centralizes guidance for running customer-focused projects across the organization, providing an entry point to initiation, planning, execution, release, and retrospective practices used by the team.

OctoAcme follows a lightweight, outcome-driven approach: validate ideas with a concise Project One‑pager during Initiation, turn approved initiatives into a prioritized and estimated backlog during Planning, and deliver in short, testable increments during Execution. Releases follow a checklist-driven deployment process with smoke tests and rollback plans, and every project ends with a Close & Retrospective to capture learnings and convert them into actionable improvements.

Workflows emphasize iterative delivery and clear handoffs. Teams use a project board with columns (Backlog → Ready → In Progress → In Review → QA → Done) and a disciplined pull request workflow that favors small changes, links PRs to issues and acceptance criteria, runs CI and security scans, and requires approvals before merging. Day-to-day cadence includes daily standups for progress and blockers, weekly delivery syncs for progress and risks, and regular demos at the end of each sprint or milestone.

Quality assurance is built into the pipeline: unit and integration tests, end-to-end smoke tests for critical flows, automated security scanning in CI, and manual QA where appropriate. Risk management is handled through a simple risk register reviewed regularly, with defined escalation paths (team → PM → Product Lead → Sponsor). Retrospectives emphasize a few prioritized action items and follow-through via the project backlog.

## Table of Contents
- [Overview & Framework](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

## Quick Start by Role
- Project Manager: Start with the Overview, then follow Initiation → Planning → Execution. Maintain the risk register and run weekly status syncs.
- Product Manager: Use the Initiation and Planning docs for one‑pagers, success metrics, and backlog prioritization.
- Developer: Read Roles & Personas, then Execution & Tracking for branching, PR expectations, and testing requirements.
- QA/Tester: Review Execution & Tracking for QA responsibilities, test plans, and release acceptance criteria.

## Key Principles
- Customer-first: prioritize customer value and usability in every decision.
- Iterative delivery: ship small, testable increments and gather feedback early.
- Clear ownership: named PM and PdM for each project; responsibilities are explicit.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback, learning, and blameless retrospectives.

## How to use these docs
- Start at this README to find the process doc you need.
- Keep the Project One‑pager and release notes updated in the project repo.
- Add process-specific artifacts to `.copilot/` if you want Copilot Spaces to use them as context.
