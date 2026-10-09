# Finding where branches diverged

`git merge-base main feature` prints the common ancestor. `git diff main...feature` (three dots) diffs from that point, which is what a PR shows.
