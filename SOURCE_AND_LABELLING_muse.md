# Source and labelling — _muse

**_muse note:** This staging directory was prepared by Muse (_muse), for
Branden's review, from the original repo `softnessasastrength/Litmo`
(snapshot ref cited in the separation proposal:
`74a9f4a5acf3ab90bfe1e314e49fb5dc4077e96f`).

## _muse labels used in this pass

- Proposed new repo name: `Litmo-App` (fallback, if taken/confusing:
  `litmo-community`) — **NOT created in this pass**; see below.
- Intended branch name for the first push, when the repo exists:
  `initial-separation_muse`
- Intended first commit message, when pushed:
  `Initial Bucket B separation, Bucket C stubs, LEGAL_AND_SAFETY open items _muse`
- Intended PR title, if a PR is used: `Initial Litmo-App separation _muse`
- This file, `README.md`, and `LEGAL_AND_SAFETY.md` each carry a `_muse`
  note stating the separation was prepared by Muse from the original repo,
  for Branden's review.
- Renamed file: `shared/src/sessionConsent.ts` — renamed from
  `sessionConsentNuclear.ts` in the original, per the proposal's Bucket C
  naming note. Logic unchanged; rename header is in the file itself.

## Attribution

Bucket B code and docs copied here remain attributed to their source,
`softnessasastrength/Litmo`. No licence is stated for this new repo yet,
because licence is undecided — see `LEGAL_AND_SAFETY.md`. Attribution is
not a licence grant.

## What was NOT done in this pass

- **New repo NOT created.** The GitHub App integration returned:
  `403 Resource not accessible by integration` on
  `POST https://api.github.com/user/repos` for `Litmo-App`, after the
  write was approved in the tool flow. That is a permission/integration
  limit, not a labelling workaround to route around. No repo, branch,
  commit, or PR was created in this pass.
- **Original repo NOT changed.** No edit, deletion, branch, commit, or
  visibility change was made to `softnessasastrength/Litmo`.
- **No Facebook post, draft, or schedule** was made in this pass.
- **No licence/covenant copied.** `LICENSE` (MPL-2.0) and
  `NON_MONETIZATION_COVENANT.md` from the original were NOT copied here,
  and were NOT silently dropped — they are stated as OPEN in
  `LEGAL_AND_SAFETY.md`.
- **No Bucket A material copied.** See the staging log
  (`_staging_log_muse.txt`) and the skipped list below.

## Skipped, with reasons (see `_staging_log_muse.txt` for the staged-file log)

- `docs/screenshots/` — uninspected, do not copy blind.
- `app/data/` seed content — needs a file-level check, skipped.
- `docs/CHANGELOG.md` — build history, not read line-by-line, skipped.
- `supabase/` — not inventoried file-by-file, skipped.
- `pics/`, `.github/` workflows — not inspected, skipped.
- `documents/GOVERNANCE.md`, root `GOVERNANCE.md` — not read in full, skipped.
- The personal gate file (Bucket A, redacted in the proposal, not named
  here) — NOT copied, NOT read in detail, NOT quoted.
- Bucket B app routes (`app/app/` public screens), wiki files, most ADRs,
  and the wider `app/services/` tail beyond the staged core subset:
  NOT staged in this initial pass. They remain in the original repo,
  untouched, and are listed in the separation proposal's Bucket B outline
  for a follow-up batch once the new repo exists. Do NOT describe this
  initial staging as a complete Bucket B copy.
- `app/data/`, `app/assets/`, `app/ios/`, `app/context/`, `app/hooks/`,
  `app/config/`, `app/lib/`, theme/config files, `app/app/(tabs)/`,
  `release/`, build/validation scripts — not staged in this pass.

## Monitoring checklist for Branden

- [ ] No Bucket A slip-in: check the staged file list against the
      proposal's Bucket A list; no containment, attachment-repair,
      ritual, dojo, cathedral, or personal-mode file should appear.
- [ ] No surviving personal wording: Bucket C material here is rewritten
      stubs only, in `docs/public-stubs/` — no personal examples or
      personal scripts.
- [ ] No licence/covenant copied: confirm no `LICENSE` and no
      `NON_MONETIZATION_COVENANT.md` in the staging directory.
- [ ] No original repo changed: original `Litmo` untouched in this pass.
- [ ] No Facebook post made: none made in this pass.
- [ ] New repo still to create: `Litmo-App` (or `litmo-community`)
      requires either an expanded GitHub App installation / manual
      creation by Branden, or another authorised creation route — then
      this staged directory can be pushed in one commit on branch
      `initial-separation_muse` with the commit message above.
