# always(), failure() and cancelled()

Steps skip after a failure unless their `if:` uses a status function. `if: failure()` runs only on failure; `if: always()` also runs on cancel, so prefer `!cancelled()` for cleanup.
