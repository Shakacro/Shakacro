# Contributing to Shakacro

Thank you for helping improve this repository.

Guidelines
- Be respectful and constructive.
- Prefer small, focused changes.
- Keep discussions and commits free of secrets and sensitive data.

Getting Started
- Fork the repo and create a feature branch: git checkout -b feat/short-description
- Use Conventional Commits:
  - feat: add new feature
  - fix: correct a bug
  - docs: update documentation
  - chore: maintenance work
- Keep commit messages concise and descriptive.

Pull Request Process
- Open a PR to main with a clear title and description.
- Link related issues (e.g., closes #123).
- Include a brief checklist:
  - [ ] Tests or manual validation done
  - [ ] Documentation updated (if needed)
  - [ ] No secrets in commits, PR description, or logs
- Reviews: CODEOWNERS will auto-request @Shakacro for matching paths.
- CI: Ensure workflows pass before requesting merge.

Security & Privacy
- Do not commit credentials or private data.
- Use GitHub Actions Encrypted Secrets for any required tokens.
- If a secret leaks, immediately rotate it and remove from history (git filter-repo or BFG), then force-push.

License
- By contributing, you agree that your contributions are licensed under the MIT License of this repository.

Support
- For questions, open a discussion or a draft PR. For sensitive matters, use Security Advisories (see SECURITY.md).