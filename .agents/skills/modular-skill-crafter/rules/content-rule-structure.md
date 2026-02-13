---
title: Consistent Rule Format
impact: HIGH
impactDescription: A standardized format (Why/Incorrect/Correct) ensures that rules provide actionable, clear, and unambiguous advice for the agent.
tags: content, formatting, rules
---

# Consistent Rule Format

## Why it matters

Agents perform better when instructions follow a consistent pattern. The "Incorrect vs Correct" comparison is a powerful way to disambiguate similar concepts and prevent common mistakes.

## Incorrect Example

writing a rule as a wall of text:

"You should always use camelCase because it is standard. Don't use snake_case."

## Correct Example

Using the structured sections:

```markdown
# Rule Name

## Why it matters

Explanation of the importance...

## Incorrect Example

variable_name = "value"

## Correct Example

variableName = "value"
```
