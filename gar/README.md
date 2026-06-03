# GAR — Governance Audit Record

**Draft:** [draft-sato-soos-gar-01](https://datatracker.ietf.org/doc/draft-sato-soos-gar/)
**Status:** Active — IETF Datatracker
**Vienna tier:** Tier 2 (Vienna important — due June 21)
**Web page:** https://soosproject.ai/drafts/gar

## What this draft specifies

GAR defines the tamper-evident, causally-ordered governance audit record for AI agent systems. It specifies the event schema, the causal ordering extension (`causal_parent_id`, `session_sequence_number`, `governance_decision`), the non-suppressibility guarantee, and the SCITT profile for governance events.

When your AI agent does something harmful, can you prove exactly what it decided and why? GAR is the tamper-evident record that answers that question.

## Files in this directory

| File | Description |
|---|---|
| `draft-sato-soos-gar-01.txt` | Current draft text (to be added) |
| `CHANGELOG.md` | Version history |

## Key relationships

- **AEP** — every AEP transition produces a GAR entry
- **HEM** — all HEM decisions are recorded in GAR
- **CAP** — all CAP enforcement decisions produce non-suppressible GAR entries
- **SCITT** — GAR is a domain-specific SCITT application for governance events

## SOOS Project

[soosproject.ai](https://soosproject.ai) · [soosproject.com](https://soosproject.com)
Apache 2.0 License · MyAuberge K.K.
