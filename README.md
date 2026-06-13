# design-thinking-practitioner-skill

> An AI agent skill that facilitates IBM Enterprise Design Thinking sessions — guiding teams through the Loop (Observe, Reflect, Make), writing and pressure-testing Hills, running Playbacks, recruiting Sponsor Users, and running ~25 named toolkit activities live.

```
npx skills add s1dd4rth/design-thinking-practitioner-skill
```

Works with Claude Code, Cursor, Windsurf, Cline, Copilot, and other agents that support the [agent skills standard](https://agentskills.io).

---

## What it does

Instead of explaining IBM Enterprise Design Thinking, this skill turns your AI agent into an active workshop facilitator: it locates the team's current position in the Loop, picks the right named activity, asks one focused question at a time, fills artifact templates with your answers, and flags framing problems — even when you ask for a fast draft.

**Modes:**
- **Facilitated** (default) — conversational, one question at a time, builds artifacts progressively.
- **Fast path** — say "just write it" and the skill produces the artifact immediately from what you've shared, with inline flags on anything that violates EDT principles.

---

## Covers the full IBM Enterprise Design Thinking framework

| Layer | What's inside |
|---|---|
| **The Principles** | User outcomes · Restless reinvention · Diverse empowered teams — as live drift-correction tools |
| **The Loop** | Observe → Reflect → Make — question banks, activity prompts, loop-closing decisions |
| **The Keys** | Hills (Who/What/Wow anatomy + pressure-test) · Playbacks (milestone sequence) · Sponsor Users (criteria + facilitation) |
| **The Toolkit** | ~25 named activities: Empathy Map, As-Is/To-be Scenario Maps, Needs Statements, Big Idea Vignettes, Cognitive Walkthrough, Feedback Grid, AI Essentials, Retrospectives, and more |

---

## Folder structure

```
design-thinking-practitioner-skill/
├── SKILL.md                          # Core facilitator logic & routing
├── design-thinking-practitioner.skill  # Compiled skill definition
└── references/
    ├── principles.md                 # Three principles as drift-correction tools
    ├── the-loop.md                   # Observe / Reflect / Make + question banks
    ├── the-keys.md                   # Hills, Playbacks, Sponsor Users + templates
    └── the-toolkit.md                # ~25 named activities mapped to Loop modes
```

---

## Example triggers

- "Help me run a design thinking session"
- "We don't know our users yet — where do we start?"
- "Write a Hill for [problem]"
- "We have fifty pages of research notes — help us synthesize"
- "Plan a Playback for our leadership review next week"
- "Should we even use AI for this problem?"
- "End-of-sprint retro — facilitate it"

---

## Attribution

IBM Enterprise Design Thinking is a framework developed by IBM. This skill is an independent facilitator implementation for AI agents and is not an official IBM product. All framework concepts are used for educational and facilitation purposes.

Built by [Siddarth Kengadaran](https://theproductguy.xyz) · Part of the [agent skills](https://agentskills.io) ecosystem.
