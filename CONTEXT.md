# TheJambo/awesome-testing context
> refreshed 2026-09-08 | upstream default: master @ b7c701cb4f22207318f030c828d57f69ad21d403

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
- `2026-09-08` issue #220 (Correct Agent QA license description) — outcome: pr-opened (fork PR #3) — README called agent-qa "Open-source" but its license is FSL-1.1-ALv2 (source-available, not OSI-approved); verified against vostride/agent-qa LICENSE.md; changed to "Source-available". Deduped: no open/closed/merged upstream PR touches this string.

## Mined gaps (discovered, not yet attempted)
- `2026-09-04` README typos + broken link (see PR #2 diff) — status: attempted
- `2026-09-08` docs-grounded: agent-qa license mislabeled "Open-source" (issue #220) — status: attempted
