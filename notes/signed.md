# Verifying signatures in CI

`git verify-commit` and `git log --show-signature` check signatures, but CI must import the trusted keys first or every commit reports as unverified. Vigilant mode marks unsigned commits in the web UI.
