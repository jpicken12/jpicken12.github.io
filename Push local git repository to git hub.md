2024-11-25 12:33

Status:

Tags: #Github #Git/push 

# Push local git repository to git hub

```git remote add origin https://github.com/jpicken12/hello-world.git
```
This command specifies that we're adding a remote repository, with the specified url as an origin for our local git repository.

Now, push the local git repo to the git hub repository, we'll push the main branch and set it as the default.

```git push --set-upstream origin main
```

# References
Source: [Git Github getting started](https://www.w3schools.com/git/git_remote_getstarted.asp?remote=github) 