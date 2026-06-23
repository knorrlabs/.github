# Contributing

Thanks for your interest in contributing. These guidelines apply across all knorrlabs repositories unless a repo overrides them with its own `CONTRIBUTING.md`.

## Getting started

1. **Open an issue first** for anything beyond a trivial fix, so we can agree on the approach before you invest time.
2. **Fork and branch** from the latest `main`. Use a descriptive branch name (`fix/...`, `feat/...`, `docs/...`).
3. **Keep changes focused.** One logical concern per pull request. Unrelated cleanup belongs in its own PR.

## Commit messages

We follow [Conventional Commits](https://www.conventionalcommits.org/):

```
feat: add retry logic to the reconcile loop
fix: handle empty config without panicking
docs: clarify install prerequisites
```

- Use the imperative mood, lowercase after the colon, no trailing period.
- Keep the subject line under ~72 characters.
- Explain the *why* in the body when it isn't obvious from the diff.

## Pull requests

- Fill out the PR template completely.
- Make sure CI passes and any relevant linters/formatters are clean before requesting review.
- Add or update tests when you change behavior.
- Update docs when you change user-facing behavior.

## Code of conduct

By participating you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).
