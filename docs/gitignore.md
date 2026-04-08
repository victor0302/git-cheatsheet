# Gitignore

## What is .gitignore?

A `.gitignore` file tells Git which files and directories to ignore.

This is useful for:
- Files you don’t want to track
- Sensitive data
- Generated files

---

## Common Examples

    node_modules
    .env
    __pycache__/
    *.pyc

- Prevents unnecessary or sensitive files from being committed

---

## How It Works

A `.gitignore` file is usually placed at the root of a repository.

It ignores matching files and directories across the project.

---

## Nested .gitignore

- You can have multiple `.gitignore` files
- A nested `.gitignore` only applies to its directory and subdirectories

---

## Patterns

### Wildcards

    *.txt

- Matches any file ending in `.txt`

---

### Rooted Patterns

    /main.py

- Matches only files in the root directory
- Does NOT match files in subdirectories

---

### Negation

    *.txt
    !important.txt

- Ignores all `.txt` files except `important.txt`

---

### Comments

    # ignore all txt files
    *.txt

- Lines starting with `#` are comments

---

### Order Matters

- Patterns are applied in order
- Later rules can override earlier ones

---

## What to Ignore

General guidelines:

- Generated files (compiled code, build files)
- Dependencies (node_modules, virtual environments)
- Personal files (editor settings)
- Sensitive data (.env, API keys, passwords)

---

## Notes

- `.gitignore` helps keep your repository clean
- Prevents accidental commits of unnecessary or sensitive files