# Safer force pushes

`git push --force-with-lease` refuses to overwrite the remote if it moved since your last fetch. Pair it with `--force-if-includes` so a background fetch cannot silently defeat the check.
