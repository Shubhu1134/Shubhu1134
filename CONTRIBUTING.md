# Contributing

This repository maintains the GitHub profile for [Shubhu1134](https://github.com/Shubhu1134).

## Scope

Useful changes include correcting profile information, improving readability and accessibility, fixing links, and maintaining repository checks. Keep the profile focused on work that visitors can inspect.

- Link to public repositories and describe their current contents accurately.
- Distinguish learning roadmaps from implemented projects.
- Keep private project details and credentials out of public content.
- Prefer readable text over decorative widgets or activity counters.

## Making a change

1. Create a focused branch, such as `profile/update-projects` or `docs/fix-links`.
2. Make the change and check the Markdown preview and affected links.
3. Run `git diff --check` and review the complete diff.
4. Open a pull request explaining the change and its validation.
5. Confirm the repository health check passes before merging.

An issue is useful for larger changes; small corrections do not need a separate issue.

## Maintainer commit identity

For work committed on behalf of the owner, configure this checkout with the owner's GitHub identity:

```bash
git config --local user.name shubhu1134
git config --local user.email 99715758+Shubhu1134@users.noreply.github.com
```

Before publishing, inspect the author and committer:

```bash
git log -1 --format=fuller
```

Other contributors should use their own identities. Credit actual collaborators accurately; do not add automatic tool co-author trailers. Existing contributor history should be preserved.

## Repository planning

The existing [execution board](./ACHIEVEMENT_EXECUTION_BOARD.md), [sprint playbook](./ACHIEVEMENT_SPRINT.md), and [repository plan](./REPO_ACCELERATION_PLAN.md) are planning references. They are not evidence of completed project features.

Report sensitive issues through the contact in [SECURITY.md](./SECURITY.md).
