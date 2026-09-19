# Cache keys need a lockfile hash

Key the cache on a hash of the lockfile, with a looser `restore-keys` prefix as fallback. Keying on the branch name alone produces stale caches that are worse than no cache.
