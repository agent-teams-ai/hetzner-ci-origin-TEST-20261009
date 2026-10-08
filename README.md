# Isolated native origin TEST

Synthetic public TEST repository owned by agent-teams-ai. This source has no
product code, secrets, credentials, checkout, dependencies or agent/runtime
commands. The only workflow is manually dispatched and prints a constant marker.
Its exact TEST label is hci-origin-TEST-20261009 and its job timeout is two minutes.

The planned runner-group policy selects this repository only and permits only
`.github/workflows/origin-TEST.yml@refs/heads/main`. Publishing this source or
reading back that policy does not prove origin enforcement or authorize a runner
registration. Positive and negative native origin qualification is a separate
explicit TEST step. Product routes and the existing Default group are untouched.
