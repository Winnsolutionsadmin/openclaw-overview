# Decisions (ADRs)

Architecture / approach decisions specific to this project. One file per decision:

```
0001-single-file-html-no-build.md
0002-host-on-github-pages.md
```

## Format

```markdown
---
name: <decision title>
description: <one-line summary>
type: project
date: YYYY-MM-DD
status: proposed | accepted | superseded | reversed
---

# <Decision title>

## Context
What forced the decision? What constraints applied?

## Decision
What did we decide? Be specific.

## Alternatives considered
What else was on the table? Why did we not pick them?

## Consequences
What does this lock in or rule out going forward?

## Revisit when
If a condition changes that should make us re-open this decision, name it.
```

## Why ADRs

So v2/v3/v4 of this project doesn't re-litigate the same arguments. If we ever say "wait, why did we pick X?" — the answer is in this folder.
