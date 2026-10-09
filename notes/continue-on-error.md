# Letting a step fail without failing the job

`continue-on-error: true` on a step marks the job green even if it fails; check `steps.<id>.outcome` afterwards. On a matrix job it lets experimental entries fail.
