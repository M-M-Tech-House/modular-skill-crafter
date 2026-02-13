---
title: Modular Rule Files
impact: HIGH
impactDescription: Breaking rules into individual files allows for better organization, easier updates, and more targeted referencing by the agent.
tags: architecture, modularity, rules
---

# Modular Rule Files

## Why it matters

Large, monolithic instruction files are hard to parse and maintain. Modular rule files allow the agent to load only the context it needs and makes it easier to add or deprecate specific rules without rewriting the entire skill.

## Incorrect Example

Defining all 20 rules inside the main `SKILL.md` file.

## Correct Example

Creating a `rules/` directory and placing each rule in its own file (e.g., `rules/code-style.md`, `rules/arch-layers.md`), then referencing them in the `SKILL.md` Quick Reference section.
