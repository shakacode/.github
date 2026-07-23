# Agent workflow template

Copy and adapt this into a repository's `AGENTS.md`. Replace every placeholder;
repository-specific instructions are more useful than generic prose.

## Repository seam

- Default branch: `<main-or-master>`
- Setup: `<deterministic-command>`
- Validate: `<single-closeout-command>`
- Tests: `<focused-and-full-commands>`
- Lint/format: `<commands>`
- Build/package: `<commands-or-not-applicable>`

## Safety boundaries

- Credentials and external systems: `<where-they-come-from-and-allowed-use>`
- Production/customer data: `<prohibited-or-approved-read-only-path>`
- Destructive actions: `<approval-and-recovery-requirements>`
- Generated files: `<source-and-regeneration-command>`

## Coordination

- Shared service/environment: `<name-or-none>`
- Worker identity and collision domain: `<protocol-or-none>`
- Hosted example/deployment: `<owner-healthcheck-logs-rollback-teardown>`

## Completion gate

1. Run `<validate>`.
2. Exercise changed behavior with `<manual-or-integration-proof>`.
3. Obtain independent review for non-trivial changes.
4. Commit to a feature branch and open a pull request.

If Claude Code is used, add a `CLAUDE.md` containing `@AGENTS.md`.
