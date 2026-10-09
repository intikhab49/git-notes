# Least-privilege GITHUB_TOKEN

Set `permissions: contents: read` at the top of a workflow and grant extra scopes per job. Any scope not listed becomes `none` once the block is present.
