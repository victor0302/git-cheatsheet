# Tracking Changes

## Staging Files

Files must be staged before they can be committed.

    git add file.txt
    git add .

- `git add file.txt` → stages a specific file  
- `git add .` → stages all changes in the current directory  

Only staged files are included in a commit.

---

## Commit

A commit is a snapshot of the repository at a specific point in time.

    git commit -m "message"

- The message describes the changes made
- Git saves the current state of all staged files

---

## Git Log

Shows the history of commits in the repository.

    git log
    git log --oneline

- Displays who made the commit
- Shows when the commit was made
- Includes the commit message

---

## Commit Hash

- Each commit has a unique identifier called a hash
- It is a long string of characters
- You can reference a commit using the first 7 characters of the hash

---

## Notes

- You must stage changes before committing
- Each commit represents a full snapshot of the repository
- Git uses commits to track all changes over time