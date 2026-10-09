# Manual runs with workflow_dispatch inputs

Define `on.workflow_dispatch.inputs` with `type: choice`, `boolean` or `string`; read them as `${{ inputs.name }}`. Runs can be triggered from the UI or `gh workflow run -f name=value`.
