# Setting env vars for later steps

`echo "NAME=value" >> "$GITHUB_ENV"` makes `NAME` available to every following step in the job, but not to the step that wrote it.
