# Comparing two versions of a branch

`git range-diff main@{u} old-tip new-tip` pairs up commits from before and after a rebase and diffs each pair. The quickest way to review what changed in a force-pushed PR.
