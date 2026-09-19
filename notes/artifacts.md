# Artifacts versus caches

Artifacts are outputs you intend to download or hand to a later job; caches are a speed optimisation that must be safe to lose. Never store a build output only in a cache — eviction is silent.
