# Engineering AI Handbook
## A Practical Guide for Building Products Without Outsourcing Your Thinking

---

# How To Use This Handbook

For every phase:

1. Try to think first.
2. Write your assumptions.
3. Draw diagrams if needed.
4. Then use the prompt.

### Prompt Categories

| Type | Purpose |
|--------|--------|
| Discovery | Understand the problem |
| Challenge | Find flaws in your thinking |
| Design | Improve architecture and modeling |
| Review | Critique your work |
| Learning | Deeply understand concepts |
| Execution | Implement more effectively |

---

# 0. The Universal Staff Engineer Prompt

## When To Use

Whenever you want guidance without receiving the solution.

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

# 1. Product Discovery

## Use When

You have an idea but don't know whether it solves a real problem.

### Prompt

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
5. Point out weak value propositions.
```
---

# 2. User Research

## Use When

You want to understand your users before designing screens.

### Prompt

```text
For the following product:

[PRODUCT DESCRIPTION]

Create realistic user personas.

For each persona include:

- Goals
- Frustrations
- Motivations
- Behaviors

Identify assumptions that require validation.
```
---

# 3. UX Flow Design

## Use When

You know the users but not the flow.

### Prompt

```text
I want to design the user flow myself.

Do not design it for me.

Ask questions that help me discover:

- Happy paths
- Edge cases
- Failure scenarios
- Recovery paths
- User confusion points
```
---

# 4. MVP Scope Definition

## Use When

Everything feels important and you need to prioritize.

### Prompt

```text
This is my product idea:

[DESCRIPTION]

Help me identify:

- Must-have features
- Nice-to-have features
- Features that should be postponed

Explain the reasoning.
```
---

# 5. Domain-Driven Design

## Use When

You are discovering business concepts.

### Prompt

```text
I am designing the domain model.

These are my entities:

[ENTITIES]

Do not redesign them.

Instead:

1. Find missing concepts.
2. Find responsibility leaks.
3. Find naming problems.
4. Find future scaling concerns.
```
---

# 6. System Design Preparation

## Use When

You are about to choose an architecture.

### Prompt

```text
These are my system requirements:

[REQUIREMENTS]

Do not recommend an architecture.

Instead identify:

- Scalability concerns
- Reliability concerns
- Complexity drivers
- Performance requirements
- Operational constraints
```
---

# 7. Architecture Comparison

## Use When

You already have candidate architectures.

### Prompt

```text
Compare these approaches:

[A]
[B]

Do not choose a winner.

Focus on:

- Trade-offs
- Complexity
- Team impact
- Testing
- Scalability
- Maintainability
```
---

# 8. Backend Architecture

## Use When

You have flows and domains and need service boundaries.

### Prompt

```text
This is my domain model:

[MODEL]

I want to design the backend myself.

Do not design it.

Instead:

1. Challenge service boundaries.
2. Identify coupling risks.
3. Identify future bottlenecks.
4. Identify ownership problems.
```
---

# 9. Frontend Architecture

## Use When

You need component and state organization.

### Prompt

```text
This is my frontend design:

[DESIGN]

Review:

- Component boundaries
- State ownership
- Reusability
- Complexity
- Future maintainability

Do not rewrite it.
```
---

# 10. Database Design

## Use When

You are converting domain concepts into tables.

### Prompt

```text
This is my domain model:

[MODEL]

Before designing tables:

1. Analyze relationships.
2. Analyze query patterns.
3. Analyze indexing requirements.
4. Identify bottlenecks.
```
---

# 11. API Design

## Use When

You are designing endpoints.

### Prompt

```text
Based on this flow:

[FLOW]

Do not design endpoints.

Instead identify:

- Required capabilities
- Security concerns
- Validation concerns
- Versioning concerns
- Edge cases
```
---

# 12. Security Review

## Use When

A feature is nearly complete.

### Prompt

```text
Review this design from a security perspective.

Focus on:

- Authentication
- Authorization
- Data leakage
- Injection risks
- Rate limiting
- Sensitive data handling
```
---

# 13. Performance Review

## Use When

The feature works but you want to evaluate scaling risks.

### Prompt

```text
Review this system.

Focus on:

- Performance bottlenecks
- Expensive operations
- Database concerns
- Network concerns
- Scalability risks
```
---

# 14. Code Review

## Use When

You finished implementation.

### Prompt

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
- Performance
```
---

# 15. Test Design

## Use When

Before writing tests.

### Prompt

```text
For this feature:

[FEATURE]

Generate test scenarios.

Do not write test code.

Focus on:

- Happy paths
- Edge cases
- Failure cases
- Security cases
```
---

# 16. Technical Debt Review

## Use When

After shipping features.

### Prompt

```text
Review this system.

Identify:

- Technical debt
- Design shortcuts
- Hidden complexity
- Long-term maintenance risks
```
---

# 17. Staff Engineer Retrospective

## Use When

After a milestone or project completion.

### Prompt

```text
I built this system:

[SYSTEM]

Review it as a Staff Engineer.

Answer:

1. What would you keep?
2. What would you change?
3. What technical debt exists?
4. What scaling risks exist?
5. What would you do differently today?
```
---

# Learning Prompts

## Socratic Mode

### Use When

You want to think, not consume answers.

```text
Use the Socratic method.

Do not provide answers immediately.

Guide me using questions.

Only provide a direct answer when I explicitly request it.
```
---

## Hint Mode

### Use When

You are stuck.

```text
Do not provide the solution.

Give only the smallest useful hint.

If I remain stuck, provide one additional hint at a time.
```
---

## Mental Model Mode

### Use When

Learning difficult topics.

```text
I want to deeply understand:

[TOPIC]

Do not start with definitions.

First build the mental model required to understand it.
```
---

# Startup Mode

## Use When

Speed matters more than perfection.

```text
Review this decision from a startup perspective.

Optimize for:

- Speed
- Simplicity
- Learning
- Iteration

Do not optimize for enterprise scale.
```
---

# Enterprise Mode

## Use When

Long-term maintainability matters.

```text
Review this decision from an enterprise perspective.

Focus on:

- Scalability
- Reliability
- Governance
- Security
- Maintainability
```
---

# Final Rule

Never ask:

"Build this for me."

Instead ask:

"Review my thinking."
