# Git Commands Guide

This guide provides a comprehensive overview of essential Git commands and workflows for managing local and remote repositories. Whether you're a beginner or an experienced developer, this guide will help you understand and use Git effectively.

## Table of Contents

--- Table of Contents ---
1. Git Configuration  
2. Basic Workflow  
3. Cloning Repositories  
4. Branch Management  
5. Merging & Syncing  
6. Remote Operations  
7. Cleanup & Maintenance  
8. Best Practices  
-------------------------

## 1. Git Configuration

```bash
git config --global user.name "Your GitHub Username"
```
```bash
git config --global user.email "your-email@example.com"
```
```bash
git config --global user.name  # View global username
```
```bash
git config --global user.email  # View global email
```
```bash
git config --global --list  # List global configs
```
```bash
git config user.name "Local Username"
```
```bash
git config user.email "local-email@example.com"
```
```bash
git config --local --list  # List local configs
```

## 2. Basic Workflow

```bash
git --version  # Check Git version
```
```bash
git init  # Initialize repo
```
```bash
git add .  # Stage all files
```
```bash
git commit -m "Initial commit"  # Commit changes
```
```bash
git remote add origin https://github.com/your-username/repo.git  # Link to remote
```
```bash
git branch -M main  # Rename branch to main
```
```bash
git push -u origin main  # Push to remote
```

## 3. Cloning Repositories

```bash
git clone https://github.com/your-username/repo.git  # Clone a repo
```
```bash
ls -a  # View hidden files (Linux/macOS)
```
```bash
Get-ChildItem -Force  # View hidden files (Windows)
```

## 4. Branch Management

```bash
git branch  # List branches
```
```bash
git branch feature1  # Create branch
```
```bash
git checkout feature1  # Switch to branch
```
```bash
git checkout -b feature2  # Create + switch (legacy)
```
```bash
git switch -c feature3  # Create + switch (modern)
```

## 5. Merging & Syncing

```bash
git diff main  # Compare changes with main
```
```bash
git fetch origin main  # Fetch updates
```
```bash
git merge main  # Merge changes
```
```bash
git pull origin main  # Pull updates
```
```bash
git rebase main  # Rebase onto main
```

## 6. Remote Operations

```bash
git push origin feature1  # Push feature branch
```
```bash
git push origin --delete feature1  # Delete remote branch
```

## 7. Cleanup & Maintenance

```bash
git branch -d feature1  # Delete local branch
```
```bash
git branch -D feature3  # Force-delete branch
```
```bash
git fetch -p  # Prune stale branches
```

## 8. Best Practices

- Always use feature branches.  
- Create Pull Requests (PRs) on GitHub.  
- Never push directly to `main`.  
- Enable branch protection rules on GitHub.  
