## Branching and merging
```
git checkout -b <branch-name> # Creates new branchs and switches to it
"Code changes"
git commit -a -m "commit message"
...
...
...
git checkout master
git merge <branch-name>
```
git checkout -b is the same as
```
git branch <branch-name>
git checkout <branch-name>
```
A good explanation of the process is described here
https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging

### Deleting a branch
To delete a branch
```
git branch -d <branch-name>
```

### Listing branches
To see which branches are a in a repository
```
git branch -v
```
To filter the ones that have been merged into the branch you are in
```
git branch --merged
git branch --no-merged
```