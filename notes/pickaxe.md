# Searching history for a string

`git log -S 'text'` finds commits that changed how many times `text` appears; `-G 'regex'` matches any added or removed line. Add `-p` to see the hunks.
