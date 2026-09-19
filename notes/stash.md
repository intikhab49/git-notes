# Stash is a commit in disguise

Stashes are real commit objects on a hidden ref. `git stash list` and `git stash show -p` inspect them. A dropped stash can often be recovered through `git fsck --unreachable`.
