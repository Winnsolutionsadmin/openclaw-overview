# openclaw-overview

## COLD-START RITUAL (read on the first message of every session)

1. Read this entire file.
2. Read `memory-bank/activeContext.md` for the live state — what the last session did, where artifacts live, what open questions are blocking, what's next.
3. If working on a deliverable, also read `memory-bank/lessons.md` for any folder-specific dos/don'ts.
4. If `memory-bank/activeContext.md` and this file conflict, trust `activeContext.md` for state and trust this file for rules / standing instructions.
5. At session end, run `/wrap-session` to refresh `memory-bank/activeContext.md` and audit in-flow captures.

## What this is

A single-file, self-contained interactive HTML slide deck — "The Clawdia System / OpenClaw System — Comprehensive Overview" — that documents Jarred's OpenClaw (Clawdia) personal-AI infrastructure end to end. The deck walks through the system architecture, the 13-agent roster, the 38-entry belief system, the dual-layer CRM, email intelligence, Growing Mindfully operations, the Winn AI Labs product engine, the autonomy/self-healing framework, finance/compliance monitoring, the voice + content pipeline, the 37 cron jobs, infrastructure/data layer, a complete use-case map, build timeline, cost/performance notes, and a roadmap. It is the explainer presentation for the whole OpenClaw stack.

**Type:** published-deploy (static HTML deck pushed to GitHub at `Winnsolutionsadmin/openclaw-overview`).

**Status:** active / published. Everything lives in one `index.html` (~93 KB) — no build step, no dependencies, no package manifest; styling is inline CSS and Inter is pulled from Google Fonts at runtime. Last rebuilt with the "Comprehensive rebuild: belief system, CRM deep dive, voice profile, content pipeline, all use cases" commit.

## Memory

Project state lives in `memory-bank/`. Start at `memory-bank/MEMORY.md` (index), then `memory-bank/activeContext.md` (where the last session left off). Behavior rules come from the macro fileset — not restated here. This file holds project-local context only.
