# Contributing to CronusCycle

First off, thank you for considering contributing to CronusCycle. It‘s people like you that make CronusCycle such a great project.

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## Important: Contributor License Agreement (CLA)

**All contributions to this project must be submitted under a valid Contributor License Agreement (CLA).**

### Why we need a CLA

CronusCycle follows an **Open Core** model:
- The core framework is open-sourced under **MIT License**
- Advanced features are provided in **CronusCycle Enterprise** (commercial, closed-source)

To protect the project’s long-term sustainability and allow us to use community contributions in both open-source and commercial versions, **every contributor must sign a CLA before their pull request can be merged**.

### How to sign the CLA

1. When you submit your first pull request, our CLA bot will automatically comment with a link.
2. Click the link, review the agreement, and sign electronically (one-time only, valid for all future contributions).
3. Once signed, your PR will be eligible for review.

If you prefer to sign manually, you can download the CLA from [CLA.md](CLA.md) and send the signed copy to [bruce@zerora.cn](mailto:bruce@zerora.cn).

## How Can I Contribute?

### Reporting Bugs

- Ensure the bug was not already reported by searching on GitHub under [Issues](https://github.com/zerora-labs/cronus-cycle/issues).
- If you‘re unable to find an open issue addressing the problem, [open a new one](https://github.com/zerora-labs/cronus-cycle/issues/new). Be sure to include a **title and clear description**, as much relevant information as possible, and a **code sample** or an **executable test case** demonstrating the expected behavior that is not occurring.

### Suggesting Enhancements

- Open a new issue describing your suggestion.
- Provide a clear and detailed explanation of the feature you want and why it would be valuable to other users.

### Your First Code Contribution

Unsure where to begin? You can start by looking through these `good-first-issue` and `help-wanted` issues.

### Pull Requests

1. **Fork** the repo and create your branch from `main`.
2. **Sign your commits** – all commits must be cryptographically signed (`git commit -S`) .
3. **Add tests** – if you’re adding code, add tests. If you’re fixing a bug, add a test that would have caught it.
4. **Update documentation** – ensure any new or changed functionality is properly documented.
5. **Ensure the test suite passes** – run `npm test` locally.
6. **Keep PRs focused** – one feature/fix per pull request. Small PRs are easier to review and merge.
7. **Reference any relevant issues** – use “Fixes #123” in your PR description to auto-close issues.

## Styleguides

### Git Commit Messages

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

- **Format**: `<type>(<scope>): <description>`
- **Types**: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`
- **Example**: `feat(galaxy-engine): add black hole risk visualization`

All commits must include a **Signed-off-by** line (automatically added with `git commit -s`), which certifies that you have the right to submit this work under the project's license.

### Code Style

- We use **Prettier** for code formatting.
- Run `npm run lint` before committing to check your code style.

## Additional Notes

### Issue and Pull Request Labels

- `bug` – confirmed bugs
- `enhancement` – feature requests
- `good first issue` – good for newcomers
- `help wanted` – extra attention needed
- `cla-required` – PRs awaiting CLA signature

## Getting Help

- GitHub Issues: [https://github.com/zerora-labs/cronus-cycle/issues](https://github.com/zerora-labs/cronus-cycle/issues)
- Email: [bruce@zerora.cn](mailto:bruce@zerora.cn)

Thank you for contributing to CronusCycle!