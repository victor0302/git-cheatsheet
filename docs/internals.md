# Internals

## Commit Hashes

Commit hashes are unique identifiers for each commit.

They are based on:
- Content changes
- Commit message
- Author name and email
- Date and time
- Parent (previous) commit

Git uses a cryptographic hash function called SHA-1.

---

## .git Directory

All Git data is stored inside the hidden `.git` directory.

This includes:
- Commits
- Branches
- Tags
- Objects

    ls -l .git/objects

---

## Git Objects

Git stores data as objects:

- Commit → snapshot of the repository
- Tree → represents a directory
- Blob → represents a file

---

## Inspect Objects

You can inspect Git objects using:

    git cat-file -p <hash>

This lets you view the contents of a commit or object.

---

## Storage

Git:
- Stores a full snapshot of files for each commit
- Compresses and packs data for efficiency
- Deduplicates identical files across commits

---

## Notes

- All version history lives inside the `.git` folder
- Git objects are the core building blocks of Git