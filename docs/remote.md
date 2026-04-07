# Remote

## What is a Remote?

A remote is:
- An external Git repository
- Usually hosted on a platform like GitHub
- Typically named "origin"

The remote is often treated as the "source of truth".

---

## Add Remote

    git remote add origin <url>

- Adds a connection to a remote repository

---

## Fetch

    git fetch

- Downloads data from the remote repository
- Retrieves commits, branches, and objects
- Does not automatically merge changes

---

## Notes

- Adding a remote does not download its contents
- You must use `git fetch` to get remote data
- Remote repositories allow collaboration and sharing code