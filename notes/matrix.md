# Matrix builds and fail-fast

A matrix expands one job across combinations. `fail-fast: true` is the default and cancels every sibling on first failure, which hides whether the break is platform-specific. Set it false when you need the full picture.
