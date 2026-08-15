# grok-writing-skills
A lightweight skill set for AI-assisted fiction writing. It separates character consistency, story continuity, narrative reasoning, scene craft, language quality, and discovery into focused modules that can be loaded only when needed.

## Design Principles

- Give each problem one primary skill owner.
- Load core skills by default; add scene and discovery skills only when needed.
- Constrain the reasons behind character behavior without predetermining plot outcomes.
- Treat examples as illustrations, never as templates that must be reproduced.
- Perform routing and reasoning internally; output the story unless analysis is requested.

## Repository Structure

```text
writing-skills/
├── README.md
├── WRITING_SKILLS_GUIDE.md
├── core/
│   ├── character-canon-usage.md
│   ├── novel-continuation.md
│   └── story-reasoning-narrative-control.md
├── scene/
│   ├── immersive-tension.md
│   ├── sex-scene-narrative.md
│   └── orgasm-control-narrative.md
├── discovery/
│   └── blind-box-discovery.md
└── quality/
    ├── natural-prose-dialogue-quality-gate.md
    ├── subtext-cinematic-behavior.md
    └── translation-fidelity-fluency-style.md
```

## Quick Start

1. Read [`WRITING_SKILLS_GUIDE.md`](WRITING_SKILLS_GUIDE.md) and select the appropriate stack.
2. For a normal new scene, use Character Canon + Story Reasoning.
3. Add Novel Continuation when extending an existing story.
4. Add skills from `scene/` or `discovery/` only when the scene genuinely needs them.
5. Run Natural Prose & Dialogue Quality Gate after drafting Chinese fiction.
6. For translation or cross-language adaptation, use Translation Fidelity, Fluency & Style instead.

These concise, model-agnostic specifications can be used as system or developer prompt modules, or adapted into skill packages for a specific agent platform. Store the actual character canon separately; this repository defines how canon should be used.

## Content Note

The adult-scene skills under `scene/` apply only to fictional adults and assume clear boundaries, character integrity, relationship context, and narrative consequences.

