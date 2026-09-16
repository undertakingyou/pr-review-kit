# PR Feedback Templates

## Areas of Interest or Concern

### 🧠 Code Quality & Readability

- Readability
- Naming
- Code Clarity
- Complexity
- Structure / Organization
- Comments & Documentation

### ⚙️ Functionality & Logic

- Correctness
- Edge Cases
- Error Handling
- Input Validation
- Business Logic

### 🚀 Performance

- Performance
- Efficiency
- Memory Usage
- Algorithm Choice

### 🔐 Security

- Security
- Data Exposure
- Authentication / Authorization
- Input Sanitization

### 🧪 Testing

- Test Coverage
- Test Quality
- Missing Tests
- Edge Case Testing

### 🧩 Architecture & Design

- Design Patterns
- Separation of Concerns
- Coupling / Cohesion
- Scalability
- Reusability

### 🧼 Maintainability

- Technical Debt
- Duplication (DRY)
- Modularity
- Extensibility

### 🎨 Style & Consistency

- Formatting
- Linting
- Code Style Consistency
- Convention Adherence

### 🔄 Git / PR Hygiene

- Commit Messages
- PR Scope
- File Organization
- Merge Conflicts / Cleanup

### 📦 Dependencies

- Dependency Choice
- Versioning
- Unused Dependencies

## Severities

| Level | Icon | Use for |
|-------|------|---------|
| High | 🔴 | Bugs, security issues, breaking behavior |
| Medium | 🟠 | Maintainability risks, logic concerns |
| Low | 🟡 | Minor improvements |
| Nit | 🔵 | Style, formatting, tiny tweaks |

## Templates

### Base Template

```
### <Area of Interest or Concern>

**Details**
<Explain the issue, context, and why it matters>

**Suggestion (optional)**
<Provide a concrete improvement or alternative>

**Severity:** <🔴 High | 🟠 Medium | 🟡 Low | 🔵 Nit>
```

### Questions / Clarification

```
### <Area of Interest or Concern>

**Question**
<Ask for clarification or intent>

**Context**
<Why you're asking / what seems unclear>

**Severity:** <🔵 Nit | 🟡 Low>
```

### Positive Feedback

```
### ✅ <Area of Strength>

**What's working well**
<Call out something done well>

**Why it's good**
<Optional explanation>

Severity: 🔵 Nit (Positive)
```

### Quick / Lightweight

```
**<Area>**
<Short comment>

Severity: <🔴 | 🟠 | 🟡 | 🔵>
```

### Teaching Oriented

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
