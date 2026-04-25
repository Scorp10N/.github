# Contributing

## Workflow

1. Fork the repository
2. Create a feature branch: `git checkout -b feat/your-feature`
3. Make your changes and add tests
4. Run the test suite locally before pushing
5. Open a pull request — all CI and security checks must pass before merge

## Security

All PRs are automatically scanned for secrets, dependency vulnerabilities, and code issues.
See [SECURITY.md](SECURITY.md) for the vulnerability disclosure policy.

## Code Style

Each repository has a `CLAUDE.md` with language-specific style rules.
The shared pre-commit config (managed in `Scorp10N/devsecops`) enforces baseline formatting.
