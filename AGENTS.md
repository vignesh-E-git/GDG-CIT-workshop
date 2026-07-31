# AGENTS.md

# Project AI Operating Manual

This vault is the single source of truth for this project.

Before answering, coding, or making decisions, the AI MUST first understand the relevant parts of the vault.

---

# Mission

Maintain complete project knowledge.

Every work session should continue from where the previous session ended.

Never lose project context.

---

# Required Reading

Before performing ANY task:

1. Read INDEX.md
2. Read PROJECT_STATUS.md
3. Determine which domain the task belongs to.
4. Read every linked note in that domain.
5. Read ACTIVE_TASKS.md
6. Read DECISIONS.md
7. Continue work.

Do NOT assume anything without reading the notes.

---

# Vault Structure

.
├── INDEX.md
├── PROJECT_STATUS.md
├── ACTIVE_TASKS.md
├── DECISIONS.md
├── FRONTEND/
├── BACKEND/
├── AI/
├── DATABASE/
├── API/
├── DEPLOYMENT/
├── TESTING/
├── DOCS/
└── MEETINGS/

---

# Master Graph

The vault is organized as:

Project

├── Frontend
├── Backend
├── Database
├── API
├── AI
├── Deployment
├── Testing
├── Documentation
└── Meetings

Every folder has its own knowledge graph.

Never duplicate knowledge.

Instead create links.

---

# INDEX.md

Acts as the homepage.

Contains links to every major section.

Example

# Index

- [[Frontend]]
- [[Backend]]
- [[Database]]
- [[API]]
- [[AI]]
- [[Testing]]
- [[Deployment]]
- [[Documentation]]

---

# PROJECT_STATUS.md

Contains overall progress.

Example

Frontend
Status: 65%

Backend
Status: 40%

Database
Status: 80%

API
Status: 55%

Deployment
Status: Not Started

Testing
Status: 10%

---

# ACTIVE_TASKS.md

Contains current work.

Example

## In Progress

- JWT Authentication
- Dashboard UI
- YOLO Integration

## Next

- Payment API
- Docker
- CI/CD

---

# DECISIONS.md

Stores important decisions.

Example

Authentication
- JWT selected
- Refresh Tokens enabled

Database
- PostgreSQL

ORM
- Prisma

Backend
- FastAPI

Frontend
- React

Never change architecture without updating this file.

---

# Frontend Node

Folder

FRONTEND/

Contains

Overview.md

Architecture.md

Components.md

Pages.md

Routing.md

State Management.md

Styling.md

Completed.md

Remaining.md

Bugs.md

Ideas.md

Each note links to related notes.

---

# Backend Node

Folder

BACKEND/

Contains

Overview.md

Architecture.md

Core Logic.md

Authentication.md

Services.md

Controllers.md

Middleware.md

Utilities.md

Completed.md

Remaining.md

Bugs.md

Ideas.md

---

# Database Node

DATABASE/

Contains

Overview.md

ER Diagram.md

Schema.md

Tables.md

Indexes.md

Migrations.md

Completed.md

Remaining.md

Future Improvements.md

---

# API Node

API/

Contains

Overview.md

Endpoints.md

Requests.md

Responses.md

Authentication.md

Error Codes.md

Swagger.md

Completed.md

Remaining.md

---

# AI Node

Contains

Models.md

Prompts.md

RAG.md

Embeddings.md

Vector DB.md

Inference.md

Evaluation.md

Experiments.md

Completed.md

Remaining.md

---

# Deployment

Contains

Hosting.md

Docker.md

Environment Variables.md

CI-CD.md

Production.md

Monitoring.md

Completed.md

Remaining.md

---

# Testing

Contains

Unit Tests.md

Integration Tests.md

Performance.md

Known Bugs.md

Regression.md

Completed.md

Remaining.md

---

# Documentation

Contains

Setup.md

Architecture.md

API Docs.md

Developer Guide.md

User Guide.md

FAQ.md

---

# AI Rules

Before answering:

Read PROJECT_STATUS.md

Read ACTIVE_TASKS.md

Read relevant node.

Read every linked note.

Never answer from memory if documentation exists.

If documentation conflicts with conversation,
documentation wins.

---

# Updating Rules

Whenever work is completed:

Update Completed.md

Remove from Remaining.md

Update PROJECT_STATUS.md

Update ACTIVE_TASKS.md

Update DECISIONS.md if architecture changed.

Never forget to update progress.

---

# Progress Tracking Format

Each node maintains

Completed

Remaining

Blocked

In Progress

Future

Example

Backend

Completed

- JWT Login
- User CRUD

In Progress

- Role Permissions

Remaining

- Payment Module

Blocked

- Await frontend API

Future

- Redis Cache

---

# Linking Rules

Every concept must be linked.

Example

Authentication

Links

[[JWT]]

[[API]]

[[Database]]

[[Frontend]]

[[Testing]]

Never create isolated notes.

---

# AI Session Workflow

Whenever a session starts:

Read INDEX.md

Read PROJECT_STATUS.md

Read ACTIVE_TASKS.md

Identify requested domain.

Read that domain.

Read linked notes.

Perform task.

Update documentation.

Update progress.

Commit changes to notes.

Session complete.

---

# AI Output Rules

When asked to implement something:

Explain where it belongs.

Mention affected nodes.

Update documentation.

Update progress.

List remaining work.

Suggest next task.

---

# Golden Rule

The vault is the project's memory.

The codebase is the implementation.

If code changes, documentation must change.

If documentation changes, project status must change.

Never leave the vault out of sync.