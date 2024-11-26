2024-11-25 13:02

Status:

Tags:

# Git Fetch

Git fetch gets the change history of a tracked branch/repo. So, on my local Git, fetch updates to see what's changed on GitHub

```git fetch origin
```

Once you have the recent changes, use;
```git status 
```
 to check the status

and;

```git log origin/main
```
to get details i.e. if the branch is behind then why?

and;

```git diff origin/main
```
to show difference between files(s)

# References
Source: [Git pull from GitHub](https://www.w3schools.com/git/git_pull_from_remote.asp?remote=github)