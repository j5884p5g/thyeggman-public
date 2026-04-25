# release/v1.2.x Branch

This is the stable release/v1.2.x branch.

## Workflow Differences from Main

This branch has its own workflow configuration that is intentionally
different from main. However, due to the pull_request_target behavior
change, PRs targeting this branch will run the workflow from main,
not the workflow defined here.
