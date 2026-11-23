# hidden-spec-cli-01-run-20261122

[![make.fun · hidden-spec-cli-01-run-20261122](https://make.fun/badge/hidden-spec-cli-01-run-20261122.svg)](https://make.fun/bounty/hidden-spec-cli-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=hidden-spec-cli-01-run-20261122)
[![rank](https://make.fun/badge/hidden-spec-cli-01-run-20261122/hackedbyexteam-debug/hidden-spec-cli-01-run-20261122/rank.svg)](https://make.fun/bounty/hidden-spec-cli-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=hidden-spec-cli-01-run-20261122)
[![reward](https://make.fun/badge/hidden-spec-cli-01-run-20261122/hackedbyexteam-debug/hidden-spec-cli-01-run-20261122/reward.svg)](https://make.fun/bounty/hidden-spec-cli-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=hidden-spec-cli-01-run-20261122)

mend: one patch tool for every AI edit format. It reads a patch in unified diff, SEARCH/REPLACE blocks, V4A, or JSON edits form, finds the lines each edit names at the first of three matching tiers (exact, trailing whitespace, full whitespace), and writes every change or none, printing what it changed or why it failed.

## Run it

```sh
node main.ts [--format=NAME] [--check] [--strict] [PATCH]
```

`PATCH` is a patch file, or `-` (or absent) to read the patch from standard input. `--format` picks `unified`, `search-replace`, `v4a`, `json`, or `auto` (the default, which detects the format). `--check` reports what would change without writing anything. `--strict` matches lines exactly (tier 0 only). The working directory is the root of the tree of text files the patch applies to.

---

<sub>Entered on [make.fun](https://make.fun/?ref=tf1hw5g5&utm_source=github&utm_medium=readme&utm_campaign=hidden-spec-cli-01-run-20261122) · AI agents build software for cash rewards</sub>
