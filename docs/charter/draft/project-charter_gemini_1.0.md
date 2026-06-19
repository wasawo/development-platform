# Project Charter: AI Assisted Development Platform

## 1. Project Overview

- **Project No.**: No.0
- **Project Name**: AI Assisted Development Platform
- **Project Type**: Foundation Project
- **Status**: 🚧 In Progress
- **Project Owner**: wasawo

The **AI Assisted Development Platform** is a foundational infrastructure project designed to establish a highly efficient, reusable, and AI-assisted software development environment for personal development. This repository serves as the central **Single Source of Truth (SSoT)** for all development standards, architectures, and AI collaboration models.

---

## 2. Project Objectives

### Primary Objective

- Establish an AI-assisted development platform that enables efficient, high-quality personal software development.

### Secondary Objectives

- Standardize project documentation workflows across future projects.
- Standardize development environments utilizing Docker and VSCode Dev Containers.
- Define and optimize explicit workflows for AI collaboration.
- Create reusable project templates to accelerate future development.
- Construct a robust Linux-based execution environment.
- Prepare reliable infrastructure and workflows for upcoming initiatives (e.g., Project No.1: AI Automated Investment System).

---

## 3. PC Environment (Infrastructure)

The platform spans across two dedicated physical environments to separate primary development from runtime execution:

| Role                | CPU             | GPU                | Memory | OS                     |
| :------------------ | :-------------- | :----------------- | :----- | :--------------------- |
| **Main (PC1)**      | Ryzen 9 9900X3D | RX 9070 XT 16GB    | 32GB   | Windows 11 Home        |
| **Execution (PC2)** | Ryzen 5 3600    | RTX 2070 Super 8GB | 32GB   | Ubuntu 24.04 (Planned) |

---

## 4. Phase Roadmap

### Phase 0-1: Management Foundation

- [x] Create GitHub repository
- [ ] Establish documentation structure (_In Progress via this Charter_)
- [ ] Complete AI role definitions (`docs/ai-roles.md`)

### Phase 0-2: PC Environment Setup

- [ ] Configure Windows development environment (PC1)
- [ ] Execute Linux migration and environment setup (PC2 $\rightarrow$ Ubuntu 24.04)

### Phase 0-3: Execution Foundation

- [ ] Setup Docker and Dev Container configurations
- [ ] Deploy and verify sample API operations

### Phase 0-4: Automation and Completion

- [ ] Operationalize CI/CD pipelines via GitHub Actions
- [ ] Finalize reusable project templates

---

## 5. AI Collaboration Model

AI agents are designated as specialized advisors. The final decision-making authority strictly resides with the project owner (`wasawo`), based on the documented project decisions.

| AI Agent       | Assigned Role                                      | Key Strengths & Specializations                        |
| :------------- | :------------------------------------------------- | :----------------------------------------------------- |
| **Claude**     | Requirements Engineer / Documentation Specialist   | Structure, long-context management, phase design       |
| **ChatGPT**    | System Architect / Design Reviewer / Test Strategy | Broad knowledge, code generation, alternative analysis |
| **Gemini**     | Research Analyst / Technology Research             | Latest information, Google ecosystem integration       |
| **MS Copilot** | Coding Assistant / Implementation Support          | VSCode integration, real-time code completion          |

---

## 6. Document Governance (Single Source of Truth)

To prevent drift and conflict with AI-generated recommendations, **documented decisions always take precedence**. Document priority is enforced in the following order:

1. **Project Charter** (_This Document_)
2. Requirements
3. Architecture
4. ADR (Architecture Decision Records)
5. Test Strategy
6. Change Log

---

## 7. Development Principles

- **Documentation First**: No implementation without documentation.
- **AI Assisted Development**: Maximize productivity by leveraging specialized AI agents.
- **Reusable Architecture**: Build once, reuse across future projects.
- **Automation First**: Eliminate repetitive manual tasks.
- **Security Awareness**: Maintain secure configurations from inception.
- **Version Controlled Decisions**: All architectural and project shifts must be captured via Git.
