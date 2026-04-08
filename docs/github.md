# GitHub

## What is GitHub?

GitHub is a platform for hosting Git repositories online.

It is used for:
- Backing up your code in the cloud
- Sharing code with others
- Collaborating on projects
- Building a public portfolio

---

## Push

    git push origin main

- Sends local commits to the remote repository
- Pushes your current branch to the remote branch

### Push to Different Branch Name

    git push origin <local-branch>:<remote-branch>

- Pushes a local branch to a differently named remote branch

### Delete Remote Branch

    git push origin :<remote-branch>

- Deletes a branch on the remote

---

## Pull

    git pull origin main

- Fetches and merges changes from the remote repository
- Updates your local branch with remote changes

### Notes on Pull

- If no branch is specified, Git pulls the current branch
- Combines `git fetch` + `git merge`

---

## Pull Requests

A pull request is used to propose changes.

It allows:
- Team members to review code
- Discussion before merging
- Approval before changes go into main

---

## Merge Pull Request

- After approval, a pull request can be merged
- This combines the changes into the main branch
- Typically done through GitHub’s interface

---

## Notes

- GitHub acts as a central place for collaboration
- Push sends your changes to GitHub
- Pull brings changes from GitHub to your local repo
- Pull requests are used for team-based workflows