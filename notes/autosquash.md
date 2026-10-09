# Fixup commits and autosquash

`git commit --fixup=<sha>` creates a `fixup!` commit; `git rebase -i --autosquash <base>` moves and folds it into its target. Set `rebase.autoSquash=true` to make it the default.
