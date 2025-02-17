# Git Commands Guide

Git is a distributed version control system that helps developers track changes in their codebase, collaborate with teams, and manage source code efficiently. This guide provides a comprehensive list of essential Git commands for setting up repositories, managing branches, syncing changes, and maintaining code hygiene. Whether you are a beginner or an experienced developer, these commands will streamline your workflow and enhance productivity.

## **Table of Contents**

**Table of Contents**

1. **Git Configuration**
2. **Basic Workflow**
3. **Cloning Repositories**
4. **Branch Management**
5. **Merging & Syncing**
6. **Remote Operations**
7. **Cleanup & Maintenance**
8. **Best Practices**

---

## 1. **Git Configuration**


### Set global username

```bash
git config --global user.name "Your GitHub Username"
```

### Set global email

```bash
git config --global user.email "your-email@example.com"
```

### View global username

```bash
git config --global user.name
```

### View global email

```bash
git config --global user.email
```

### List global configurations

```bash
git config --global --list
```

### Set local username

```bash
git config user.name "Local Username"
```

### Set local email

```bash
git config user.email "local-email@example.com"
```

### List local configurations

```bash
git config --local --list
```

---

## 2. **Basic Workflow**


### Check Git version

```bash
git --version
```

### Initialize a new repository

```bash
git init
```

### Stage all files for commit

```bash
git add .
```

### Commit staged changes

```bash
git commit -m "Initial commit"
```

### Link repository to a remote origin

```bash
git remote add origin https://github.com/your-username/repo.git
```

### Rename branch to main

```bash
git branch -M main
```

### Push changes to remote repository

```bash
git push -u origin main
```

---

## 3. **Cloning Repositories**


### Clone an existing repository

```bash
git clone https://github.com/your-username/repo.git
```

### View hidden files (Linux/macOS)

```bash
ls -a
```

### View hidden files (Windows)

```bash
Get-ChildItem -Force
```

---

## 4. **Branch Management**


### List all branches

```bash
git branch
```

### Create a new branch

```bash
git branch feature1
```

### Switch to an existing branch

```bash
git checkout feature1
```

### Create and switch to a new branch (legacy)

```bash
git checkout -b feature2
```

### Create and switch to a new branch (modern)

```bash
git switch -c feature3
```

---

## 5. **Merging & Syncing**


### Compare changes with main branch

```bash
git diff main
```

### Fetch updates from the remote repository

```bash
git fetch origin main
```

### Merge changes from main branch

```bash
git merge main
```

### Pull updates from remote repository

```bash
git pull origin main
```

### Rebase branch onto main

```bash
git rebase main
```

---

## 6. **Remote Operations**


### Push feature branch to remote repository

```bash
git push origin feature1
```

### Delete a remote branch

```bash
git push origin --delete feature1
```

---

## 7. **Cleanup & Maintenance**


### Delete a local branch

```bash
git branch -d feature1
```

### Force delete a branch

```bash
git branch -D feature3
```

### Prune stale branches from remote tracking

```bash
git fetch -p
```

### It lists proper removed branches

```bash
git branch -a
```

---

## 8. **Best Practices**


- Always use feature branches.
- Create Pull Requests (PRs) on GitHub.
- Never push directly to `main`.
- Enable branch protection rules on GitHub.

---
