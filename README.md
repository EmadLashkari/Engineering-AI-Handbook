# AI-Assisted Product Development Playbook
*A workflow for building products while keeping ownership of thinking, design, and engineering decisions.*

---

# Core Principle

Use AI as:

- Mentor
- Reviewer
- Challenger
- Thought Partner

Not as:

- Primary Architect
- Code Generator
- Decision Maker

---

# Universal Prompt

Use this whenever you want AI to act like a senior engineer instead of generating solutions.

```text
Act as a Staff Engineer.

I want to solve the problem myself.

Do NOT provide direct solutions or code.

Instead:

1. Ask questions.
2. Challenge my assumptions.
3. Identify blind spots.
4. Point out edge cases.
5. Explain trade-offs.
6. Give hints only when I get stuck.

Only provide a complete solution if I explicitly ask for it.
```

---

# Phase 1 — Problem Discovery

## Goal

Understand the problem before designing a solution.

## Prompt

```text
Act as a Senior Product Manager.

I have the following idea:

[IDEA]

Do not propose solutions.

Instead:

1. Identify hidden assumptions.
2. Highlight product risks.
3. List unanswered questions.
4. Explain what user problem this product is actually solving.
5. Point out any weak value propositions.
```
---

# Phase 2 — User Research & Personas

## Goal

Understand who the product is for.

## Prompt

```text
For the following product:

[PRODUCT DESCRIPTION]

Create 3 realistic user personas.

For each persona include:

- Goals
- Frustrations
- Motivations
- Behaviors

At the end, identify assumptions that need validation.
```
---

# Phase 3 — UX Flow Design

## Goal

Design user journeys before UI.

## Prompt

```text
I want to design the user flow myself.

Do not design the flow for me.

Instead ask questions that help me discover:

- Happy paths
- Edge cases
- Failure scenarios
- Recovery paths
- User confusion points
```
---

# Phase 4 — Domain Modeling

## Goal

Identify core business entities and relationships.

## Prompt

```text
I want to design the domain model myself.

These are my entities:

[ENTITIES]

Do not redesign them.

Instead:

1. Identify missing entities.
2. Identify misplaced responsibilities.
3. Identify questionable relationships.
4. Point out future scalability concerns.
```
---

# Phase 5 — API Design

## Goal

Design APIs based on user flows and domain requirements.

## Prompt

```text
I want to design the APIs myself.

Based on this user flow and domain model:

[DESCRIPTION]

Do not design endpoints.

Instead:

1. Identify scenarios my APIs must support.
2. Point out edge cases.
3. Highlight security concerns.
4. Highlight validation concerns.
```
---

# Phase 6 — Architecture Decisions

## Goal

Choose architecture intentionally.

## Prompt

```text
These are my system requirements:

[REQUIREMENTS]

Do not recommend an architecture.

Instead identify factors that influence architecture decisions:

- Team size
- Scalability needs
- Complexity
- Deployment model
- Testing requirements
- Development speed
```
### Architecture Comparison Prompt

```text
Compare the trade-offs between:

- Layered Architecture
- Modular Monolith
- Clean Architecture

Do not pick a winner.

Focus only on trade-offs.
```
---

# Phase 7 — Database Design

## Goal

Design data structures based on access patterns.

## Prompt

```text
This is my domain model:

[MODEL]

Before designing tables:

1. Analyze normalization needs.
2. Analyze relationships.
3. Analyze likely query patterns.
4. Identify potential bottlenecks.
```
---

# Phase 8 — Implementation

## Goal

Write the first version yourself.

## Rule

Always write the initial implementation before asking AI.

### Review Prompt

```text
Act as a Senior Engineer.

Review my code.

Do not rewrite it.

Focus on:

- Bugs
- Complexity
- Coupling
- Readability
- Maintainability
- Performance concerns
```
---

# Phase 9 — Testing

## Goal

Design tests before generating test code.

## Prompt

```text
For the following feature:

[FEATURE]

Generate test scenarios.

Do not write test code.

Focus on:

- Happy paths
- Edge cases
- Failure cases
- Security cases
- Performance cases
```
---

# Phase 10 — Architecture Retrospective

## Goal

Learn from your own decisions.

## Prompt

```text
I built the following system:

[SYSTEM DESCRIPTION]

If you were reviewing this as a Staff Engineer:

1. Which decisions would you keep?
2. Which decisions would you change?
3. What technical debt exists?
4. What scaling risks exist?
5. What would you do differently if starting today?
```
---

# Learning Mode Prompts

## Socratic Mode

```text
Use the Socratic method.

Do not provide answers immediately.

Guide me toward the solution by asking thoughtful questions.

Only provide a direct answer when I explicitly request it.
```
## Hint-Only Mode

```text
Do not give the solution.

Give only the smallest useful hint.

If I remain stuck, provide one additional hint at a time.
```
## Mental Model Builder

```text
I want to deeply understand this topic:

[TOPIC]

Do not start with definitions.

First build the mental model required to understand it.
```
---

# Golden Rule

Before asking AI for a solution:

1. Think first.
2. Sketch ideas.
3. Write assumptions.
4. Attempt implementation.

Then use AI to:

- Critique
- Review
- Challenge
- Improve

Not to replace your thinking.
