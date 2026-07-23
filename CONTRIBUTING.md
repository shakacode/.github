# Contributing to ShakaCode open source

Thank you for helping improve a ShakaCode project. Repository-specific
instructions take precedence over this organization default.

## Before starting

- Search existing issues and pull requests.
- For a substantial feature, public API change, dependency migration, or broad
  refactor, open an issue or discussion before investing significant work.
- Keep security reports private; follow the repository's security policy.
- Confirm the repository is actively maintained. An old repository may be kept
  for historical or compatibility reasons.

## A useful contribution

A pull request should have one clear purpose, explain the user or maintainer
value, and avoid unrelated cleanup. Include:

- the problem and why it is worth solving;
- the approach and important tradeoffs;
- tests or a concrete explanation when tests do not apply;
- documentation and changelog updates when behavior changes;
- exact validation commands and results;
- screenshots or recordings for visible UI changes.

Generated, formatting-only, speculative, or low-signal changes may be closed
when their maintenance cost exceeds their value. Adding tests is welcome when
the tests cover meaningful behavior, failure cases, or a regression—not merely
implementation details already exercised elsewhere.

If AI tools materially assisted the change, review every line yourself and say
so in the pull request. The contributor remains responsible for correctness,
licensing, security, and responding to review.

## Development workflow

1. Fork the repository and create a focused branch.
2. Follow its `README`, `CONTRIBUTING.md`, and `AGENTS.md`.
3. Add or update tests before changing behavior when practical.
4. Run the repository's documented formatter, linter, tests, and validation.
5. Open a pull request using the template and keep the branch current.

Do not include secrets, private data, proprietary code, or dependencies whose
license is incompatible with the repository.

## Review and acceptance

Maintainers may ask for a narrower change, additional evidence, or a different
design. Approval does not guarantee immediate merge or release. Maintainers may
close a pull request that is out of scope, inactive, unsafe, duplicative, or too
costly to maintain; this is about project fit, not the contributor's worth.
