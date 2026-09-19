# Reusable workflows versus composite actions

A reusable workflow is called with `uses:` at the job level and can define its own jobs and secrets. A composite action packages steps inside one job. Reach for the workflow when you need separate runners, the action when you need inline steps.
