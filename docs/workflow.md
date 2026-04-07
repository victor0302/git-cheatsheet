# Workflow

## Basic Git Workflow

This is a simple workflow using the commands covered so far.

---

## 1. Start a Repository

    git init

Creates a new Git repository for your project.

---

## 2. Check Status

    git status

Shows the current state of the repository:
- Untracked files
- Staged files
- Committed changes

---

## 3. Stage Changes

    git add file.txt
    git add .

Stages files so they can be included in the next commit.

---

## 4. Commit Changes

    git commit -m "message"

Creates a snapshot of the staged changes.

---

## 5. Create a Branch

    git switch -c new-branch

Creates a new branch and switches to it.

---

## 6. Work on the Branch

Make changes, then check status, stage, and commit again:

    git status
    git add .
    git commit -m "message"

---

## 7. Switch Back to Main

    git switch main

Returns to the main branch.

---

## 8. Merge the Branch

    git merge new-branch

Brings the branch changes into `main`.

---

## 9. Connect to a Remote

    git remote add origin <url>

Adds the remote repository.

---

## 10. Fetch Remote Data

    git fetch

Downloads data from the remote repository.

---

## Notes

- Stage before you commit
- Branches help keep work separate
- Merge brings finished work back into `main`
- A remote lets you connect your local repo to another repository