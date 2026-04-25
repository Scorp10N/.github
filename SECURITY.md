# Security Policy

## Supported Versions

| Project | Supported |
|---------|-----------|
| resumeforge (latest) | ✅ |
| resumeforge-cloud (latest) | ✅ |

## Reporting a Vulnerability

**Do not open a public issue for security vulnerabilities.**

Email: scorpyarin@gmail.com

Please include:
- Description of the vulnerability
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

You will receive a response within 48 hours. If the issue is confirmed, a patch will be released as soon as possible and you will be credited in the release notes.

## Security Scanning

All Scorp10N repositories run automated security scans on every push and pull request:
- Secret scanning (TruffleHog)
- Dependency vulnerability scanning (pip-audit, govulncheck, npm audit)
- Container scanning (Trivy)
- Static analysis (CodeQL, Semgrep)

Security tooling is centralized in [`Scorp10N/devsecops`](https://github.com/Scorp10N/devsecops).
