# Archived upstream workflows

These workflows came from the upstream Bitnami charts repository and are kept
only as migration reference. They are intentionally outside
`.github/workflows`, so GitHub does not execute them in this fork.

Several workflows were tied to the `bitnami` organization, contained invalid
fork-specific triggers, or used privileged `pull_request_target` automation.
The active, least-privilege pipeline for this repository is
`.github/workflows/universal-ci.yml`.

Do not move an archived workflow back into `.github/workflows` without updating
it for this repository, pinning every action by commit SHA, and passing both
`actionlint` and `zizmor` at medium confidence and severity.
