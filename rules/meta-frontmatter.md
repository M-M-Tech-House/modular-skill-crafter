---
title: Complete YAML Metadata
impact: CRITICAL
impactDescription: Agent systems rely on accurate metadata to index, categorize, and understand the purpose of each skill. Missing metadata breaks discovery.
tags: metadata, yaml, frontmatter
---

# Complete YAML Metadata

## Why it matters

The `SKILL.md` file acts as the manifest for the skill. Without proper YAML frontmatter, the system cannot register the specific attributes like name, version, or author, making the skill unusable or untrackable.

## Incorrect Example

Omitting the YAML block or using critical fields:

```markdown
# My Skill

This is a description of my skill.
```

## Correct Example

Including a complete YAML frontmatter block at the top of `SKILL.md`:

```markdown
---
name: my-skill-name
description: A short, clear description of what this skill does.
license: MIT
metadata:
  author: System
  version: "1.0.0"
---

# My Skill Name

...
```
