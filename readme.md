# membership_bot

This project is decommissioned and intentionally non-operational.

## status

- Runtime logic has been removed.
- The entrypoint exits immediately with a decommission message.
- No credential loading remains in repository code.

## security posture

- No active secret files are tracked in the repository.
- Legacy token and password values must still be treated as compromised if they were ever exposed.
- Historical leak risk is handled by credential rotation and decommissioning, not by current code state.

## repository intent

This repository is kept only as a clean archival record. It is not intended for deployment.
