# IDP — Intent Declaration Primitive

**Draft:** [draft-sato-soos-idp-04](https://datatracker.ietf.org/doc/draft-sato-soos-idp/)
**Status:** Active — IETF Datatracker
**Vienna tier:** Tier 1 (Vienna critical — due June 14)
**Web page:** https://soosproject.ai/drafts/idp

## What this draft specifies

IDP defines the per-step signed intent declaration that an AI agent issues before each action. It specifies the IDP token format (profiled JWT), the required context-binding claims (`session_id`, `gec_instance_id`, `action_sequence_number`), the cross-context replay threat model, and the GEC validation rules.

Every action an AI agent takes is a decision. Right now, none of those decisions are signed.

## Files in this directory

| File | Description |
|---|---|
| `draft-sato-soos-idp-04.txt` | Current draft text (to be added) |
| `CHANGELOG.md` | Version history |

## Key relationships

- **AEP** — IDP is issued at each AEP PLAN step before ACT
- **HEM** — the triggering IDP is included in the HEM escalation request
- **GAR** — IDP tokens are referenced in governance audit records
- **KIA** — `gec_instance_id` in IDP is sourced from the KIA attestation record

## SOOS Project

[soosproject.ai](https://soosproject.ai) · [soosproject.com](https://soosproject.com)
Apache 2.0 License · MyAuberge K.K.
