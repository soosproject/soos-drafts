# MJWT — Mandate JWT

**Draft:** [draft-sato-soos-mjwt-00](https://datatracker.ietf.org/doc/draft-sato-soos-mjwt/)
**Status:** Active — IETF Datatracker
**Vienna tier:** Tier 3 (Launch complete — due June 28)
**Web page:** https://soosproject.ai/drafts/mjwt

## What this draft specifies

MJWT defines the attenuated delegation token format for the SOOS protocol family. It is a profile of OAuth 2.0 Token Exchange [RFC 8693] extended with the INV-4 Narrowing Property (each delegation hop must narrow, never expand, authority), audience binding to KIA-attested GEC instance identifiers, and cross-GEC replay attack prevention.

## Files in this directory

| File | Description |
|---|---|
| `draft-sato-soos-mjwt-00.txt` | Current draft text (to be added) |
| `CHANGELOG.md` | Version history |

## Key relationships

- **MAD** — MAD uses MJWT as the delegation credential at each hop in the delegation graph
- **KIA** — MJWT `aud` claim binds to the KIA-attested GEC instance identifier
- **RFC 8693** — MJWT is an RFC 8693 profile with chain semantics

## SOOS Project

[soosproject.ai](https://soosproject.ai) · [soosproject.com](https://soosproject.com)
Apache 2.0 License · MyAuberge K.K.
