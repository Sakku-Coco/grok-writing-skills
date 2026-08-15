# Writing Skills

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

### Create Character Canon

1. Give Grok 4.5 the relevant conversations, character notes, and story chapters.
2. Run `Build Character Canon`.
3. Generate one profile per character using `Character Canon Template`.
4. Review inferred and unresolved claims.
5. Approve the profiles before using them for fiction writing.

### Write Fiction

1. Load the approved character profiles.
2. Apply Character Canon Usage.
3. Add Novel Continuation when extending an existing story.
4. Run Story Reasoning & Narrative Control.
5. Add scene or discovery skills only when needed.
6. Finish with the appropriate quality gate.

Do not run Build Character Canon during ordinary scene generation.

These concise, model-agnostic specifications can be used as system or developer prompt modules, or adapted into skill packages for a specific agent platform. Store the actual character canon separately; this repository defines how canon should be used.

## Content Note

The adult-scene skills under `scene/` apply only to fictional adults and assume clear boundaries, character integrity, relationship context, and narrative consequences.
