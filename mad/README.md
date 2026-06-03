# MAD — Multi-Agent Delegation

**Draft:** [draft-sato-soos-mad-01](https://datatracker.ietf.org/doc/draft-sato-soos-mad/)
**Status:** Active — IETF Datatracker
**Vienna tier:** Tier 2 (Vienna important — due June 21)
**Web page:** https://soosproject.ai/drafts/mad

## What this draft specifies

MAD defines the delegation protocol for multi-agent systems, including the delegation graph model, the INV-4 Narrowing Property (each delegation hop must narrow authority), the CAEP profile for `agent-session-revoked`, and partial-completion handling (CLEAN / PARTIAL / UNKNOWN states with natural breakpoint semantics).

## Files in this directory

| File | Description |
|---|---|
| `draft-sato-soos-mad-01.txt` | Current draft text (to be added) |
| `CHANGELOG.md` | Version history |

## Key relationships

- **MJWT** — MAD uses MJWT tokens as the delegation credential at each hop
- **AEP** — MAD session revocation supersedes AEP session lifecycle
- **GAR** — delegation graph and revocation events are audited in GAR
- **HEM** — PARTIAL completion state at revocation escalates to HEM

## SOOS Project

[soosproject.ai](https://soosproject.ai) · [soosproject.com](https://soosproject.com)
Apache 2.0 License · MyAuberge K.K.
