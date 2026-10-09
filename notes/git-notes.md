# Attaching notes to commits

`git notes add -m 'msg' <sha>` stores text under `refs/notes/commits` without changing the commit hash. Notes are not pushed by default; push `refs/notes/*` explicitly.
