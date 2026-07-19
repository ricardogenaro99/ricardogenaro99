# Security Policy

## Supported Versions

This is a GitHub profile README repository. It contains:
- Profile `README.md`
- GitHub Actions workflows for automating devcard updates

| Component | Status |
|-----------|--------|
| GitHub Actions workflows | ✅ Actively maintained |

## Reporting a Vulnerability

If you discover a security vulnerability (e.g., a workflow that could be exploited via injection), please report it responsibly:

1. **Do NOT open a public GitHub Issue** for security vulnerabilities.
2. Contact me directly via email: [genaro.choquehuanca.palli@gmail.com](mailto:genaro.choquehuanca.palli@gmail.com)
3. Include a description of the vulnerability and steps to reproduce.

I will acknowledge your report within **48 hours** and work on a fix promptly.

## Security Best Practices Applied

- ✅ GitHub Actions use pinned versions (`actions/checkout@v4`)
- ✅ Workflows use `[skip ci]` to avoid recursive triggers
- ✅ Minimal permissions: only `contents: write` where needed
- ✅ No secrets stored beyond GitHub's built-in `GITHUB_TOKEN`
- ✅ Dependabot enabled to keep Actions up to date
