# 🔵 Design Thinking Practitioner Skill

An AI agent skill that facilitates **IBM Enterprise Design Thinking** sessions — guiding teams through the Loop (Observe, Reflect, Make), writing and pressure-testing Hills, planning Playbacks, recruiting Sponsor Users, and running ~25 named toolkit activities live.

## 🚀 Install

```
npx skills add s1dd4rth/design-thinking-practitioner-skill
```

*Works with Claude Code, Cursor, Windsurf, Cline, Copilot, and [other agents](https://skills.sh).*

## 🧠 What it does

Instead of explaining the framework, this skill turns your AI agent into an active workshop facilitator: it locates where the team is in the Loop, picks the right named activity, asks one focused question at a time, fills artifact templates with your answers, and flags framing problems — even when you ask for a fast draft.

**Two modes:**
- **Facilitated** (default) — conversational, one question at a time, builds artifacts progressively.
- **Fast path** — say "just write it" and the skill produces the artifact immediately from what you've shared, with inline flags on anything that violates EDT principles.

## ✨ Framework coverage

| Layer | What's inside |
|---|---|
| **The Principles** | User outcomes · Restless reinvention · Diverse empowered teams — as live drift-correction tools |
| **The Loop** | Observe → Reflect → Make with question banks, activity prompts, and loop-closing decisions |
| **The Keys** | Hills (Who/What/Wow anatomy + pressure-test) · Playbacks (milestone sequence) · Sponsor Users (criteria + facilitation) |
| **The Toolkit** | ~25 named activities: Empathy Map, As-Is/To-be Scenario Maps, Needs Statements, Big Idea Vignettes, Cognitive Walkthrough, Feedback Grid, AI Essentials, Retrospectives, and more |

## 🛠️ Try it

After installing, try prompts like:

- *"Help me run a design thinking session for our support tool."*
- *"We don't know our users yet — where do we start?"*
- *"Write a Hill for [problem]."*
- *"We have fifty pages of research notes. Help us synthesize."*
- *"Plan a Playback for our leadership review next week."*
- *"Should we even use AI for this problem?"*
- *"End-of-sprint retro — facilitate it."*

## 📂 Skill structure

```
design-thinking-practitioner-skill/
├── SKILL.md                                  # Core facilitator logic & routing
├── design-thinking-practitioner.skill        # Compiled skill definition
└── references/
    ├── principles.md                         # Three principles as drift-correction tools
    ├── the-loop.md                           # Observe / Reflect / Make + question banks
    ├── the-keys.md                           # Hills, Playbacks, Sponsor Users + templates
    └── the-toolkit.md                        # ~25 named activities mapped to Loop modes
```

## 🔗 Coexists with

- **[babok-skill](https://github.com/s1dd4rth/babok-skill)** — BABOK is the business analysis frame for *what* requirements and solutions to pursue; Design Thinking is the human-centred process for *discovering* the right problem and generating solutions worth pursuing. Use DT for discovery and alignment, BABOK for rigorous analysis and documentation.
- **[ooux-skill](https://github.com/s1dd4rth/ooux-skill)** — Once a Hill is written and a To-be scenario is sketched, OOUX picks up for modelling the objects, relationships, and CTAs inside that future experience. DT frames the problem; OOUX structures the solution.

## 📜 Attribution

**IBM Enterprise Design Thinking** is a framework developed by IBM. This skill is an independent facilitator implementation for AI agents and is not an official IBM product. All framework concepts are used for educational and facilitation purposes.

Built by [Siddarth Kengadaran](https://theproductguy.xyz) using the Anthropic [skill-creator](https://github.com/anthropics/skills) framework.

## ⚖️ License

MIT — see [LICENSE](LICENSE)
