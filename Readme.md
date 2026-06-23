# Git Commands Reference

## Setup

```bash
git init                  # Initialize a new repository
git clone <url>           # Clone a remote repository
```

## Stage & Commit

```bash
git add <file>            # Stage a specific file
git add .                 # Stage all changes
git commit -m "message"   # Commit staged changes
git commit -am "message"  # Stage tracked files and commit in one step
```

## Push & Pull

```bash
git push origin <branch>  # Push branch to remote
git push -u origin <branch> # Push and set upstream tracking
git pull                  # Fetch and merge remote changes
```

## Branches

```bash
git branch                # List local branches
git branch <name>         # Create a new branch
git switch <name>         # Switch to a branch
git switch -c <name>      # Create and switch to a new branch
git branch -d <name>      # Delete a branch (safe)
git branch -D <name>      # Force delete a branch
```

## Merge

```bash
git merge <branch>        # Merge a branch into the current branch
git merge --no-ff <branch> # Merge with a merge commit (no fast-forward)
git merge --abort         # Abort an in-progress merge
```

## Status & Log

```bash
git status                # Show working tree status
git log --oneline         # Show condensed commit history
git diff                  # Show unstaged changes
```
