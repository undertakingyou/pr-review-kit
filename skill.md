# PR Feedback Skill

You are helping a reviewer write structured PR feedback. Use the templates and conventions defined in this kit to produce clear, consistent, actionable review comments.

## Instructions

1. Read the changed files or diff provided to you.
2. Identify issues, questions, or positive patterns worth calling out.
3. For each piece of feedback, select:
   - The **area of concern** that best fits (from the list below)
   - The **severity** level
   - The **template** that best matches the kind of feedback
4. Format each comment using the chosen template.
5. If the feedback matches a known **common pattern**, reference or reuse it rather than writing from scratch.

## Areas of Concern

Use the most specific sub-area that applies.

- 🧠 **Code Quality & Readability**: Readability, Naming, Code Clarity, Complexity, Structure / Organization, Comments & Documentation
- ⚙️ **Functionality & Logic**: Correctness, Edge Cases, Error Handling, Input Validation, Business Logic
- 🚀 **Performance**: Performance, Efficiency, Memory Usage, Algorithm Choice
- 🔐 **Security**: Security, Data Exposure, Authentication / Authorization, Input Sanitization
- 🧪 **Testing**: Test Coverage, Test Quality, Missing Tests, Edge Case Testing
- 🧩 **Architecture & Design**: Design Patterns, Separation of Concerns, Coupling / Cohesion, Scalability, Reusability
- 🧼 **Maintainability**: Technical Debt, Duplication (DRY), Modularity, Extensibility
- 🎨 **Style & Consistency**: Formatting, Linting, Code Style Consistency, Convention Adherence
- 🔄 **Git / PR Hygiene**: Commit Messages, PR Scope, File Organization, Merge Conflicts / Cleanup
- 📦 **Dependencies**: Dependency Choice, Versioning, Unused Dependencies

## Severity Levels

| Level | Icon | Use for |
|-------|------|---------|
| High | 🔴 | Bugs, security issues, breaking behavior |
| Medium | 🟠 | Maintainability risks, logic concerns |
| Low | 🟡 | Minor improvements |
| Nit | 🔵 | Style, formatting, tiny tweaks |

## Templates

### Standard feedback (default)

```
### <Area of Interest or Concern>

**Details**
<Explain the issue, context, and why it matters>

**Suggestion (optional)**
<Provide a concrete improvement or alternative>

**Severity:** <🔴 High | 🟠 Medium | 🟡 Low | 🔵 Nit>
```

### When asking a question

```
### <Area of Interest or Concern>

**Question**
<Ask for clarification or intent>

**Context**
<Why you're asking / what seems unclear>

**Severity:** <🔵 Nit | 🟡 Low>
```

### When something is done well

```
### ✅ <Area of Strength>

**What's working well**
<Call out something done well>

**Why it's good**
<Optional explanation>

Severity: 🔵 Nit (Positive)
```

### For quick/minor comments

```
**<Area>**
<Short comment>

Severity: <🔴 | 🟠 | 🟡 | 🔵>
```

### When teaching or explaining

```
### <Area of Interest or Concern>

**What I'm seeing**
<Describe the current implementation>

**Why it matters**
<Explain impact: readability, bugs, performance, etc.>

**Suggested approach**
<Clear improvement or example>

**Severity:** <🔴 High | 🟠 Medium | 🟡 Low | 🔵 Nit>
```

## Guidelines

- Always use the emoji icons for areas of concern and severity levels — they are part of the format, not decoration.
- Lead with the most important feedback (highest severity first).
- Always include at least one piece of positive feedback when something is done well.
- Use the teaching template for junior contributors or when the "why" is non-obvious.
- Use the quick template for nits to keep the review scannable.
- Group related feedback when multiple comments touch the same concern.
- Be specific: reference line numbers, function names, and concrete alternatives.
