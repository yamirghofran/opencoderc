---
description: create a pull request using the github cli
agent: build
model: opencode/kimi-k2
---

Explore the changes that are made/provided and use the github cli to create a draft pull request with a conventional and proper title and description.
Take the following information given by the user into account: $ARGUMENTS.

For example:

- If a PR is already included/provided, edit that instead of creating a new one yourself.
- Include an issue number they say this PR addresses/closes/fixes.
- If provided with git commits, use the git cli (e.g. git log) to view the changes and information to inform what you write in the pull request title and description.

Write the PR title and description in best practice.
