# Shallow fetch in CI

`fetch-depth: 1` is the Actions default and speeds up checkout, but breaks anything reading history — changelog generation, `git describe`, and blame-based tooling. Set `fetch-depth: 0` for those jobs only.
