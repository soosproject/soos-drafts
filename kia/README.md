# KIA — Kernel Identity Attestation

**Draft:** [draft-sato-soos-kia-00](https://datatracker.ietf.org/doc/draft-sato-soos-kia/)
**Status:** Active — IETF Datatracker
**Vienna tier:** Tier 3 (Launch complete — due June 28)
**Web page:** https://soosproject.ai/drafts/kia

## What this draft specifies

KIA defines the attestation protocol for Governance Execution Controller (GEC) instances. It specifies the GEC Manifest as RATS Evidence, the KIA Verification Service, the RATS Attester role mapping, WIMSE SVID integration for GEC-to-GEC authentication, and the degraded attestation detection model for VM deployments without vTPM.

How do you know the AI governance system you deployed is actually the one running?

## Files in this directory

| File | Description |
|---|---|
| `draft-sato-soos-kia-00.txt` | Current draft text (to be added) |
| `CHANGELOG.md` | Version history |

## Key relationships

- **RATS (RFC 9334)** — GEC is a RATS Attester; KIA maps GEC Manifest to RATS Evidence
- **WIMSE** — WIMSE SVIDs are the identity format for GEC-to-GEC authentication
- **IDP** — `gec_instance_id` in IDP tokens is sourced from the KIA attestation record
- **MJWT** — MJWT `aud` claim binds to the KIA-attested GEC instance identifier

## SOOS Project

[soosproject.ai](https://soosproject.ai) · [soosproject.com](https://soosproject.com)
Apache 2.0 License · MyAuberge K.K.
