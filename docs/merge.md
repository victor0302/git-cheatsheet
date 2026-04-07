# Merge

## Merge a Branch

    git switch main
    git merge feature-branch

- Merges changes from another branch into the current branch

---

## Merge Process

When merging, Git will:

1. Find the "merge base" (best common ancestor)
2. Replay changes from the main branch
3. Replay changes from the feature branch
4. Create a new commit with the combined changes
5. The merge commit has two parent commits

---

## Log Visualization

    git log --oneline --decorate --graph --parents

- Shows commit history as a graph
- Displays branch structure and merge commits

---

## Fast-Forward Merge

- Occurs when the current branch is behind another branch
- Git simply moves the branch pointer forward
- No merge commit is created

---

## Notes

- Merge combines changes from different branches
- Merge commits preserve branch history