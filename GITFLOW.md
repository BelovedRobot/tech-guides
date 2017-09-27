# Gitflow

This guide outlines the source control strategy for all of Beloved Robot projects.

## General Tasks
- Please check your capitlization, spelling, and grammar to ensure they are correct.
- Always follow-up with your Development Lead to ensure your pull requests are merged with Main

## Commit Messages
- Commit messages must be concise and they should describe only one change
- Commit messges consists of three parts
  1. Short description or title
  2. Commit body which provides detail
  3. Issue reference, which provides some web link to the issue/task you are working on

Example:
```shell
Add pictures deleted model type 

Added the new deleted pictures model and created new table view cell for the new picture type.

Closes [link to Trello card or DaPulse card]
```

## Branches
- Always start working on a new task by creating a branch from the main branch (master or development depending on the project)
- Use the correct branch-naming conventions:
  1. For fixes use: ```fix/crash-on-creating-new-tasks```
  2. For features or other enhancements: ```enhancement/improve-tasks-fetch-codestyle```

## Pull requests / Merge requests
- Make an individual pull request for each task when you are complete
- You can create a pull request with various commits but when the pull request is ready to merge squash all commits into a single pull request for consistency
- Use rebase instead of merge when resolving conflicts (we use rebase to have a linear git history)
- Insead of pushing WIP (work in progress) commits or pull requsts use these labels
  1. In Progress
  2. Ready for Review
  3. Ready for Merge
