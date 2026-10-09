# Recovering commits with the reflog

`git reflog` records every position HEAD has been at, including after a bad reset or rebase. Find the entry and `git reset --hard HEAD@{n}`. Entries expire after 90 days by default (30 for unreachable ones).
