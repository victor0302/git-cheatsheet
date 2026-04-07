# Config

## Get a Value

You can retrieve a specific configuration value:

    git config --get user.name

---

## Unset a Value

You can remove a configuration value:

    git config --unset user.name

---

## Configuration Locations

Git configuration can exist in multiple places:

- System → /etc/gitconfig  
  Applies to all users on the system  

- Global → ~/.gitconfig  
  Applies to all repositories for a specific user  

- Local → .git/config  
  Applies to a specific repository  

- Worktree → .git/config.worktree  
  Applies to part of a project  

---

## Notes

- Use `--global` for settings like username and email  
- Use `--local` for project-specific configuration  
- Git allows duplicate configuration entries