# Engineering AI Decision Tree
## A Practical Navigation System For Building Software Products

---

# Start Here

Ask yourself:

## What is my current situation?

```text
I have an idea
```
➡ Go to **1. Product Discovery**

```text
I understand the problem
```
➡ Go to **2. User Research**

```text
I know the users
```
➡ Go to **3. UX Flow Design**

```text
I know the flows
```
➡ Go to **4. Domain Modeling**

```text
I know the domain**
```
➡ Go to **5. Architecture Design**

```text
I chose an architecture
```
➡ Go to **6. Database & API Design**

```text
I designed the system
```
➡ Go to **7. Implementation**

```text
The feature is built
```
➡ Go to **8. Review & Testing**

```text
The product is shipped
```
➡ Go to **9. Retrospective & Scaling**
---

# 1. Product Discovery

## Ask Yourself

- What problem am I solving?
- Who has this problem?
- Why is this painful?

### Use

**Product Discovery Prompt**

When:
- You have an idea.
- You don't know if it's valuable.

Output:
- Risks
- Assumptions
- Open questions

Next:
➡ User Research

---

# 2. User Research

## Ask Yourself

- Who is the user?
- What are they trying to accomplish?
- What frustrates them?

### Use

**Persona Prompt**

When:
- You know the problem.
- You don't fully understand users.

Output:
- Personas
- Motivations
- Frustrations

Next:
➡ UX Flow Design

---

# 3. UX Flow Design

## Ask Yourself

- What is the happy path?
- What can go wrong?
- How does the user recover?

### Use

**UX Flow Prompt**

When:
- You know the users.
- You need journeys.

Output:
- Flows
- Edge cases
- Failure scenarios

Next:
➡ MVP Scope Definition

---

# 4. MVP Scope Definition

## Ask Yourself

- What is essential?
- What can wait?

### Use

**MVP Prioritization Prompt**

When:
- Everything feels important.

Output:
- Must-have
- Nice-to-have
- Future features

Next:
➡ Domain Modeling

---

# 5. Domain Modeling

## Ask Yourself

- What concepts exist?
- What responsibilities exist?
- What relationships exist?

### Use

**DDD Prompt**

When:
- You know the business process.

Output:
- Entities
- Relationships
- Missing concepts

Next:
➡ Architecture Design

---

# 6. Architecture Design

## Ask Yourself

- How complex is the domain?
- How large will this become?
- How many developers will work on it?

### Use

### Architecture Factors Prompt

First.

Then:

### Architecture Comparison Prompt

Output:
- Trade-offs
- Constraints
- Risks

Next:
➡ Database Design

---

# 7. Database Design

## Ask Yourself

- What queries will happen most?
- What data changes frequently?
- What relationships exist?

### Use

**Database Review Prompt**

Output:
- Query patterns
- Indexing considerations
- Bottlenecks

Next:
➡ API Design

---

# 8. API Design

## Ask Yourself

- What capabilities are required?
- What must be protected?
- What must be validated?

### Use

**API Review Prompt**

Output:
- Requirements
- Security concerns
- Validation concerns

Next:
➡ Implementation

---

# 9. Implementation

## Golden Rule

Write Version 1 Yourself.

Do NOT ask AI to write the feature first.

### Use AI For

- Clarification
- Guidance
- Hints
- Reviews

### Avoid

- Generate entire feature
- Generate entire architecture
- Generate entire project

Next:
➡ Code Review

---

# 10. Code Review

## Ask Yourself

- Is this understandable?
- Is this maintainable?
- Is this too complex?

### Use

**Code Review Prompt**

Output:
- Bugs
- Smells
- Complexity concerns

Next:
➡ Test Design

---

# 11. Test Design

## Ask Yourself

- What can break?
- What assumptions exist?
- What should never happen?

### Use

**Test Design Prompt**

Output:
- Happy paths
- Edge cases
- Failure cases

Next:
➡ Security Review

---

# 12. Security Review

## Ask Yourself

- Who can access this?
- What can be abused?
- What data is sensitive?

### Use

**Security Review Prompt**

Output:
- Security risks
- Authorization issues
- Data exposure risks

Next:
➡ Performance Review

---

# 13. Performance Review

## Ask Yourself

- What happens with 10 users?
- 1,000 users?
- 100,000 users?

### Use

**Performance Review Prompt**

Output:
- Bottlenecks
- Scaling concerns

Next:
➡ Launch

---

# 14. Launch Review

## Ask Yourself

- Is this good enough?
- What assumptions remain untested?

### Use

**Startup Mode**
or
**Enterprise Mode**

Depending on your goals.

Next:
➡ Retrospective

---

# 15. Retrospective

## Ask Yourself

- What did I learn?
- What would I change?
- What debt did I create?

### Use

**Staff Engineer Retrospective Prompt**

Output:
- Lessons learned
- Technical debt
- Future improvements

---

# Emergency Decision Tree

## I'm Stuck

➡ Use Hint Mode

---

## I Don't Understand The Topic

➡ Use Mental Model Mode

---

## I Want To Think More

➡ Use Socratic Mode

---

## I Want A Second Opinion

➡ Use Staff Engineer Mode

---

## I Want To Move Faster

➡ Use Startup Mode

---

## I Need Long-Term Quality

➡ Use Enterprise Mode

---

# One Rule To Remember

Before asking:

"Can AI build this?"

Ask:

"Have I thought about this enough to review AI's answer critically?"
