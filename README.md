# PR Review Kit

A structured system for giving clear, consistent, and actionable PR feedback. Inspired by the templates Mason Meyer created.

## What's in here

- **[templates.md](templates.md)** — Areas of concern, severity levels, and feedback templates
- **[common/](common/)** — Reusable feedback patterns I find myself giving repeatedly
- **[skill.md](skill.md)** — Agent skill for formatting PR feedback using these templates

## Using the skill

The `skill.md` file can be used with Claude Code or other agent harnesses to automatically format PR review feedback using these templates.

### Claude Code

Add to your `.claude/commands/` directory or reference it directly:

```bash
cp skill.md ~/.claude/commands/pr-feedback.md
```

Then invoke with `/pr-feedback` during a review.

### Other agent harnesses

The skill file is a plain markdown instruction set. Feed it as a system prompt or instruction block to any LLM-based review tool.

## Common feedback patterns

The `common/` directory contains frequently-given feedback, each written using the template format. Add new ones as you notice yourself repeating the same review comment.

To add a new common pattern, create a markdown file in `common/` following the template format from `templates.md`.
