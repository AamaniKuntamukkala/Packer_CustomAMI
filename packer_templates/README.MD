Troubleshooting Guide for Git and Packer
1. Git: Commit Not Showing Up
If your changes don't appear after committing:

Check commit history: git log --oneline

Ensure files were staged: git status → If unstaged, run git add .

Verify you're on the correct branch: git branch

Push changes to remote: git push origin <branch-name>

2. Git: "fatal: not a git repository" Error
If Git commands fail due to a missing repository:

Navigate to the project folder: cd /path/to/repo

Initialize a repository if needed: git init
