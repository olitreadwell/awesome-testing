# TheJambo/awesome-testing context
> refreshed 2026-09-04 | upstream default: master @ 29f9e688a423972135242dd6c3f42703377c6410

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
- single maintainer (TheJambo); active (pushed 2026-09-03).
- areas actively working: adding new tools to the list (Test Data Management, UI & E2E).

## Issue-area health
- No open issues tracked for this pass; self-found trivial fixes only.

## Gap ledger (dedupe — READ FIRST, never re-pick)
- `2026-09-04` self-found trivial-fix pass — outcome: pr-opened (fork PR #2) — packed 8 typos + 1 broken markdown link in README.md; all verified present in current upstream, deduped (no upstream PR touches these strings).

## Mined gaps (discovered, not yet attempted)
- `2026-09-04` README typos + broken link (see PR #2 diff) — status: attempted
