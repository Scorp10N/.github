# .github — Scorp10N Org-Level Community Health Files

This is the org-level `.github` repository for the [Scorp10N](https://github.com/Scorp10N) GitHub organization. Files placed here serve as org-wide defaults and are automatically inherited by every repository in the org that does not provide its own equivalent.

## Contents

### Community Health Files

| File | Purpose |
|------|---------|
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Describes the standard contribution workflow (branching, pull requests, CI requirements) for all Scorp10N repositories. |
| [`SECURITY.md`](SECURITY.md) | Documents the vulnerability disclosure policy, supported project versions, and the automated security scanning (TruffleHog, CodeQL, Trivy, etc.) applied to every push and PR. |
| [`SUPPORT.md`](SUPPORT.md) | Directs users to the correct channel for bugs, feature requests, security issues, and general questions. |

### Organization Profile

| Path | Purpose |
|------|---------|
| [`profile/README.md`](profile/README.md) | Rendered as the public-facing Scorp10N organization profile on GitHub, giving visitors a brief overview of the org and its projects. |

## Notes

- Repository-specific `CLAUDE.md` files take precedence over org-wide defaults for language and style rules.
- Security tooling and pre-commit configuration are centralized in [`Scorp10N/devsecops`](https://github.com/Scorp10N/devsecops).
