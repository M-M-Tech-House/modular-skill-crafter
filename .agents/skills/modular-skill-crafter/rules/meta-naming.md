---
title: Semantic Skill Naming
impact: MEDIUM
impactDescription: Clear, hyphenated names with semantic prefixes ensure consistency, easy identification, and automatic organization of skills and rules.
tags: naming, conventions, metadata, prefixes
---

# Semantic Skill Naming

## Why it matters

Consistent naming conventions help in organizing the skill library.

- **Skills**: Hyphenated, lowercase names (kebab-case) are standard for file systems and URL-friendly.
- **Rules**: Must include their category prefix (e.g., `arch-`, `sec-`) to group related rules together and indicate their domain at a glance.

## Incorrect Example

**Skill Names:**

- `MyNewSkill` (CamelCase)
- `skill_for_testing` (snake_case)

**Rule Filenames:**

- `naming.md` (No prefix)
- `rule_01.md` (Abstract name)
- `APIConfig.md` (Mixed case)

## Correct Example

**Skill Names:**

- `skills-crafter`
- `business-logic-manager`
- `api-creator`

**Rule Filenames:**

- `meta-naming.md` (Category: Metadata)
- `struct-scaffold.md` (Category: Structure)
- `sec-validate-inputs.md` (Category: Security)
