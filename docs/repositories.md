# Repositories

## What is a Repository?

A Git repository:
- Represents a single project
- Is a directory containing your files
- Includes a hidden `.git` directory

The `.git` folder stores all of Git’s internal tracking and versioning information.

---

## Initialize a Repository

    git init

---

## File States

A file in Git can be in one of the following states:

- Untracked → Not being tracked by Git
- Staged → Marked for inclusion in the next commit
- Committed → Saved to the repository history

---

## Check Status

    git status

This command shows:
- Which files are untracked
- Which files are staged
- Which files are committed

---

## Notes

- A repository is the starting point of any Git project
- The `.git` directory is automatically created when you run `git init`
- All version control data is stored inside `.git`