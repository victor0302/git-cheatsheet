# Branching

## What is a Branch?

A branch is:
- A named pointer to a specific commit
- The commit it points to is called the tip of the branch
- Lightweight and cheap to create

---

## Default Branch

- Historically: master  
- Recommended: main  

---

## Create a Branch

    git branch new-branch

- Creates a new branch
- Does not switch to it

---

## Create and Switch

    git switch -c new-branch

- Creates a new branch
- Immediately switches to it

---

## Switch Branches

    git switch main

- Moves between branches

---

## Git Log Options

    git log --oneline --decorate
    git log --decorate=full

- `--oneline` → compact view of commits  
- `--decorate` → shows branch references  

---

## Branch Storage

Branches are stored in:

    .git/refs/heads

---

## Notes

- Branches help keep changes separate
- Switching branches changes your working directory
- `git switch` is preferred over `git checkout` for switching branches