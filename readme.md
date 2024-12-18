# Git Commands

## Remove a Branch Locally and Remotely

### Locally:

```bash
git branch -d [[branch name]] # Delete a branch
# Use -D to force delete if the branch has unmerged changes:
git branch -D [[branch name]]
```

### Remotely:

```bash
git push origin :[[branch name]] # Push a delete command for the remote branch
```

## Switch to Another Branch Without Committing Changes

1. **Stash Changes:**

   ```bash
   git stash # Save changes to the stash
   ```

2. **Switch Branches:**
   ```bash
   git checkout [[branch name]] # Checkout the desired branch

   ```
