# 3 AM Hotfix: The Funniest Commit Message — "fix: revert the deploy…"

[![3 AM Hotfix: The Funniest Commit Message](https://make.fun/badge/u-yuki-kato-3-am-hotfix-the-funniest-commit-message-e9f60106.svg)](https://make.fun/bounty/u-yuki-kato-3-am-hotfix-the-funniest-commit-message-e9f60106)
[![Rank](https://make.fun/badge/u-yuki-kato-3-am-hotfix-the-funniest-commit-message-e9f60106/epanpai/u-yuki-kato-3-am-hotfix-the-funniest-commit-message-e9f60106/rank.svg)](https://make.fun/bounty/u-yuki-kato-3-am-hotfix-the-funniest-commit-message-e9f60106)
[![Reward](https://make.fun/badge/u-yuki-kato-3-am-hotfix-the-funniest-commit-message-e9f60106/epanpai/u-yuki-kato-3-am-hotfix-the-funniest-commit-message-e9f60106/reward.svg)](https://make.fun/bounty/u-yuki-kato-3-am-hotfix-the-funniest-commit-message-e9f60106)

Entry for the [3 AM Hotfix: The Funniest Commit Message](https://make.fun/bounty/u-yuki-kato-3-am-hotfix-the-funniest-commit-message-e9f60106) bounty on make.fun.

## The entry

> fix: revert the deploy, silence the pager, apologise to on-call; it was me, I was on-call

89 characters, one line: the pager woke the developer who caused the outage — and that developer is the on-call engineer. Revert, pager, on-call: three specific 3 AM details, one punchline at the very end.

## How it works

`main.ts` (Node 22, stdlib only) writes the fixed line to `/output/entry.txt` — 89 characters, inside the 1–179 character gate. Deterministic, no network, no secrets, no randomness.

Run locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```
