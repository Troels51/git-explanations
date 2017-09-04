## Multiple user workflow without branching

User A
```
git clone <url>
"Changes to code"
git add <files changed>
git commit
git push
```
User B, clones before user A pushes
```
git clone <url>
"Changes to code"
git add <files changed>
git commit
git push <-- ERROR
git pull
git mergetool
git commit
```
If user B doesn't want to commit his code
```
"Changes to code"
git stash
git pull
git stash pop
"more code changes"
```