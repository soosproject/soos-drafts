# FAIP — Federated Agent Intelligence Protocol

**Draft:** [draft-sato-soos-faip-00](https://datatracker.ietf.org/doc/draft-sato-soos-faip/)
**Status:** Active — IETF Datatracker
**Vienna tier:** Tier 3 (Launch complete — due June 28)
**Web page:** https://soosproject.ai/drafts/faip

## What this draft specifies

FAIP defines the privacy-preserving federated aggregation protocol for AI agent behavioral data across organizational boundaries. It specifies the aggregation round model, the VDAF integration, minimum participation thresholds, round cancellation on participant revocation, and the k-anonymity architecture.

## Files in this directory

| File | Description |
|---|---|
| `draft-sato-soos-faip-00.txt` | Current draft text (to be added) |
| `CHANGELOG.md` | Version history |

## Key relationships

- **GAR** — FAIP round results and cancellations are recorded in GAR
- **MAD** — session revocation of a FAIP participant triggers round withdrawal
- **draft-irtf-cfrg-vdaf** — VDAF is the aggregation primitive FAIP profiles

## SOOS Project

[soosproject.ai](https://soosproject.ai) · [soosproject.com](https://soosproject.com)
Apache 2.0 License · MyAuberge K.K.
