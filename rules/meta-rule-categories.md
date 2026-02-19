---
title: Rule Categorization and Prefixes
impact: HIGH
impactDescription: Categorizing rules by priority and using standard prefixes ensures that the most critical instructions are processed first and that related rules are grouped together.
tags: categorization, priority, naming, structure
---

# Rule Categorization and Prefixes

## Why it matters

Agents process information sequentially. Defining clear categories with priorities ensures that critical architecture or security rules are evaluated before stylistic or optional preferences. Prefixes in filenames act as a visual namespaces, preventing collisions and making the skill directory self-sorting.

## Incorrect Example

**In `SKILL.md`:** No category table.

**Filenames:**

- `dont-hardcode.md`
- `naming.md`
- `security.md`

## Correct Example

**In `SKILL.md`:**

| Priority | Category     | Impact   | Prefix   |
| -------- | ------------ | -------- | -------- |
| 1        | Security     | CRITICAL | `sec-`   |
| 2        | Architecture | HIGH     | `arch-`  |
| 3        | Style        | LOW      | `style-` |

**Filenames:**

- `rules/sec-no-hardcoded-creds.md`
- `rules/arch-hexagonal-layers.md`
- `rules/style-naming-conventions.md`
