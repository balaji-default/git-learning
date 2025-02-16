# Git Commands Guide

This guide provides a comprehensive overview of essential Git commands and workflows for managing local and remote repositories. Whether you're a beginner or an experienced developer, this guide will help you understand and use Git effectively.

## Table of Contents

Git Commands Guide

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

--- 1. Git Configuration ---
1. Set global username: git config --global user.name "Your GitHub Username"  
2. Set global email: git config --global user.email "your-email@example.com"  
3. View global username: git config --global user.name  
4. View global email: git config --global user.email  
5. List global configs: git config --global --list  
6. Set local username: git config user.name "Local Username"  
7. Set local email: git config user.email "local-email@example.com"  
8. List local configs: git config --local --list  

--- 2. Basic Workflow ---
9. Check Git version: git --version  
10. Initialize repo: git init  
11. Stage all files: git add .  
12. Commit changes: git commit -m "Initial commit"  
13. Link to remote: git remote add origin https://github.com/your-username/repo.git  
14. Rename branch to main: git branch -M main  
15. Push to remote: git push -u origin main  

--- 3. Cloning Repositories ---
16. Clone a repo: git clone https://github.com/your-username/repo.git  
17. View hidden files (Linux/macOS): ls -a  
18. View hidden files (Windows): Get-ChildItem -Force  

--- 4. Branch Management ---
19. List branches: git branch  
20. Create branch: git branch feature1  
21. Switch to branch: git checkout feature1  
22. Create + switch (legacy): git checkout -b feature2  
23. Create + switch (modern): git switch -c feature3  

--- 5. Merging & Syncing ---
24. Compare changes with main: git diff main  
25. Fetch updates: git fetch origin main  
26. Merge changes: git merge main  
27. Pull updates: git pull origin main  
28. Rebase onto main: git rebase main  

--- 6. Remote Operations ---
29. Push feature branch: git push origin feature1  
30. Delete remote branch: git push origin --delete feature1  

--- 7. Cleanup & Maintenance ---
31. Delete local branch: git branch -d feature1  
32. Force-delete branch: git branch -D feature3  
33. Prune stale branches: git fetch -p  

--- 8. Best Practices ---
- Always use feature branches.  
- Create Pull Requests (PRs) on GitHub.  
- Never push directly to `main`.  
- Enable branch protection rules on GitHub.  