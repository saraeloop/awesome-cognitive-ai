# Contributing

Thanks for helping make cognitive-AI more **inspectable** and **reliable**.

## Checklist

- [ ] Pick the right category.
- [ ] Add `catalog/items/<category>/<name>.yaml` (see schema & example).
- [ ] Include: description, license, repo URL, docs URL, **last_commit**, **artifacts**, **eval_signals**, **claims_with_citations**.
- [ ] If you are a maintainer of the project, set `disclosure: Maintainer-Contributed`.
- [ ] Run local checks:
  - `pnpm i && pnpm validate`
  - `pnpm build-readme`

## Entry quality guidelines

- **Neutral tone**; no hype language.
- **Falsifiable claims only** (with citations).
- Prefer entries with **active maintenance** (commits in last 12 months).
- Prefer entries that emit **artifacts** (traces, logs, memory, eval).

## Review policy

PRs require:
- Passing CI (schema, awesome-lint, links).
- At least one reviewer approval.
- PR template filled.

Thanks! 🙌