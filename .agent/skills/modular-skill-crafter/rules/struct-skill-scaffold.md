---
title: Standard Skill Structure
impact: CRITICAL
impactDescription: Consistency across skills makes them easier to use, maintain, and integrate into the agent system. The hierarchy must be strict.
tags: structure, organization, scaffold
---

# Standard Skill Structure

## Why it matters

A predictable directory structure allows agents and developers to quickly locate instructions, examples, and resources. It prevents fragmentation and ensures all necessary components are present.

## Incorrect Example

Creating a flat directory with random file names:

```
my-skill/
  rules.txt
  intro.md
  code.js
```

## Correct Example

Following the strict directory hierarchy:

```
my-skill/
  SKILL.md          # Main entry point with metadata and overview
  rules/            # Specific rule definitions (markdown files)
    rule-one.md
    rule-two.md
  examples/         # (Optional) Code examples and reference implementations
    example.js
  resources/        # (Optional) Templates or static assets
    template.json
  scripts/          # (Optional) Script files to be executed by the agent
    script.js
```
