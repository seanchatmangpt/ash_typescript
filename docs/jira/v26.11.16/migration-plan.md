# ash_typescript migration plan v26.11.16

Standing: UNVERIFIED

## Identity
- Path: /Users/sac/ash_typescript
- Remote: https://github.com/seanchatmangpt/ash_typescript (fork of ash-project/ash_typescript)
- Branch: main@5d6e80a tracking origin/main ; last commit 2026-11-05 ; 1034 commits ; 12 MB
- Languages/build: Elixir / mix (mix.exs)
- Nested repos: none

## Observed state
- Dirty 0, untracked 0; ahead 0 / behind 0; stash 0; unpushed branches 0
- No _build or deps present; no submodules

## What it is
AshTypescript: automatic TypeScript type/client generation for Ash resources and actions.
This is a fork of the upstream ash-project library; local history is upstream's.

## Classification
ACTIVE per census, but evidence suggests VENDOR-like fork: no local-only commits observed.

## Migration risk
NONE. Fully clean and pushed; nothing exists locally that is not on the remote.

## Recommended action
CLONE-FRESH
1. Nothing to commit. Do not copy the directory.
2. On new machine: `git clone https://github.com/seanchatmangpt/ash_typescript`
3. Optionally add upstream: `git remote add upstream https://github.com/ash-project/ash_typescript`

## First commands on the new machine
`mix deps.get && mix compile && mix test`

## See Also
- /Users/sac/docs/jira/v26.11.16/README.md (master index)
