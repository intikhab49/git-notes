# Version strings from git describe

`git describe --tags --always --dirty` prints e.g. `v1.4.0-12-gabc1234-dirty`: nearest tag, commits since, short SHA, and whether the tree is modified. Handy for build version stamps.
