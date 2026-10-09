# Per-directory git identity

In `~/.gitconfig`, `[includeIf "gitdir:~/work/"]` with `path = ~/.gitconfig-work` loads a separate user.email for every repo under that directory.
