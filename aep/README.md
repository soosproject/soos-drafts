# AEP — Agentic Execution Protocol

**Draft:** [draft-sato-soos-aep-00](https://datatracker.ietf.org/doc/draft-sato-soos-aep/)
**Status:** Active — IETF Datatracker
**Vienna tier:** Tier 2 (Vienna important — due June 21)
**Web page:** https://soosproject.ai/drafts/aep

## What this draft specifies

AEP defines the governed execution loop for AI agents operating under delegated authority. It specifies the five-step loop (SENSE, REASON, PLAN, ACT, OBSERVE), the session lifecycle state machine (INITIALIZING → ACTIVE → HEM_PENDING → RESUMED | TERMINATED), the GEC Query Interface for pre-ACT authorization, and the Context Package format.

When an autonomous AI agent takes an irreversible action — sends a wire transfer, deletes a record, submits an order — there is currently no standard that governs how that action was authorized, whether a human approved it, or whether the audit trail can be trusted.

## Files in this directory

| File | Description |
|---|---|
| `draft-sato-soos-aep-00.txt` | Current draft text (to be added) |
| `CHANGELOG.md` | Version history |

## Key relationships

- **IDP** — issued at each PLAN step
- **HEM** — HEM_PENDING is the AEP session state during human escalation
- **GAR** — every AEP transition produces a governance audit record
- **MAD** — delegation context for the AEP session

## SOOS Project

[soosproject.ai](https://soosproject.ai) · [soosproject.com](https://soosproject.com)
Apache 2.0 License · MyAuberge K.K.
