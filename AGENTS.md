# AGENTS.md

## Start here

Before consequential work:

1. Read `README.md`.
2. Read `.observstory/coordination.json`.
3. If an Observstory snapshot is available, inspect it for overlap, waiting and recent work before changing shared areas.
4. Check open PRs / branches touching the area you plan to modify.
5. Keep problem claims, evidence, experiments and implementation distinguishable.

## Hackathon operating rule

Do not optimize for maximum isolated agent throughput.

Prefer:

```
explore → return proposition → collide → agree → execute
```

When two approaches conflict, preserve the disagreement long enough to test it instead of silently choosing one.

## Evidence

For consequential claims derived from open data, capture provenance and limitations. If the data cannot support the intended conclusion, say so and change the product claim.

## Coordination

Observstory observes; it does not authorize work.

Do not invent gates, commitments or team decisions. Only add them to `.observstory/coordination.json` after explicit human agreement.
