# AI Roles and Responsibilities

> **Document Reference:** [Project Charter](./charter/project-charter.md) Section 13: AI Collaboration Model

---

## 📋 Overview

This document defines the roles, responsibilities, strengths, and collaboration guidelines for AI advisors used in Project No.0 and subsequent projects.

**Key Principle**: AI advisors are **specialized consultants**, not decision-makers. Final decisions rest exclusively with the Project Owner.

---

## Decision-Making Framework

```
AI Advisor Input → Project Owner Decision → Documented (Charter/ADR)
     ↓                      ↓                        ↓
  Recommend            Evaluate &               Implement
  Research             Decide                   Execute
  Analyze              Document
```

**Golden Rule**: If AI recommendations conflict with **documented decisions**, documented decisions **always take precedence**.

---

## 1. Claude — Requirements Engineer / Documentation Specialist

### Role Summary

Claude serves as the primary architect for requirements analysis, documentation structure, and long-term project planning. Claude excels at creating comprehensive documentation and maintaining consistency across technical specifications.

### Primary Responsibilities

#### 1.1 Requirements Engineering

- **Charter & Planning**
  - Draft project charters and foundational documents
  - Create detailed project plans with phases and milestones
  - Define success criteria and acceptance conditions
  - Identify scope boundaries (In Scope / Out of Scope)

- **Requirements Analysis**
  - Translate business needs into technical specifications
  - Create requirement documents (functional, non-functional, system)
  - Identify dependencies and relationships
  - Validate completeness and clarity

#### 1.2 Documentation Specialist

- **Structured Documentation**
  - Create documentation templates and frameworks
  - Maintain documentation consistency (style, terminology)
  - Organize information hierarchically for readability
  - Implement the "Documentation First" principle

- **Document Management**
  - Manage document versions and history
  - Track document priorities per the SSoT hierarchy
  - Ensure traceability between requirements → design → code
  - Assists ADR (Architecture Decision Records) documentation

#### 1.3 Phase Design & Planning

- **Long-term Strategy**
  - Design multi-phase project timelines
  - Define phase gates and completion criteria
  - Create roadmaps with clear milestones
  - Plan resource allocation and dependencies

### Strengths

| Strength                    | Application                                           |
| --------------------------- | ----------------------------------------------------- |
| **Structure**               | Organizing complex information into clear hierarchies |
| **Long-context management** | Maintaining consistency across large documents        |
| **Phase design**            | Breaking projects into manageable, sequential phases  |
| **Requirements clarity**    | Removing ambiguity from specifications                |
| **Risk identification**     | Spotting potential issues early                       |

### Use Cases

- **Initial Project Setup**: Draft charter, phases, and roadmap
- **Requirements Definition**: Create detailed requirement documents
- **Documentation Review**: Check consistency and completeness
- **ADR Creation**: Document architectural decisions
- **Phase Planning**: Design multi-phase timelines

### Limitations & Constraints

- ⚠️ Not responsible for implementation or coding
- ⚠️ Should defer to Gemini for latest technology research
- ⚠️ Should defer to ChatGPT for architectural alternatives
- ⚠️ Not for real-time code completion (defer to Copilot)

### Communication Pattern

> **When to consult Claude:**
>
> - "Draft a comprehensive charter for this project"
> - "Create a requirements document for feature X"
> - "Review this documentation for consistency"
> - "Design a multi-phase implementation plan"

---

## 2. ChatGPT — System Architect / Design Reviewer / Test Strategy

### Role Summary

ChatGPT serves as the chief architect, design evaluator, and test strategy planner. ChatGPT brings broad technical knowledge and the ability to evaluate multiple design alternatives and ensure comprehensive test coverage.

### Primary Responsibilities

#### 2.1 System Architecture

- **Design & Architecture**
  - Propose system architectures for complex problems
  - Design component relationships and interfaces
  - Evaluate architectural patterns (MVC, microservices, etc.)
  - Ensure scalability and maintainability

- **Design Documentation**
  - Create architecture diagrams and descriptions
  - Document design decisions and trade-offs
  - Specify integration points
  - Define performance and scalability requirements

#### 2.2 Design Review & Alternatives

- **Architecture Review**
  - Review designs created by other advisors
  - Identify design flaws or improvements
  - Suggest alternative approaches
  - Evaluate pros/cons of design choices

