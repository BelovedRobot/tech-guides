# Gitflow

This guide intends to set a pattern across all the Beloved Robot projects when handling git projects.

## General
- Check that your pushed changes have been updated with the main branch.
- Check your spelling and grammar. 

## Commit messages
Commit messages must be concise and they should describe only one change.
Commit messges consists of three parts:
- Shortlog
- Commit body
- Issue reference

Example:
```shell
Add pictures deleted model type 

Added the new deleted pictures model and created new table view cell for the new picture type.

Closes [link to Trello card or DaPulse card]
```

## Branches
- Always start working on a new task creating a branch from the main branch (master or development depending on the project)
- Use a correct branch-naming:
  - For features use: ```feature/add-new-database-support```
  - For fixes use: ```fix/crash-on-creating-new-tasks```
  - For enhancements: ```enhancements/improve-tasks-fetch-codestyle```

## Pull requests / Merge requests
- Make an individual pull request / report for each suggestion / bug or enhancement.
- You can create a pull request with various commits but when the PR is ready to merge squash all commits into one.
- Use rebase instead of merge when resolving conflicts (we use rebase to have a linear git history)
- Insead of pushing WIP commits or PRs use the labels on GitHub (Ready for review, In Progress, Ready for merge).

