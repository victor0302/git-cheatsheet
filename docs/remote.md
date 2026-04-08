# Remote

## What is a Remote?

A remote is:
- An external Git repository
- Has mostly the same Git history as your local repo
- Usually hosted on a platform like GitHub
- Typically named "origin"

The remote is often treated as the "source of truth".

---

## Add Remote

    git remote add origin <url>

- Adds a connection to a remote repository
- `origin` is the standard name for the main remote

---

## Fetch

    git fetch

- Downloads data from the remote repository
- Retrieves commits, branches, and objects
- Does NOT merge changes into your current branch

---

## Notes on Fetch

- Adding a remote does not download its contents
- Fetch only gets metadata and objects
- You may not have all working files after fetching

---

## View Remote History

    git log origin/main

- Shows commit history from the remote branch
- Useful for inspecting changes before merging

---

## Merge Remote Branch

    git merge origin/main

- Merges changes from the remote branch into your current branch

---

## Notes

- Remote repositories enable collaboration and sharing code
- Fetch allows you to see changes before applying them
- Merge is required to bring fetched changes into your local branch