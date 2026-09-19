# Client-side hooks are not shared

Hooks in .git/hooks never travel with a clone. Point `core.hooksPath` at a tracked directory to version them, but remember hooks are trivially bypassed with `--no-verify`, so never rely on them as a security control.
