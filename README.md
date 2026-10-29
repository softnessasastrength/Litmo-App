# Litmo-App — _muse

**_muse note:** This repository was prepared by Muse (_muse) from the original
`softnessasastrength/Litmo` repo, for Branden's review. It is a separation
proposal in code form, not a launch, not therapy, and not a safety guarantee.

## What this repo is

A vetted, small-community, consent-first app for non-sexual, platonic
connection — built only from Bucket B machinery in the original repo, plus
rewritten public stubs in `docs/public-stubs/`.

- Consent is specific, mutual, and revocable. It is never inferred from a
  match, a profile, or a history.
- Stopping is immediate and needs no justification.
- Trust history is context, never certification of safety.
- This app does not diagnose, treat, certify safety, or replace professional
  care. It coordinates consent and communication; it does not guarantee
  anyone's safety.

## What this repo is NOT

- It is **not** the Private Dojo. No Private Dojo (Bucket A) material is in
  this repo: no personal containment, attachment-repair, ritual, dojo,
  cathedral, or personal-mode content.
- It is **not** a public launch. The items in `LEGAL_AND_SAFETY.md` are OPEN.
- It is **not** an open marketplace. The intended first form, if Branden
  approves it, is a vetted, hosted, small community — not open matching
  between strangers.

## Contents

- `shared/src/` — consent engine, consent snapshot, session lifecycle,
  session consent state machine (renamed from the original's "nuclear"
  naming for public use, logic unchanged), constitution invariants, haptic
  language. Copied with attribution to `softnessasastrength/Litmo`.
- `backend/` — consent, compatibility, and session-snapshot routes/services.
- `app/services/`, `app/components/` — public subset only: auth, age gate,
  moderation, reporting, appeals, blocks, safety-ops, emergency stop,
  session, proximity, NFC, QR invite, local vault, privacy.
- `docs/` — Bucket B docs only: consent flow, snapshot system, withdrawal
  and emergency stop, continuous consent, onboarding consent, safety-ops,
  trauma-informed safety, security, encryption, auth, trust, proximity,
  privacy/compliance drafts, architecture.
- `docs/public-stubs/` — rewritten Bucket C stubs (new public wording, not
  copies of personal wording).
- `LEGAL_AND_SAFETY.md` — the 10 open items. All marked OPEN.
- `SOURCE_AND_LABELLING_muse.md` — source, attribution, _muse labels used,
  and what was skipped and why.

## Licence / monetization — OPEN, undecided

No `LICENSE` and no `NON_MONETIZATION_COVENANT.md` have been copied into
this repo. Both are undecided, per the separation proposal, and are stated
as open in `LEGAL_AND_SAFETY.md`. Do not assume a licence from the original
repo applies here until Branden decides.

## Status

Proposal-stage, for Branden's monitoring and approval. No Facebook post,
no announcement, and no public launch are part of this repo.
