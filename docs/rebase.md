# Rebase

## What is Rebase?

Rebase moves commits from one branch to another.

It places your branch commits on top of another branch.

---

## Run Rebase

    git switch feature-branch
    git rebase main

- Rebases the current branch onto `main`

---

## What Happens

1. Git finds the latest commit from `main`
2. Uses it as the new base
3. Replays each commit from the current branch
4. Updates the branch to point to the new commits

---

## Notes

- Rebase does not affect the `main` branch
- Creates a clean, linear commit history
- Do not rebase public branches (like `main`)