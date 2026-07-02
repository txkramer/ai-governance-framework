# Fable Overhaul — ai-governance-framework — 2026-07-01

## Summary

Public docs/policies repo — treated as docs quality + structure per the playbook. Healthy content; one real structural problem fixed: a full byte-identical duplicate of every document lived in a legacy `files/` tree (guaranteed future drift). Local AI tooling files (CLAUDE.md, .claude/, graphify-out/) are now gitignored so they never publish to the public repo.

## Restore point

Tag: `pre-fable-overhaul-20260701` @ `9b55323` → `git reset --hard pre-fable-overhaul-20260701`. ⚠ Local-only until pushes unblocked.

## Changes

- **Structure:** removed `files/` — 11 byte-identical duplicates of the categorized docs plus the pre-reorg README (verified `diff -q` identical before deletion; nothing links to them).
- **Hygiene (public repo):** `.claude/`, `CLAUDE.md`, `graphify-out/` gitignored — local tooling, not framework content.
- **Docs quality:** README internal links all resolve (checked programmatically). Content read: coherent, consistent voice, no secrets/PII, no stale internal hostnames.
- Not applicable: security/tests/frontend/build (no code).

## Verification

- "Builds/boots" N/A (docs). Link integrity ✓. Tree clean ✓.
- ultrareview: low value for a docs repo — skipped deliberately.

## ⚠ Needs Steven

- Push `master` + tag when pushes are unblocked (note: default branch here is `master`, not `main`).
