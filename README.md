# .github

This repository contains **shared GitHub configurations** for the entire organization.

## Purpose

By centralizing these files, we ensure consistency.

### Included

- ✅ **Pull Request Templates** – Standardize PR descriptions across projects

## Behavior

- These files automatically apply to all repositories in the organization, **unless overridden** by a local `.github/` folder in a repo.
- This promotes **standardization, better collaboration, and easier onboarding**.

## Resources

- [GitHub Docs: About the `.github` Repository](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)

- 🔧 **Commit message hook** – each repo ships `.githooks/prepare-commit-msg` (enable it with `git config core.hooksPath .githooks`)
