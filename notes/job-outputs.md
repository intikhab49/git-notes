# Passing values between jobs

A step writes `echo "key=value" >> "$GITHUB_OUTPUT"`, the job maps it under `outputs:`, and a dependent job reads `${{ needs.<job>.outputs.key }}`.
