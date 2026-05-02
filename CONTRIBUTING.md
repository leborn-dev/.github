# Contributing to Leborn projects

Thank you for considering contributing!

This is the **org-level default** for all Leborn projects. Individual projects may have their own `CONTRIBUTING.md` that overrides or extends this.

## Before you start

1. **Read the project's `LEBORN.md`** to understand:
   - The current phase (A through E)
   - The original upstream project being honored
   - The roadmap toward v0.1.0
2. **Read the project's `README` and `docs/`** for setup instructions.
3. **Open an Issue first** before any significant work, so we can align on direction. Trivial fixes (typos, formatting) can go straight to PR.

## Reporting issues

- Use GitHub Issues with the right template (Bug, Feature request, Migration question).
- Include reproduction steps, expected vs actual behavior, and environment details.
- For security issues, see `SECURITY.md` — please do **not** open a public issue for vulnerabilities.

## Pull requests

- Fork the repository and create a feature branch.
- Keep PRs **small and focused** — one concern per PR.
- Reference the related Issue in the PR description.
- Include tests when reasonable. Phase D may have stricter requirements.
- Follow the project's coding style. CI will check on push.
- Be patient with reviews — maintainers review when capacity allows.

## On AI-assisted contributions

We use AI heavily ourselves (Claude Code, Cursor, Copilot). You are welcome to use AI too.

But:
- Verify everything AI generates locally, run tests, and read the code yourself
- Be ready to explain any part of your PR if a reviewer asks
- "AI told me to" is not a justification — be ready to defend the design
- Do not paste AI output without comprehension — it leads to subtle bugs and hallucinated APIs

## Phases and where to contribute

| Phase | What's open for contribution |
|-------|------------------------------|
| **A** Setup & Analysis | Documentation improvements, missing platform setup steps |
| **B** Runtime compatibility | Bug fixes for runtime-specific failures |
| **C** Dependency upgrades | Help upgrading specific dependencies, compatibility shims |
| **D** Tests & CI | Test additions, CI matrix expansion |
| **E** AI-native rebirth | The biggest creative space — propose features via Feature Request issues |

## Licensing

By submitting code, you agree that your contributions will be licensed under the same license as the project (see `LICENSE` and `NOTICE`).

## Code of Conduct

By contributing, you agree to abide by the [Code of Conduct](./CODE_OF_CONDUCT.md).

## About Leborn

Leborn is an initiative to revive popular but stalled OSS projects with AI-native enhancements. It is sponsored and operated by [LLL Sdn Bhd](https://lll.dev). See [the org profile](https://github.com/leborn-dev) for context.
