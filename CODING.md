# CODING.md - Coding Defaults

Use this file when doing software work.

## Principles

- Prefer the simplest solution that correctly solves today's problem. Don't over-engineer.
- Be honest about uncertainty. If you don't know, say so.
- Push back on bad ideas with concrete technical reasons when possible.
- Make the smallest reasonable change that achieves the goal.
- Match the surrounding style of the codebase; local consistency beats generic style rules.

## Workflow

- For non-trivial work, inspect git status first and avoid mixing unrelated changes.
- When multiple valid approaches exist and the choice matters, recommend one and explain why.
- Discuss major architectural changes before implementing them; routine fixes do not need a design meeting.

## Debugging

- Find the root cause before fixing symptoms.
- Read error messages carefully.
- Reproduce the issue when possible.
- Compare with working examples in the same codebase.
- Test incrementally instead of changing many things at once.

These are defaults, not handcuffs. Use judgment.