- **Comparative Analysis**
  - Compare different technology stacks
  - Evaluate multiple implementation strategies
  - Create decision matrices for alternatives
  - Identify optimal solutions for given constraints

#### 2.3 Test Strategy & Quality Assurance

- **Test Planning**
  - Define test strategy (unit, integration, E2E)
  - Create test plans with coverage requirements
  - Design test cases and scenarios
  - Plan for CI/CD test integration

- **Quality Assurance**
  - Identify potential quality issues
  - Review code for best practices
  - Ensure security considerations are addressed
  - Validate compliance with development principles

### Strengths

| Strength            | Application                                     |
| ------------------- | ----------------------------------------------- |
| **Broad knowledge** | Understanding diverse technology domains        |
| **Code generation** | Creating well-structured code examples          |
| **Alternatives**    | Proposing multiple solutions and comparing them |
| **Architecture**    | Designing scalable, maintainable systems        |
| **Testing**         | Comprehensive test strategy planning            |

### Use Cases

- **Architecture Design**: Propose system designs and components
- **Design Review**: Evaluate existing designs for improvements
- **Code Examples**: Generate implementation examples
- **Technology Evaluation**: Compare different technology options
- **Test Strategy**: Plan comprehensive test coverage
- **Quality Review**: Check code for best practices

### Limitations & Constraints

- ⚠️ Not responsible for implementation details (defer to Copilot)
- ⚠️ Should defer to Gemini for latest framework updates
- ⚠️ Should defer to Claude for long-term planning consistency
- ⚠️ Recommendations subject to Project Owner approval

### Communication Pattern

> **When to consult ChatGPT:**
>
> - "Design the architecture for this system"
> - "Review this design and suggest improvements"
> - "Create a test strategy for this component"
> - "Compare these technology options"

---

## 3. Gemini — Research Analyst / Technology Research

### Role Summary

Gemini serves as the research specialist with access to the latest information and technologies. Gemini is the primary source for current, up-to-date information about frameworks, libraries, tools, and best practices.

### Primary Responsibilities

#### 3.1 Technology Research

- **Latest Information**
  - Research current versions of frameworks and libraries
  - Identify new tools and emerging technologies
  - Track breaking changes and deprecations
  - Monitor security advisories

- **Technology Evaluation**
  - Research technology capabilities and limitations
  - Compare features and performance
  - Identify community adoption and maturity
  - Evaluate documentation quality

#### 3.2 Ecosystem Intelligence

- **Cloud & Ecosystem Research**
  - Research Google Cloud services and APIs
  - Understand Google ecosystem integrations
  - Track Google service updates and changes
  - Evaluate GCP for project needs

- **Broader Ecosystem**
  - Research other major cloud providers
  - Track open-source project developments
  - Monitor industry trends and best practices
  - Evaluate emerging standards

#### 3.3 Dependency & Compatibility Analysis

- **Version Management**
  - Research compatible versions of dependencies
  - Identify breaking changes between versions
  - Track security patches and updates
  - Evaluate migration paths

- **Compatibility**
  - Assess technology compatibility
  - Research known issues and workarounds
  - Identify platform-specific considerations
  - Evaluate cross-platform support

### Strengths

| Strength                | Application                                     |
| ----------------------- | ----------------------------------------------- |
| **Latest information**  | Current knowledge of frameworks and tools       |
| **Google ecosystem**    | Deep understanding of GCP and related services  |
| **Trend analysis**      | Identifying emerging technologies and practices |
| **Dependency research** | Finding current versions and compatibility info |
| **Security updates**    | Tracking latest security advisories             |

### Use Cases

- **Technology Selection**: Research frameworks or tools
- **Version Planning**: Determine current stable versions
- **Security Updates**: Check for security advisories
- **Ecosystem Research**: Evaluate GCP and Google services
- **Trend Analysis**: Research emerging best practices
- **Migration Planning**: Research upgrade paths

### Limitations & Constraints

- ⚠️ Not responsible for architecture decisions (defer to ChatGPT)
- ⚠️ Not for documentation structure (defer to Claude)
- ⚠️ Recommendations subject to Project Owner approval
- ⚠️ Research findings should be cited with sources

### Communication Pattern

> **When to consult Gemini:**
>
> - "What's the latest stable version of [framework]?"
> - "Research [tool] and its capabilities"
> - "Are there security updates for [dependency]?"
> - "What's the current best practice for [technology]?"

