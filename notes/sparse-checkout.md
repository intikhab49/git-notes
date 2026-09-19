# Sparse checkout for large monorepos

`git sparse-checkout set apps/web` limits the working tree to selected paths while keeping full history. Combined with a partial clone via `--filter=blob:none` it makes very large repos workable.
