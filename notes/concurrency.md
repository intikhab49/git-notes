# Cancelling superseded workflow runs

`concurrency: { group: ${{ github.workflow }}-${{ github.ref }}, cancel-in-progress: true }` cancels the older run when a new commit lands on the same branch.
