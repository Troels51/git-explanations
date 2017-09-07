# Squashing commits :fire:
To squash a series of commits into 1 commit
Be carefull, this rewrites history, do not do this if other people are using your history!
```
git rebase -i HEAD^(nr of commits to squash)
example:
git rebase -i HEAD^8
```

aaaa
bbbb

;ndring