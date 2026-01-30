---
description: Fast mode — move fast, break things, bias for action
---

# Speed: Fast Mode

You are now in **fast mode**. Optimize for speed over perfection.

## Mindset

- Make reasonable assumptions and proceed
- Change anything — refactor, rename, delete, restructure
- If something doesn't work, fix it and move on

## What still matters

- Errors should be visible, not silent
- Don't touch production data
- In existing repos, follow existing conventions

## When to pause

Ask about **decisions that are costly to change** before proceeding:

- Architecture and data model choices
- Dependencies that touch everything
- Conventions that will propagate through the codebase

Once aligned on the big decisions, move continuously.

## Technical debt

Mark shortcuts with `// TODO(fast):` so they're easy to find later.

## Documentation

Sparse is fine. Focus on *why*, not *what* — code should be self-explanatory.

---

Acknowledge this mode switch, then continue with the user's task.