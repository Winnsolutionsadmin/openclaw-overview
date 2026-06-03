---
name: project brief — openclaw-overview
description: What this project is, why it exists.
type: project
---

# openclaw-overview

**Category:** ws (Winn.solutions)
**Type:** published-deploy (static HTML deck on GitHub — `Winnsolutionsadmin/openclaw-overview`)
**Status:** active / published

## Purpose

The explainer presentation for Jarred's OpenClaw (Clawdia) personal-AI infrastructure. It is a single self-contained interactive HTML slide deck — titled "The Clawdia System / OpenClaw System — Comprehensive Overview" — that lays out the entire stack so it can be understood and shown at a glance. Slides cover: what the system is, the system architecture, the 13-agent roster, the 38-entry belief system across 4 domains, the beliefs → content-curation → growth loop, the dual-layer CRM, email intelligence, Growing Mindfully operations, the Winn AI Labs 47-product revenue engine, the autonomy + self-healing framework, finance/compliance monitoring, the voice profile + content pipeline, the 37 daily cron jobs, the infrastructure/data layer, a complete use-case map, the 36-day build timeline, cost/performance/optimization, and a "what's next" roadmap.

## Key tech

- Single file: `index.html` (~93 KB). No `package.json`, no build tooling, no dependencies.
- Inline CSS (dark theme, CSS custom properties); Inter font loaded from Google Fonts at runtime.
- Vanilla JS deck navigation (slides with active/exit transitions, progress bar, slide counter, prev/next buttons).
- Hosted on GitHub (`origin` = `https://github.com/Winnsolutionsadmin/openclaw-overview.git`, branch `main`).

## Context not obvious from files

<!--
Things that only exist in Jarred's head right now:
- Audience for the deck (internal reference vs. external pitch)
- Whether it's served via GitHub Pages and the live URL, if any
- How it should stay in sync as the underlying OpenClaw system evolves
-->
