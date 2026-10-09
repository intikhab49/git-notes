# Blobless partial clones

`git clone --filter=blob:none` downloads all commits and trees but fetches file contents on demand. History commands stay fast; it is usually a better default than `--depth 1` for development clones.
