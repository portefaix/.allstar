# Portefaix / Allstar Security Policy Enforcement

This repository outlines the security policy enforcement for the Portefaix organization, using the Allstar GitHub App.
Allstar helps enforce security best practices by automatically checking and ensuring our repositories comply with
our established policies.

## Policy Configuration

These are the expected settings to be in compliance

### [Branch Protection](branch_protection.yaml)

|                       |              |
| --------------------- | ------------ |
| Branches enforced     | default      |
| Require approval      | yes          |
| Approvals required    | 1            |
| Dismiss stale reviews | not required |
| Block force push      | yes          |

### [Binary Artifacts](binary_artifacts.yaml)

- Binary artifacts not allowed.

### [Outside Collaborators](outside.yaml)

- Push access allowed.
- Admin access not allowed.

### [SECURITY.md](security.yaml)

- SECURITY.md required.
