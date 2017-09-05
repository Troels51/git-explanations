## When something goes wrong
Sometimes you have staged a file that you do not really want to commit
```
git reset HEAD <file>
```
The file is still modified but it is not staged

### Unmodifiing a file
Sometimes you have changed a file, and you want to go back to your last commit
```
git checkout -- <file>
```
This will remove your modifications

### Amend a commit
If you have commit too early and want to add some files or rewrite the commit
```
(git add <file>)
git commit --amend
```