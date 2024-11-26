2024-11-24 21:27

Status:

Tags: #Git/staging 

# Git Staging

Files in Git are either 
- tracked, Git know about these and they are added to the repository
- untracked, part of the working directory but not added to the repository 
```
touch index.html
```

Files are untracked until added to the staging environment and committed to the repository. 

During work, files will be edited, created or removed. When reaching a milestone, the changes should be staged. Staged files are ready to be committed.

```
git add index.html
```

# References
Source: [Git staging environment](https://www.w3schools.com/git/git_staging_environment.asp?remote=github)