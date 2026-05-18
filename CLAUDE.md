# Jotty Android — Claude Code Instructions

## Review before proposing PRs

Before creating or pushing any PR branch, always run an Opus review of the changes using:

```
Agent(model="opus", prompt="Review these changes for correctness, edge cases, and regressions: ...")
```

Include the problem description, the old code, the new code, and relevant context (related classes, patterns used elsewhere in the codebase). Be thorough and critical.

Only proceed with the PR after the Opus review is clean or all raised issues are addressed.
