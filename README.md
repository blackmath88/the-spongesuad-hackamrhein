# The Sponge Squad — Hack am Rhein 2026

Shared working repository for our Hack am Rhein team project.

The repo is intentionally set up as both a build space and a shared team memory. We expect several people — and several coding agents — to work in parallel. The goal is to move fast **without disappearing into separate agent caves**.

## Working loop

```
question
→ evidence
→ idea
→ experiment
→ prototype
→ validation
→ story
```

Keep these distinct. A polished prototype is not evidence. An interesting dataset is not yet a use case. A model output is not a decision.

## Team principle

> Explore privately. Return propositions. Collide them. Converge together. Then execute.

Use the repository to make the collisions visible.

## Suggested project structure

- `problem/` — challenge framing, users, broken decisions, assumptions
- `data/` — dataset notes, provenance, fitness checks, joins, derived artefacts
- `src/` — product / prototype implementation
- `experiments/` — cheap tests, spikes, rejected ideas, evaluation evidence
- `docs/` — architecture, decisions, notes, handoffs
- `pitch/` — demo flow, narrative, screenshots, final presentation material
- `.observstory/` — declared coordination state for the team

These folders can evolve with the project. Observstory treats them as semantic lanes rather than bureaucracy.

## Observstory

This repository is wired to [Observstory](https://github.com/blackmath88/observstory), a shared situational-awareness layer for fast parallel work.

It observes:

- overlapping unmerged work
- work that has gone stale
- dependencies / waiting
- machine-paced commit bursts
- declared team gates, decisions and commitments

It does **not** rank people or decide what the team should do.

> **Repo = truth. Observstory = see. Humans = decide.**

During a hackathon, the useful questions are simple:

- What is everyone touching right now?
- Are two people or agents unknowingly building the same thing?
- What assumption are we currently testing?
- What evidence changed our mind?
- What must be true before we commit to the demo?
- What is still open before the pitch?

The workflow creates an `observstory` artifact with the Project Map and machine-readable snapshot.

## Hackathon rhythm

We use short coordination horizons because this project lives in hours, not weeks.

Suggested gates:

1. **Problem locked** — we can state the broken decision / need in one sentence.
2. **Evidence sufficient** — we know which data supports the idea and its limits.
3. **Prototype proves the interaction** — happy path works end-to-end.
4. **Validation passed** — we have tested the core claim, not just the UI.
5. **Demo frozen** — only fixes that protect the demo after this point.

Record actual gates and commitments in `.observstory/coordination.json` when the team agrees them.

## Data principle

Hack am Rhein is an open-data hackathon, so provenance matters.

For important claims, record:

- source
- retrieval / version date when relevant
- transformation
- known quality limitations
- what conclusion the data does **not** support

The RUNO2 warm-up is our reminder: discovering that a dataset cannot support the tempting conclusion can be more valuable than forcing a ranking from noise.
