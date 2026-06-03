# HEM — Human Escalation Mechanism

**Draft:** [draft-sato-soos-hem-04](https://datatracker.ietf.org/doc/draft-sato-soos-hem/)
**Status:** Active — IETF Datatracker
**Vienna tier:** Tier 1 (Vienna critical — due June 14)
**Web page:** https://soosproject.ai/drafts/hem

## What this draft specifies

HEM defines the kernel-level protocol that governs what happens when an AI agent reaches a decision boundary requiring human review. It specifies the `HEM_PENDING` session state, the structured escalation request format, the ordered designation chain of human principals, five human decision types (APPROVE, APPROVE_WITH_CONSTRAINTS, REDIRECT, TERMINATE, DEFER), and the timeout model governing chain exhaustion.

## Files in this directory

| File | Description |
|---|---|
| `draft-sato-soos-hem-04.txt` | Current draft text (to be added) |
| `CHANGELOG.md` | Version history |

## Key relationships

- **AEP** — HEM_PENDING is a state in the AEP session lifecycle
- **GAR** — all HEM decisions are recorded in the governance audit trail
- **IDP** — the triggering IDP is included in the HEM escalation request
- **MAD** — session revocation during HEM_PENDING defers to MAD §X

## SOOS Project

[soosproject.ai](https://soosproject.ai) · [soosproject.com](https://soosproject.com)
Apache 2.0 License · MyAuberge K.K.
