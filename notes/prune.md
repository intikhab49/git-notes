# Pruning stale remote branches

`git fetch --prune` deletes local refs whose remote counterpart is gone. Set `fetch.prune=true` globally, otherwise deleted branches accumulate in `git branch -r` indefinitely.
