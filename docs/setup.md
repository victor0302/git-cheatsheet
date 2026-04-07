

# Setup

## What is Git?

Git is a distributed version control system (VCS).

It allows developers to:
- Keep a history of code changes
- Revert mistakes
- Collaborate with others
- Create backups of their code

---

## Porcelain vs Plumbing

Git commands are divided into two types:

### Porcelain (high-level, commonly used)

These are the commands you use most often:

    git status
    git add
    git commit
    git push
    git pull

### Plumbing (low-level)

These are more advanced internal commands:

    git apply
    git commit-tree
    git hash-object

---

## Configure Git

Git tracks who makes changes, so you must configure your identity.

### Set global configuration

    git config --global user.name "Your Name"
    git config --global user.email "you@example.com"
    git config --global init.defaultBranch main

- `--global` applies settings to all repositories on your system

---

## View Configuration

You can view your global Git configuration file:

    cat ~/.gitconfig

You can also list all configuration values:

    git config --list

---

## Notes

- Git has multiple configuration levels:
  - Global → applies to all repos
  - Local → applies to a specific repo
- Most of the time, you will use global configuration for your name and email

