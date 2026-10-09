# Multiple checkouts with worktree

`git worktree add ../hotfix main` gives a second working directory sharing the same object store. Cheaper than a second clone; a branch can only be checked out in one worktree at a time.
