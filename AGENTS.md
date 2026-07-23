# ShakaCode organization defaults

This public repository supplies organization profile and community-health
defaults. Do not include private repository names, credentials, customer
information, or internal operational details.

## Workflow

- Base branch: `main`
- Setup: `.agents/bin/setup` (requires Ruby and Go; installs pinned
  `actionlint` under `.agents/.tools/`)
- Validation: `.agents/bin/validate`
- Changes require a feature branch and pull request.
- Organization defaults must remain broadly applicable. Put project-specific
  commands and policy in that project's repository.

Review all workflow permission changes and external action references explicitly.