---

## 4. MS Copilot — Coding Assistant / Implementation Support

### Role Summary

MS Copilot serves as the hands-on coding assistant, integrated directly into VSCode. Copilot is the primary advisor for implementation details, code completion, debugging, and development workflow automation.

### Primary Responsibilities

#### 4.1 Code Implementation

- **Code Generation**
  - Generate code based on specifications and examples
  - Provide boilerplate and template code
  - Implement common patterns and algorithms
  - Create utility functions and helpers

- **Code Completion**
  - VSCode integrated real-time code suggestions
  - Function signature completion
  - Import statement suggestions
  - Pattern-based code completion

#### 4.2 Development Workflow Support

- **Debugging Assistance**
  - Help identify code issues and bugs
  - Suggest debugging approaches
  - Provide error explanation and solutions
  - Optimize problematic code

- **Code Refactoring**
  - Suggest code improvements
  - Identify code duplication
  - Improve code readability
  - Optimize performance

#### 4.3 Development Environment Integration

- **VSCode Integration**
  - Inline code suggestions
  - Documentation lookup
  - Test generation
  - Git commit message suggestions

- **Automation Support**
  - Script generation and automation
  - Configuration file creation
  - Build script assistance
  - Deployment script help

### Strengths

| Strength               | Application                           |
| ---------------------- | ------------------------------------- |
| **VSCode integration** | Real-time suggestions in the editor   |
| **Code completion**    | Fast, context-aware code suggestions  |
| **Implementation**     | Quick code generation and boilerplate |
| **Productivity**       | Reducing repetitive coding tasks      |
| **Debugging**          | Identifying and fixing code issues    |

### Use Cases

- **Real-time Coding**: VSCode inline suggestions
- **Boilerplate Generation**: Creating project templates
- **Code Completion**: Function and variable completion
- **Debugging**: Identifying and fixing bugs
- **Refactoring**: Improving existing code
- **Testing**: Generating test cases
- **Scripts**: Creating automation scripts

### Limitations & Constraints

- ⚠️ Not responsible for architecture (defer to ChatGPT)
- ⚠️ Not for long-term planning (defer to Claude)
- ⚠️ Not for latest technology research (defer to Gemini)
- ⚠️ Code suggestions should be reviewed for correctness

### Communication Pattern

> **When to consult Copilot:**
>
> - Code completion in VSCode
> - "Generate boilerplate for [framework]"
> - "Help debug this error"
> - "Create a test case for this function"

---

## AI Collaboration Workflow

### Typical Project Lifecycle

```
Phase 1: Planning & Design
├─ Claude: Draft charter and phases
├─ ChatGPT: Design architecture
└─ Gemini: Research technology stack

Phase 2: Requirements & Specifications
├─ Claude: Create detailed requirements
├─ ChatGPT: Review and refine design
└─ Gemini: Verify technology choices

Phase 3: Implementation
├─ Copilot: Generate code and templates
├─ ChatGPT: Review design implementation
├─ Gemini: Verify dependency versions
└─ Claude: Track progress and updates

Phase 4: Testing & Quality
├─ ChatGPT: Create test strategy
├─ Copilot: Generate test code
├─ Claude: Document test results
└─ Gemini: Research testing best practices

Phase 5: Documentation & Delivery
├─ Claude: Create comprehensive documentation
├─ ChatGPT: Review final design
└─ Copilot: Generate final code examples
```

### Decision Recording (from Project Charter)

When AI advisors provide recommendations, **all decisions must be documented** in the following priority order:

1. **Project Charter** (foundational decisions)
2. **Requirements** (functional specifications)
3. **Architecture** (system design decisions)
4. **ADR** (Architecture Decision Records - for specific choices)
5. **Test Strategy** (testing approaches)
6. **Change Log** (implementation progress)

**Important**: If an AI recommendation conflicts with any **documented decision**, the documented decision takes precedence. Update documentation rather than override decisions.

---

## 5. Conflict Resolution & Decision Making

### When AI Advisors Disagree

If different AI advisors recommend conflicting approaches:

1. **Project Owner evaluates** both recommendations
2. **Project Owner decides** based on project constraints
3. **Document decision** in ADR or appropriate section
4. **Communicate decision** to all advisors
5. **Future recommendations** should respect this decision

