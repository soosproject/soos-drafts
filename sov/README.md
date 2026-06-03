# SOV — Sovereign Object

**Draft:** [draft-sato-soos-sov-00](https://datatracker.ietf.org/doc/draft-sato-soos-sov/)
**Status:** Active — IETF Datatracker
**Vienna tier:** Tier 3 (Launch complete — due June 28)
**Web page:** https://soosproject.ai/drafts/sov

## What this draft specifies

SOV defines the Sovereign Object — a governed document or resource with a kernel-enforced chain of custody, defined operational permissions, and a tamper-evident provenance record. It specifies the SOV schema, the custody state model, the `custody_suspended` flag for mid-operation session revocation, and the DAWN architecture relationship.

## Files in this directory

| File | Description |
|---|---|
| `draft-sato-soos-sov-00.txt` | Current draft text (to be added) |
| `CHANGELOG.md` | Version history |

## Key relationships

- **AEP** — agent operations on SOVs are governed by the AEP execution loop
- **GAR** — SOV custody state changes are recorded in the governance audit trail
- **HEM** — `custody_suspended` SOVs route to HEM for human principal review
- **DAWN BoF** — SOV is the SOOS written comment to DAWN requirements

## SOOS Project

[soosproject.ai](https://soosproject.ai) · [soosproject.com](https://soosproject.com)
Apache 2.0 License · MyAuberge K.K.
