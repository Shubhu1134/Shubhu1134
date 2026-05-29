# Contributing Playbook

This repository is your profile repo, but you should use the same workflow quality as product repositories.

## Scope

Use this repo for profile polish, weekly execution planning, issue templates, PR templates, and automation that supports public shipping.

## Fast Contribution Loop (20 minutes)
1. Open or create an issue first.
2. Create a branch: `git checkout -b docs/<short-name>`, `fix/<short-name>`, `feat/<short-name>`, `chore/<short-name>`, or `ci/<short-name>`.
3. Make a focused change and commit with a clear message.
4. Run the relevant local validation.
5. Push: `git push origin <branch-name>`.
6. Open a pull request and merge after checks/review.
7. Close the linked issue.

## PR Quality Checklist
- Change is linked to an issue
- Scope is small and clear
- README/docs updated if behavior changed
- No secrets or credentials in files
- Commit messages are meaningful
- Local Markdown links still resolve
- Weekly sprint docs stay current when dates or targets change

## Commit Message Examples
- `docs: refresh profile execution links`
- `fix: correct weekly sprint cron schedule`
- `ci: add repo health workflow`
- `chore: ignore local agent artifacts`

## Achievement-Oriented Workflow
- Prefer PR-based merges over direct pushes
- Use public repositories for visible activity
- Add co-authored commits when collaborating
- Participate in discussions and mark accepted answers where possible
- Log merged PRs, closed issues, reviews, and external contributions in the weekly sprint issue
