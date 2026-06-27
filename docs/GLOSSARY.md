# AI Engineering Platform - Glossary

This document defines the official terminology used throughout the project.

Every architectural document must use these definitions consistently.

---

# Project

A software initiative managed by the AI Engineering Platform.

A project contains software, engineering knowledge, decisions, documentation and artifacts.

A project exists independently of any specific AI provider.

---

# Goal

A high-level objective expressed by the engineer.

Examples:

- Create a frontend application.
- Analyze an existing repository.
- Improve accessibility.
- Generate documentation.

Goals describe **what** should be accomplished.

They never describe **how** to accomplish it.

---

# Engineering Knowledge

Structured knowledge owned by the project.

Engineering knowledge may originate from conversations, documentation, source code, external providers or engineering decisions.

Once incorporated into the project, the knowledge belongs to the project.

---

# External Provider

Any external system capable of supplying engineering information.

Examples include:

- GitHub
- GitLab
- Jira
- Azure DevOps
- Figma
- Notion

External providers are optional.

---

# Capability

A type of engineering information or functionality required by the platform.

Examples include:

- Requirements
- Design
- Source Control
- Documentation

A capability may be satisfied by one or more external providers.

---

# Artifact

Any engineering asset managed by the platform.

Examples include:

- Documents
- Architecture Decisions
- Source Code
- Workflows
- Test Suites
- Diagrams

---

# Workflow

A repeatable engineering process executed by the platform in order to achieve a goal.

---

# Orchestrator

The central component responsible for transforming user goals into engineering workflows.

Users interact with the Orchestrator.

Users never interact directly with individual agents.

---

# Engineer

The human responsible for the project.

The engineer always retains control over important engineering decisions.