# switch and restore instead of checkout

`git switch` changes branches and `git restore` discards file changes; together they cover the two unrelated jobs `git checkout` used to do. `git restore --staged file` unstages without touching the working tree.
