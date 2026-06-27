# AI Engineering Platform - Domain Model

## Purpose

This document defines the core domain model of the AI Engineering Platform.

The objective is to identify the primary entities of the platform and their relationships before designing the software architecture.

---

# Root Entity

## Project

The Project is the central entity of the AI Engineering Platform.

Everything inside the platform exists to create, understand, improve or maintain a project.

Projects are independent from:

- AI providers
- IDEs
- Cloud providers
- External engineering tools
- Internal platform implementations

A project must remain understandable and usable regardless of changes to those dependencies.

---

# First-Level Domain Entities

A Project owns the following domain entities:

- Goals
- Engineering Knowledge
- Artifacts
- Workflows
- Decisions
- Providers
- Configuration

These entities together describe the complete engineering state of a project.

---

# High-Level Domain Model

```text
Project
│
├── Goals
├── Engineering Knowledge
├── Artifacts
├── Workflows
├── Decisions
├── Providers
└── Configuration
```

The Project is the only root entity.

Every other entity belongs to exactly one Project.