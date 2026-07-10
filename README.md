# Personal GitHub Defaults

This repository is a central configuration hub for my personal GitHub account.
It is meant to provide a consistent baseline for new repositories without forcing
every repo to carry the same boilerplate.

## What This Repo Standardizes

- Shared community files such as [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md), [CONTRIBUTING.md](CONTRIBUTING.md), [SECURITY.md](SECURITY.md), and [CHANGELOG.md](CHANGELOG.md)
- Default issue templates under [`.github/ISSUE_TEMPLATE`](.github/ISSUE_TEMPLATE)
- A shared pull request template in [`.github/pull_request_template.md`](.github/pull_request_template.md)
- Shared account-level metadata in [`.github/FUNDING.yaml`](.github/FUNDING.yaml)
- Workflow templates and reusable automation in [`.github/workflows`](.github/workflows)
- Development defaults for editing and validation in [`.devcontainer`](.devcontainer), [`.pre-commit-config.yaml`](.pre-commit-config.yaml), [`.markdownlint.json`](.markdownlint.json), and [`.yamllint.yaml`](.yamllint.yaml)

## What Still Lives Per Repository

This repo does not replace GitHub settings that are still managed per repository or via GitHub admin controls:

- Branch protection and rulesets
- Repository visibility and topics
- Secrets, variables, and environments
- Merge strategy and required status checks
- Actions permissions and workflow security settings

## How To Use It

When I create a new repository, I use this repo as the source of shared defaults and only add repo-specific files when they are genuinely needed.
The goal is to keep the account-wide baseline small, safe, and easy to update.

## Structure

- `MARKDOWN_GUIDE.md` for repository-agnostic Markdown standards and templates
- `.github/ISSUE_TEMPLATE/` for issue intake
- `.github/workflows/` for reusable automation patterns
- `.github/FUNDING.yaml` for sponsor links
- `.devcontainer/` for editing this repository locally
- Root-level lint and hook config for shared formatting and validation rules
