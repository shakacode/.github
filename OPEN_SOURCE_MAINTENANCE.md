# ShakaCode open-source maintenance baseline

This is the public baseline for actively maintained ShakaCode repositories.
Repository-specific requirements may be stricter.

## Repository setup

- Use `main` for new repositories. Rename an existing default branch only
  through an explicit migration that checks CI, releases, deployments, badges,
  documentation, and downstream consumers.
- Delete head branches after merge.
- Prefer squash merge; disable merge commits unless release history requires them.
- Protect the default branch against force pushes and deletion.
- Require pull requests for maintained projects. Flagship projects normally
  require at least one approval and resolved review conversations.
- Give workflows the smallest permissions they need and pin sensitive
  third-party actions to reviewed versions or commit SHAs.
- Enable private vulnerability reporting, dependency alerts, and automated
  dependency updates when supported.
- Keep topics, description, website, license, ownership, and archive status current.

## Maintained repository contents

Normally provide a README, license, contribution guide, code of conduct,
security policy, support guidance, issue/PR templates, CI, and an `AGENTS.md`
with real setup and validation commands.

## Lifecycle review

Inactivity is a signal, not an automatic archive decision:

- review classification after about six months without a push;
- mark for maintainer attention after one year;
- consider archival after two years;
- give repositories over five years without activity especially strong review.

Before archiving, check package downloads, dependents, releases, deployments,
support/security commitments, whether the project is intentionally stable, and
whether a replacement exists. Update the README and links before archiving.
Never delete or archive solely because a timer elapsed.

## Outside contributions

Treat fork pull requests as untrusted input. Review metadata and the complete
diff before running contributor-controlled code with credentials. Do not expose
secrets to fork workflows. A contribution should earn its long-term maintenance
cost through clear user value, meaningful coverage, or reduced risk.
