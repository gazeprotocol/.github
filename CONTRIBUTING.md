<!-- gz-context: docs -->
# Contributing to Gaze

Thank you for helping build Gaze, a watch protocol on Solana.
This guide applies to every repository in the organization unless a repo has its own.

## Before you start

- Search existing issues and discussions first.
- For anything larger than a small fix, open an issue and agree on the approach before writing code.
- Be kind and specific. Our [Code of Conduct](CODE_OF_CONDUCT.md) applies everywhere.

## Making a change

1. Fork the repository and branch from `main`. Name branches `type/short-description`, for example `fix/extension-timer`.
2. Keep each pull request to one change. Small pull requests get reviewed faster.
3. Write commit messages in [Conventional Commits](https://www.conventionalcommits.org) form: `feat:`, `fix:`, `docs:`, `chore:`.
4. Sign off every commit to certify the [Developer Certificate of Origin](https://developercertificate.org): `git commit -s`.
5. Add or update tests, and run the repo's lint and test commands before you push.
6. Open the pull request and fill in the template.

## Writing about Gaze

Docs, READMEs, UI text and release notes follow the Gaze style guide:

- Say **protocol**, **watcher**, **creator**, **creator token**, **period** and **rewards**.
- Write plainly and calmly. No hype, no urgency, no exclamation marks.
- Describe only what is built, using the approved claims in the style guide.

Pull requests that change public copy must pass the copy linter.

## Security issues

Never report a vulnerability in a public issue. Follow [SECURITY.md](SECURITY.md).

## Licensing

Each repository states its license in its own `LICENSE` file.
By contributing, you agree your contribution is licensed under that repository's license.
