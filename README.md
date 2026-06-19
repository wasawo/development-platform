# AI Assisted Development Platform

> Project No.0

## Overview

Development Platform is a personal development foundation project  
designed to establish a reusable, AI-assisted software development environment.

This repository serves as the central source of truth for:

- Development standards and principles
- Project templates
- Architecture Decision Records (ADR)
- AI collaboration rules and role definitions
- Development environment configuration
- Documentation structure

---

## Project Information

| Item            | Value                            |
| --------------- | -------------------------------- |
| Project No.     | No.0                             |
| Project Name    | AI Assisted Development Platform |
| Status          | 🚧 In Progress                   |
| Repository Type | Foundation Project               |
| Owner           | wasawo                           |

---

## PC Environment

| Role            | CPU             | GPU                | Memory | OS                     |
| --------------- | --------------- | ------------------ | ------ | ---------------------- |
| Main (PC1)      | Ryzen 9 9900X3D | RX 9070 XT 16GB    | 32GB   | Windows 11 Home        |
| Execution (PC2) | Ryzen 5 3600    | RTX 2070 Super 8GB | 32GB   | Ubuntu 24.04 (planned) |

---

## Objectives

### Primary Objective

Establish an AI-assisted development platform that enables efficient personal software development.

### Secondary Objectives

- Standardize project documentation
- Standardize development environments using Docker / Dev Containers
- Define AI collaboration workflows
- Create reusable project templates
- Build a Linux-based execution environment
- Prepare infrastructure for future projects

---

## Phase Progress

### Phase 0-1: Management Foundation

- [x] GitHub repository created
- [x] Documentation structure established
- [x] AI role definitions completed

### Phase 0-2: PC Environment Setup

- [ ] Windows development environment (PC1)
- [ ] Linux migration and setup (PC2 → Ubuntu 24.04)

### Phase 0-3: Execution Foundation

- [ ] Docker / Dev Container setup
- [ ] Sample API operational

### Phase 0-4: Automation and Completion

- [ ] CI/CD operational (GitHub Actions)
- [ ] Project template completed

---

## AI Collaboration Model

| AI         | Role                                               | Strengths                                        |
| ---------- | -------------------------------------------------- | ------------------------------------------------ |
| Claude     | Requirements Engineer / Documentation Specialist   | Structure, long-context management, phase design |
| ChatGPT    | System Architect / Design Reviewer / Test Strategy | Broad knowledge, code generation, alternatives   |
| Gemini     | Research Analyst / Technology Research             | Latest information, Google ecosystem             |
| MS Copilot | Coding Assistant / Implementation Support          | VSCode integration, code completion              |

> Detailed definitions: [docs/operations/ai-roles.md](docs/operations/ai-roles.md)

### Collaboration Principle

AI agents are treated as specialized advisors.

Final decisions are made by the project owner based on documented project decisions.

---

## Single Source of Truth

Current Status:

✅ Project Charter v1.0.0 approved.  
✅ AI Roles & Responsibilities defined.  
Documentation structure is now operational.

All project decisions must be documented in this repository.

Priority order:

1. Project Charter
2. Requirements
3. Architecture
4. ADR (Architecture Decision Records)
5. Test Strategy
6. Change Log

> If AI-generated recommendations conflict with documented decisions,  
> **documented decisions take precedence.**

---

## Development Principles

- Documentation First
- AI Assisted Development
- Reusable Architecture
- Automation First
- Security Awareness
- Version Controlled Decisions

---

## Repository Structure

```text
development-platform/
├── docs/
│   ├── charter/
│   ├── requirements/
│   ├── architecture/
│   ├── adr/
│   ├── test/
│   ├── changelog/
│   ├── operations/
│   └── phases/
│
├── templates/
├── infra/
├── scripts/
├── .github/
└── README.md
```

---

## Future Projects

| Project No. | Project Name                   |
| ----------- | ------------------------------ |
| No.1        | AI Automated Investment System |
| TBD         | Future Projects                |

---

## License

Not defined yet.