### Example

> **Scenario**: Claude recommends phased architecture, ChatGPT recommends monolithic for speed.
>
> **Resolution**:
>
> - Project Owner decides: "Use modular monolith for Phase 0-1, migrate to microservices in Phase 0-3"
> - Document in: ADR-001: Architecture Evolution Strategy
> - Both advisors align with documented decision
> - Subsequent recommendations respect this decision

---

## 6. Guidelines for Effective AI Collaboration

### ✅ DO

- ✅ Provide clear context and requirements to AI advisors
- ✅ Review AI recommendations before implementation
- ✅ Document decisions made and reasoning
- ✅ Use each AI's strengths for their specialty
- ✅ Ask for clarification or alternatives
- ✅ Track AI recommendations in issues/PRs
- ✅ Verify AI-generated code before merging
- ✅ Keep documentation in sync with decisions

### ❌ DON'T

- ❌ Blindly implement AI suggestions without review
- ❌ Assume AI recommendations are always correct
- ❌ Allow undocumented decisions to stand
- ❌ Use wrong AI for wrong task (e.g., Copilot for architecture)
- ❌ Ignore conflicts between AI recommendations
- ❌ Forget to update documentation with final decisions
- ❌ Accept outdated information from AI (verify with Gemini)
- ❌ Override documented decisions without new documentation

---

## 7. AI Advisor Selection Guide

### Quick Reference: Which AI to Consult?

| Task                    | Primary | Secondary | Verify With |
| ----------------------- | ------- | --------- | ----------- |
| Charter & Planning      | Claude  | ChatGPT   | N/A         |
| Requirements Definition | Claude  | ChatGPT   | Claude      |
| Architecture Design     | ChatGPT | Claude    | N/A         |
| Technology Research     | Gemini  | ChatGPT   | Gemini      |
| Code Implementation     | Copilot | ChatGPT   | Copilot     |
| Code Review             | ChatGPT | Copilot   | ChatGPT     |
| Test Strategy           | ChatGPT | Claude    | ChatGPT     |
| Documentation           | Claude  | ChatGPT   | Claude      |
| Bug Fixing              | Copilot | ChatGPT   | Copilot     |
| Version Planning        | Gemini  | ChatGPT   | Gemini      |

---

## 8. Communication Templates

### 📝 Asking Claude

```
Task: [Charter/Requirements/Documentation/ADR]
Context: [Current project state]
Constraints: [Budget/Time/Technical]
Request: [Create/Review/Refine]
Reference: [Previous decisions or docs]
```

### 🏗️ Asking ChatGPT

```
Problem: [Architecture/Design/Test challenge]
Constraints: [Non-functional requirements]
Alternatives: [Options to consider]
Request: [Design/Compare/Review]
Reference: [Existing designs or standards]
```

### 🔬 Asking Gemini

```
Technology: [Framework/Tool/Library]
Purpose: [What we want to achieve]
Constraints: [Version/Compatibility requirements]
Request: [Research/Compare/Find alternatives]
Context: [Current tech stack]
```

### 💻 Asking Copilot

```
Feature: [What to implement]
Framework: [Technology stack]
Requirements: [Functional specs]
Constraints: [Code style/patterns]
Context: [Existing code or architecture]
```

---

## 10. AI Escalation Matrix

| Task         | Primary | Secondary |
| ------------ | ------- | --------- |
| Charter      | Claude  | ChatGPT   |
| Requirements | Claude  | ChatGPT   |
| Architecture | ChatGPT | Claude    |
| Research     | Gemini  | ChatGPT   |
| Coding       | Copilot | ChatGPT   |
| Testing      | ChatGPT | Copilot   |

---

## 11. Related Documents

- [Project Charter](./charter/project-charter.md) — Overall project direction
- [Development Principles](./charter/project-charter.md#14-development-principles) — Guiding values
- [Governance](./charter/project-charter.md#6-governance) — Decision authority
- Architecture Decision Records (ADR) — Specific design decisions

---

## Document History

| Version | Date       | Changes                                          |
| ------- | ---------- | ------------------------------------------------ |
| 1.0.0   | 2026-06-19 | Initial creation based on Project Charter v1.0.0 |

---

_This document works in conjunction with Project Charter v1.0.0. Both are foundational documents for Project No.0._
