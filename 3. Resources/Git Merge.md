2024-11-24 23:14

Status:

Tags: #Git/merge 

# Git Merge

Once you've finished your work on a branch, you can merge it with main.
```git merge emergency-fix
```
## Delete a branch
``` git branch -d emergency-fix
```
## Merge conflicts
If you try to merge a branch and a file has been changed since you took that version, you may get a conflict. This then shows in the files for example

<<<<<<< HEAD  
<p>This line is here to show how merging works.</p>  
=======

It seems that git shows the difference between these <<< and === tags.
- [ ] Explore Git conflicts in more detail

# References
Source: 