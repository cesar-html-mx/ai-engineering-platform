# User Journey

## Purpose

This document describes how software engineers interact with the AI Engineering Platform.

It focuses on the user experience rather than the internal implementation.

The objective is to define **what the platform should do**, not **how it is implemented**.

---

# Chapter 1 — First Contact

A software engineer wants to start a new software project.

The engineer clones the repository.

```bash
git clone https://github.com/<organization>/ai-engineering-platform.git
```

After opening the project, there is no need to understand the internal architecture of the platform.

The engineer simply starts the platform.

The platform welcomes the user and begins a guided engineering conversation.

Example:

> Welcome to AI Engineering Platform.
>
> What would you like to accomplish today?

The engineer does not choose agents, workflows or AI models.

The engineer only expresses a goal.

Examples:

- Create a new project.
- Continue an existing project.
- Analyze an existing repository.
- Improve software quality.
- Generate documentation.
- Configure infrastructure.

The platform is responsible for determining how that goal should be achieved.

At this stage, the platform does not assume any external integrations.

The project may have:

- No external providers.
- One or more external providers.
- A complete engineering ecosystem.

The experience must remain consistent regardless of the available integrations.

---

## Outcome

At the end of the first interaction, the engineer understands that:

- The platform is goal-driven.
- Engineering comes before implementation.
- External providers are optional.
- The platform guides the engineering process.