# Reset

## Undo Changes

Git allows you to undo commits and changes in your repository.

---

## Soft Reset

    git reset --soft HEAD~1

- Moves the current branch back one commit
- Keeps changes staged
- Useful if you want to redo a commit

---

## Hard Reset

    git reset --hard HEAD~1

- Moves the current branch back one commit
- Deletes all changes
- Resets both staging area and working directory

---

## Notes

- `HEAD~1` means the previous commit
- Use `--soft` to keep changes
- Use `--hard` to discard changes permanently