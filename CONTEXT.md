# TheJambo/awesome-testing context
> refreshed 2026-09-24 | upstream default: master @ 2c20cf4f277978888f681abf70aef383e24227c6

## Identity & policies
- upstream: TheJambo/awesome-testing, default branch `master`, primary language Markdown (awesome list), English-first (yes — README/CONTRIBUTING in English).
- CLA/DCO: none (no CLA bot, no DCO sign-off in CONTRIBUTING).
- AI-assisted PR policy: unstated (no AI policy found; no ai_disclosure_required).
- signed commits required: no.
- PR template: none (no .github/PULL_REQUEST_TEMPLATE.md, no org default). Use pipeline fallback body.
- external tracker: github.

## Conventions (verified from merged PRs)
- branch naming: `add-<name>` or `patch-1` for additions; no strong fix-branch pattern — use `fix/<kebab-description>` for cleanup.
- commit style: plain imperative ("Add X to Y", "Update README.md").
- test command: none (markdown-only awesome list). CI = GitHub Actions dead-link checker (restqa/404-links@2.2.0) on push to master + PR.
- how outside PRs get merged: responsive; 17 recent external merges in 30-PR sample; additions merged quickly.

## Maintainer picture
- single maintainer (TheJambo); active (pushed 2026-09-04).
- areas actively working: adding new tools to the list (Test Data Management, UI & E2E).

## Issue-area health
- 13 open issues, all "Add <tool> to <section>" self-promotions with 0 comments (no maintainer engagement). #128 (Polarity markdown line) is a vague screenshot-only report. #220 (Correct Agent QA license description) is a documented, specific, verifiable docs fix.

## Gap ledger (dedupe — READ FIRST, never re-pick)
- `2026-09-04` self-found trivial-fix pass — outcome: pr-opened (fork PR #2) — packed 8 typos + 1 broken markdown link in README.md; all verified present in current upstream, deduped (no upstream PR touches these strings). Promoted + merged upstream as #229.
- `2026-09-24` refresh: upstream master moved b7c701c -> 2c20cf4 (PR #229 typos and #240 duplicate-entry both merged; plus tool additions #231/#232/#237/#238). Fork PR #4 (agent-qa license) still open on fork, not yet promoted. PR #2 merged upstream as #229; PR #5 merged upstream as #240 on 2026-09-13.
- `2026-09-08` issue #220 (Correct Agent QA license description) — outcome: pr-opened (fork PR #4) — README called agent-qa "Open-source" but its license is FSL-1.1-ALv2 (source-available, not OSI-approved); verified against vostride/agent-qa LICENSE.md; changed to "Source-available". Deduped: no open/closed/merged upstream PR touches this string.
- `2026-09-09` self-found repo-audit gap (duplicate entry) — outcome: pr-opened (fork PR #5) — the Manning book "Chaos Engineering" was listed twice in the Books section (same URL, 3 lines apart); removed the second, more generic entry. Deduped: no open/closed/merged upstream PR addresses the duplicate (PR #20 added the first entry; e832123 added the second).

- `2026-09-24` trivial/minor-fix loop pass — outcome: skipped (fewer than 3 genuine fixes after an exhaustive whole-repo hunt) — fresh full scan of README/CONTRIBUTING/workflows/LICENSE/CoC: codespell clean (only "Lastest" and "TestNG", both genuine product names), no duplicated words, no stale command references, and a live HTTP sweep of all 185 external links found exactly one genuine 404 (`https://mockhero.dev`, product defunct — mockhero.io/www/app/docs/api all fail; no replacement URL, so the only possible fix would delete the whole entry = beyond a trivial link swap). Two same-URL repeats (Polarity, Learn to Code) are deliberate cross-listings in different sections with distinct descriptions (consistent with Keploy/MockServer), not accidental duplicates — not fixed. No CONTRIBUTING policy signal that this run needs (bans_trivial false, no CLA/signup, English-first).

## Mined gaps (discovered, not yet attempted)
- `2026-09-04` README typos + broken link (see PR #2 diff) — status: attempted
- `2026-09-08` docs-grounded: agent-qa license mislabeled "Open-source" (issue #220) — status: attempted
- `2026-09-09` docs: duplicate "Chaos Engineering" book entry in Books section (same Manning URL twice) — status: attempted
- `2026-09-24` mockhero.dev dead link — status: dropped (only genuine 404 found; no working replacement URL; removing the whole entry exceeds trivial-link scope)
- `2026-09-24` Polarity + Learn-to-Code same-URL repeats — status: dropped (deliberate cross-listings, not accidental duplicates; not in scope)
