# Submodules pin a commit, not a branch

A submodule records an exact SHA. Updating the upstream branch changes nothing until you enter the submodule, pull, and commit the new pointer in the parent. Clone with `--recurse-submodules` or the directories arrive empty.
