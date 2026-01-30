## How to install

In Claude Code, run:

```
/plugin marketplace add glgh/claude-fast-and-slow-plugin
```

Then run:

```
/plugin install fast-and-slow@glgh
```

Then restart Claude Code to load the plugin.

## Commands 

```
/fast      # prototype mode — move fast, break things, bias for action
/slow      # production mode — careful, deliberate changes, slow and steady
/reset     # return to default behavior
```

## Modes

### `/fast` — Prototype Mode
- Bias for action, minimal interruptions
- Breaking changes and refactors are fine
- Only pause for significant, irreversible decisions
- Unless instructed otherwise, don't maintain backward compatibility

### `/slow` — Production Mode
- Ask before making non-obvious changes
- Maintain backward compatibility
- Incremental, reviewable commits
- Consider edge cases and failure modes

### `/reset` — Default
- Return to baseline Claude behavior. A reasonable middle ground—thoughtful but not overly careful.
